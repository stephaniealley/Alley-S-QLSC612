# Installation
The code, analysis, and figures included in this project are contained in a Jupyter notebook (myanalysis) in Command_Files. The python dependencies required are provided in Documents/requirements.txt. The specific Python 3 version used is 3.7.6.

Create Python virtual environment:

`python3 -m venv /path/to/new/virtual/env`

Activate virtual environment:

`source /path/to/new/virtual/env/bin/activate`

Install dependencies:

`pip install -r requirements.txt`

# Usage
The analysis can be performed by running the Jupyter notebook.

# Expected output
The notebook will generate the following statistical tests:
* F test
* Analysis of variance (ANOVA)
* Compare F test

The following figures will be generated within the notebook:
* Partial regression
* Detailed regression plots for FSIQ, including Y and Fitted vs X, Residuals versus FSIQ, Partial regression, and CCPR
