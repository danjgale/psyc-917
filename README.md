# PSYC 917: Introduction to Cognitive Neuroimaging

Hello! Welcome to the PSYC 917 repository. Here you will find all of the tutorial notebooks used in the course. 

## Overview

The course teaches the basics of fMRI analysis and is aimed at first-year graduate students that may have some prior programming experience. The course uses Python because we believe that Python currently offers the best available tools out there for fMRI. However, _this is not a programming course_, and students are not expected to be proficient in Python. Pretty much all of the code is provided so that students can focus on the concepts rather than get lost in implementation (which will be saved for their own time and research projects ;)). All of the excercises done at the end of each tutorial involve copying and tweaking the provided tutorial code.

## Outline

| Week | Topic                                    | Lesson    |
|------|------------------------------------------|-----------|
| 1    | Introduction Lecture & course overview   | N/A       |
| 2    | Principles of fMRI Design and Analysis   | 1 + 2     |
| 3    | Temporal processing                      | 3         |
| 4    | Spatial Processing                       | 4         |
| 5    | First-level analysis                     | 5         |
| 6    | Second-level analysis                    | 6         |
| 7    | Reading Week                             | N/A       |
| 8    | ROI-based analyses                       | 7         |
| 9    | MVPA 1: Pattern Classification           | 8         |
| 10   | MVPA 1: Representational similarity      | 9         |
| 11   | Research Project week                    | N/A       |
| 12   | Functional Connectivity 1                | 10        |
| 13   | Functional Connectivity 1                | 11        |

## Set Up

### 1. Downloading the repository 

First, you'll want to download the repository, which can be done by the bright green button at the top right of the page. Click on `Download Zip`. Once downloaded, extract the zip file and move the repository folder to a location of your choice. 

### 2. Getting the Data

The course uses data from a localizer experiment we've collected. The total dataset (raw and preprocessed versions) is ~16GB. The data is stored on a USB key and will be available to everyone.

Once you've got the data, place the folder in the repository alongside the notebooks.

### 3. Anaconda

This course assumes that you have Python 3 installed using [Anaconda](https://www.anaconda.com/). Please ensure that you install the **Python 3.11** distribution for your operating system. You can try more recent versions, but this course has been developed and tested to work with `3.11`. If you do not wish to rely on Anaconda, you can simply install the dependencies (see 2) below).

All dependencies are found in `requirements.txt` and can be installed by running `pip install -r requirements.txt`. With Anaconda, many of these will already be installed. You _do not need to install the dependencies right away_, as we'll be installing them together in the first lesson. 

## Resources

There are plenty of resources available online for Python, and some for both Python and fMRI. We recommend the following (see also the last section in `1_Intro_to_Python.ipynb`):

1. [Scipy Lectures](https://scipy-lectures.org/)
2. [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/) and the [accompanying repository](https://github.com/jakevdp/PythonDataScienceHandbook)
3. The Python tutorial in [A First Course in Network Science](https://github.com/CambridgeUniversityPress/FirstCourseNetworkScience/blob/master/tutorials/Appendix%20-%20Python%20Tutorial.ipynb)

Once you've familiarized yourself with Python and fMRI in the first couple of weeks, we **highly recommend** diving into the [Nilearn documentation](https://nilearn.github.io/index.html). The documentation isn't just code documentation; it has a number of tutorials and code examples for a variety of different aspects of fMRI.


