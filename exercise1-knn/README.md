## PSYC 272: Computational Approaches to Visual Abstraction
### Technical Exercise \#1

This exercise is adapted from [Stanford's CS231n](http://cs231n.stanford.edu/):

#### Procedure:
1. Read Stanford CS 231n course notes on image classification. Ask questions and discuss concepts with your neighbors as you go through the material.
 - Intro to image classification: http://cs231n.github.io/classification/

2. Set up your computing environment. If you have already done this, please help your fellow classmates who have not or are less familiar with these tools. 
 - Download Anaconda: Anaconda Distribution Python 3.7
 - Getting started with Anaconda: https://docs.anaconda.com/anaconda/install/
 - Recommended: download/install a fully featured text editor: e.g., Sublime or Atom or VS Code. 

3. Download assignment starter code by cloning this repo or downloading as zipped folder.
- Download CIFAR-10 dataset
  Open the Terminal app and navigate to this repo using `cd` then run the included bash script to download data.
```
  cd /exercise1-knn/psyc272cava/datasets/
  ./get_datasets.sh
```
- Launch jupyter notebook server from the `exercise1-knn` directory.
- Submit assignment files by 4pm on 10/7 via file upload on Canvas
   - `psyc272-cava-knn-yourname.ipynb`
   - `k_nearest_neighbor.py`

**Note:**
There are START OF YOUR CODE & END OF YOUR CODE tags denoting the start and end of code sections you should fill out. 

This code has been tested to be compatible with python version 3.7. You will need to make sure that during your virtual environment setup (managing your python environment using conda is recommended) that the correct version of python is used. 

#### Tips:
- If you run into an error where you can't import the module `past`, you may need to run this command in your Terminal: 
`pip install future`

#### Resources:
 - Python for R users (Datacamp): https://www.datacamp.com/courses/python-for-r-users
 - Jupyter: https://medium.com/codingthesmartway-com-blog/getting-started-with-jupyter-notebook-for-python-4e7082bd5d46
 - Python/NumPy: http://cs231n.github.io/python-numpy-tutorial/ 
 - 3Blue1Brown on Calculus: https://www.youtube.com/playlist?list=PLZHQObOWTQDMsr9K-rj53DwVRMYO3t5Yr
 - MIT OCW on Calculus:  https://ocw.mit.edu/resources/res-18-006-calculus-revisited-single-variable-calculus-fall-2010/course-introduction/ 
 - Deep Learning Book on Linear Algebra: https://www.deeplearningbook.org/contents/linear_algebra.html
 - Metacademy for everything else: https://metacademy.org/ 
