# Code for the ML Editor from the book "Building Machine Learning Powered Applications" by Emmanuel Ameisen.

**The main github repo for the book can be found [here](https://github.com/hundredblocks/ml-powered-applications).**

Reasons for not just forking the original repo :

- Prefer to build the ML Editor from scratch (mistakes and all)
- The original repo is not organized by chapters which I wanted 

---
About the repo

- `'notebook'` folder contains the Jupyter notebooks, which illustrate the concepts
- `'ml_editor'` contains the code for the case study example 
- code names for files is based on when I came across it first in the book
- changed `'data'` folder name to `'raw_data'`

---
I used anaconda. Created a conda virtual environment, installed all required libraries. Installed the packages individually in the conda environment. List of commands is present in [`conda install commands`](./raw_data/conda_install_cmds.txt)

To run the app, navigate to the root of the repository and run:

`set FLASK_APP=app.py` 
`flask run`

It spins up a local web-app you can access at `http://127.0.0.1:5000/`

---
Output images from the sample run of ML Editor

### 1. Main page of ML Editor

![](https://github.com/vidyabhandary/BuildML/blob/main/imgs/ml1.PNG)

### 2. Model V1 - Sample Question

![](https://github.com/vidyabhandary/BuildML/blob/main/imgs/ml2.PNG)

### 3. Model V1 - Readability score

![](https://github.com/vidyabhandary/BuildML/blob/main/imgs/ml3.PNG)

### 4. Model V2 - Sample Question

![](https://github.com/vidyabhandary/BuildML/blob/main/imgs/ml4.PNG)

### 5. Model V2 - Question Score

![](https://github.com/vidyabhandary/BuildML/blob/main/imgs/ml5.PNG)

### 6. Model V3 - Sample Question

![](https://github.com/vidyabhandary/BuildML/blob/main/imgs/ml6.PNG)

### 7. Model V3 - Detailed Recommendations

![](https://github.com/vidyabhandary/BuildML/blob/main/imgs/ml7.PNG)

### 8. Model V3 - Another Recommendation example (Copied from writers.stackexchange.com)

![](https://github.com/vidyabhandary/BuildML/blob/main/imgs/ml8.PNG)
