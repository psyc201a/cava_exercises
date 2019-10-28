## PSYC 272: Computational Approaches to Visual Abstraction
### Technical Exercise \#3

This exercise is a 'conceptual replication' of a key analysis in Fan, Yamins, & Turk-Browne (2018).

#### Procedure:

1. Review the following sources of our analysis approach and data: 
- analysis: Fan, J. E., Yamins, D. L., & Turk‐Browne, N. B. (2018). Common object representations for visual production and recognition. Cognitive Science, 42(8), 2670-2698.
- data: Sangkloy, P., Burnell, N., Ham, C., & Hays, J. (2016). The sketchy database: learning to retrieve badly drawn bunnies. ACM Transactions on Graphics (TOG), 35(4), 119.
- model: VGG-19 from Simonyan & Zisserman (2014), re-implemented by torchvision developers with PyTorch.

2. Download dataset from SSRDE.
- If you are on a Mac, open up Terminal and make sure you can ssh into SSRDE: `ssh ADUSERNAME@ssrde.ucsd.edu`. Use your UCSD AD password.
- If you can't, try establishing a VPN connection to UCSD. 
- Once you're in, inspect the location of the dataset: `ls /sscf/ssrde-storage/personal/psyc272cava/`. Is there a directory named `features` there? If so, good!
- On your local machine, navigate via the Terminal to the location of this technical exercise. 
- If there is no directory called `features` that currently exists, create one by running the command: `mkdir features`.
- We are going to transfer the dataset from SSRDE to a target location on your machine.
To do this, run: `rsync -azvh ADUSERNAME@ssrde.ucsd.edu:/sscf/ssrde-storage/personal/psyc272cava/exercise3-sketch/features/ ./features/`.

3. Download assignment starter code by cloning this repo or downloading as zipped folder.
- Launch jupyter notebook server from the `exercise3-sketch` directory.
- Submit assignment files by 4pm on 11/11 via file upload on Canvas, replacing `yourname` with your UCSD AD username.
   - `psyc272-cava-sketch-yourname.ipynb`

**Note:**
There are START OF YOUR CODE & END OF YOUR CODE tags denoting the start and end of code sections you should fill out. 

This code has been tested to be compatible with python version 3.7. You will need to make sure that during your virtual environment setup (managing your python environment using conda is recommended) that the correct version of python is used. 

#### Resources:
- Quick Intro to Pandas: https://towardsdatascience.com/a-quick-introduction-to-the-pandas-python-library-f1b678f34673
- Learn about Seaborn plotting library: https://seaborn.pydata.org/
- PyTorch torchvision package: https://pytorch.org/docs/stable/torchvision/index.html
