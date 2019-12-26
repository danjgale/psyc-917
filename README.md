# PSYC 917: Introduction to Cognitive Neuroimaging

Hello! Welcome to the PSYC 917 repository. Here you will find all of the tutorial notebooks used in the course. 

## Overview

The course teaches the basics of fMRI analysis and is aimed at first-year graduate students that may have some prior programming experience. The course uses Python because we believe that Python currently offers the best available tools out there for fMRI. However, _this is not a programming course_, and students are not expected to be proficient in Python. Pretty much all of the code is provided so that students can focus on the concepts rather than get lost in implementation (which will be saved for their own time and research projects ;)). All of the excercises done at the end of each tutorial involve copying and tweaking the provided tutorial code.

## Set Up

### 1. Downloading the repository 

First, you'll want to download the repository, which can be done by the bright green button at the top right of the page. Click on `Download Zip`. Once downloaded, extract the zip file and move the repository folder to a location of your choice. 

### 2. Downloading the Data

The courses uses data from [Gorgolewski et al (2013)](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3641991/), which can be downloaded from OpenNeuro [here](https://openneuro.org/datasets/ds000114/versions/1.0.1). Click on `Download`, which will take you to a second page where you can download the data using your browser. 

The data will be downloaded as `ds000114-1.0.1` (or something similar). Once downloaded, unzip the folder to extract the data. **Rename the folder to `data` and move this folder to inside the repository folder**. The `data` folder should exist inside the repository, alongside the rest of the files.

### 3. Anaconda

This course assumes that you have Python 3 installed using [Anaconda](https://www.anaconda.com/). Please ensure that you install the **Python 3.7** distribution for your operating system. If you do not wish to rely on Anaconda, you can simply install the dependencies (see 2) below).

All dependencies are found in `requirements.txt` and can be installed by running `pip install -r requirements.txt`. With Anaconda, many of these will already be installed. You _do not need to install the dependencies right away_, as we'll be installing them together in the first lesson. 

## Resources

There are plenty of resources available online for Python, and some for both Python and fMRI. We recommend the following (see also the last section in `1_Intro_to_Python.ipynb`):

1. [Scipy Lectures](https://scipy-lectures.org/)
2. [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/) and the [accompanying repository](https://github.com/jakevdp/PythonDataScienceHandbook)
3. The Python tutorial in [A First Course in Network Science](https://github.com/CambridgeUniversityPress/FirstCourseNetworkScience/blob/master/tutorials/Appendix%20-%20Python%20Tutorial.ipynb)

Once you've familiarized yourself with Python and fMRI in the first couple of weeks, we **highly recommend** diving into the [Nilearn documentation](https://nilearn.github.io/index.html). The documentation isn't just code documentation; it has a number of tutorials and code examples for a variety of different aspects of fMRI.


