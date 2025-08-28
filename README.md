# The Wisdom of Crowds and resilience to mis- and disinformation study
## Data analysis repository

This repository contains the code for analysing the results of the pre-registered [Wisdom of Crowds and Resilience to mis- and disinformation study](https://osf.io/mjsh5/) by the Australian [Digital Trust Research Group](https://www.digitaltrustresearch.com/). The study looks at the effects on a testimonial network when the central nodes of the network are unreliable, with a special focus on the use of the [Wisdom of Crowds package](https://github.com/cvklein/wisdom-of-crowds) to study features of network structure that may help or hinder with dealing with mis- and disinformation. More detail of the aims and methods of the study is to be found in the [study's preregistration](https://osf.io/mjsh5/).

The study is performed by running simulations using the [Polygraphs package](https://github.com/alexandroskoliousis/polygraphs/). This repository has already extracted the data from the Polygraphs processors and has stored it in pickled DataFrames (_*.pkl_ and _*.xz_), to be manipulated by _unreliable-nets-analysis.ipynb_. 

Other than the already mentioned pickled files, the other file (_centrality.json_) contains network centrality data that was analysed before starting the simulations, and that is referred to by this code.