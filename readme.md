## Introduction

In this notebook, you'll use the [Pomegranate](https://github.com/jmschrei/pomegranate) library to build a hidden Markov model for part of speech tagging with a [universal tagset](http://www.petrovi.de/data/universal.pdf). Hidden Markov models have been able to achieve >96% tag accuracy with larger tagsets on realistic text corpora. Hidden Markov models have also been used for speech recognition and speech generation, machine translation, gene recognition for bioinformatics, and human gesture recognition for computer vision, and more.

## Basic Instructions

1. Open a terminal and clone the project repository:
```
$ git clone https://github.com/nayan3090/Part-of-Speech-Tagger.git
```

2. Switch to the project folder and create a conda environment (note: you must already have Anaconda installed):
```
.../ $ conda env create -f hmm-tagger.yaml
```

3. Activate the conda environment, then run the jupyter notebook server. (Note: windows users should run `activate hmm-tagger`)
```
.../ $ source activate hmm-tagger
(hmm-tagger) .../ $ jupyter notebook
```
