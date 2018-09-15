# DEEPSIG DATASETS

This repository is a collection of references and software regarding:

- https://www.deepsig.io/datasets/

DeepSig has created a small corpus of standard datasets which can be used for original and reproducible research, experimentation, measurement and comparison by fellow scientists and engineers.

These datasets allow machine learning researchers with new ideas to dive directly into an important technical area without the need for collecting or generating new datasets, and allows for direct comparison to efficacy of prior work.

Please reference the above page or our relevant academic papers when using these datasets.

## LICENSE NOTICE

All datasets provided by Deepsig Inc. are licensed under the [Creative Commons Attribution - NonCommercial - ShareAlike 4.0 License (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/). If an alternative license is needed, please contact [info@deepsig.io](mailto:info@deepsig.io).

# DEEPSIG DATASET: RADIOML 2016.10A

A synthetic dataset, generated with GNU Radio, consisting of 11 modulations (8 digital and 3 analog) at varying signal-to-noise ratios. This dataset was first released at the 6th Annual GNU Radio Conference.

This represents a cleaner and more normalized version of the 2016.04C dataset, which this supersedes.  The file is formatted as a "pickle" file which can be open for example in python by using `cPickle.load(...)`.

- Signal Generation Software: [https://github.com/radioML/dataset](https://github.com/radioML/dataset)
- Dataset Download: [RML2016.10a.tar.bz2](http://opendata.deepsig.io/datasets/2016.10/RML2016.10a.tar.bz2)
- Larger Version (including AM-SSB): [RML2016.10b.tar.bz2](http://opendata.deepsig.io/datasets/2016.10/RML2016.10b.tar.bz2)
- Example ClassifierJupyter Notebook: [RML2016.10a_VTCNN2_example.ipynb](https://github.com/radioML/examples/blob/master/modulation_recognition/RML2016.10a_VTCNN2_example.ipynb)

## DEEPSIG DATASET: RADIOML 2016.04C

A synthetic dataset, generated with GNU Radio, consisting of 11 modulations. This is a variable-SNR dataset with moderate LO drift, light fading, and numerous different labeled SNR increments for use in measuring performance across different signal and noise power scenarios.

This dataset was used for the "[Convolutional Radio Modulation Recognition Networks](https://arxiv.org/abs/1602.04105)" and "[Unsupervised Representation Learning of Structured Radio Communications Signals](https://arxiv.org/abs/1604.07078)" papers, found on the [DeepSig Publications Page](https://www.deepsig.io/publications)

There are three variations within this dataset with the following characteristics and labeling:

Dataset Download: [2016.04C.multisnr.tar.bz2](http://opendata.deepsig.io/datasets/2016.04/2016.04C.multisnr.tar.bz2)

## Docker container

The [dockerRML](https://github.com/sofwerx/dockerRML) container was used to generate the above dataset.
