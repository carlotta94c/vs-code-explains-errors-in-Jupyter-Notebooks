# Copilot Explains - Error troubleshooting in Jupyter Notebooks

Data scientists and AI engineers love to work with Jupyter Notebooks because they make so much easier to look at the result of each and every data exploration step or data modeling experiment and take decisions accordingly.
However, Jupyter notebooks are not immune to errors and sometimes understanding error messages - in particular if you aren’t a native English speaker or you are a beginner - and troubleshooting code might be painful and time consuming. 

In this repo, you'll find the code shown in [Copilot Explains Episode 6: Error troubleshooting in Jupyter Notebooks]().

The original Jupyter Notebook (version without errors) along with the related documentation is taken from [Lesson 4 - Logistic Regression](https://github.com/microsoft/ML-For-Beginners/tree/main/2-Regression/4-Logistic) of the [Machine Learning for Beginners](https://github.com/microsoft/ML-For-Beginners/) open-source curriculum.

⚠️ **The notebook included in this repo contains errors for didactic purposes, so it will not execute successfully as it is.** You can use this as a base to follow along with the [video content]() and troubleshoot the errors with GitHub Copilot and VS Code. 

## Pre-requisites
To replicate the demo, you need the following pre-requisites:
1. Install [VS Code](https://code.visualstudio.com/) on your machine
2. Sign up for a [GitHub Copilot free trial](https://github.com/github-copilot/signup) 
3. Install [GitHub Copilot](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot) and [GitHub Copilot Chat](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot-chat) extensions on VS Code
4. Install the Python extension 
5. [Create a virtual environment](https://code.visualstudio.com/docs/python/environments#_using-the-create-environment-command) with [numpy](https://pypi.org/project/numpy/) and [pandas](https://pypi.org/project/pandas/) packages installed

## Errors
[Copilot Explains episode 6] covers 3 types of common errors when working with Python in Jupyter Notebooks.

### 1. Indentation Error
Whereas in other programming languages the indentation in code is for readability only, the indentation in Python is very important. Python uses indentation to indicate a block of code, so you have to use the same number of spaces in the same block of code, otherwise Python will give you an error, like in the example below.
![Indentation Error Example](https://github.com/carlotta94c/vs-code-explains-errors-in-Jupyter-Notebooks/assets/82521518/31e021b7-43ac-4e00-8a88-b31f33bd1151)

### 2. Module Not Found Error
When you try to import in your code a library that is not installed in your development environment, you'll encounter a _ModuleNotFound_ error. In our example below, we are trying to use the [seaborn](https://seaborn.pydata.org/) library, which is not installed in our venv.
![Module Not Found Error Example](https://github.com/carlotta94c/vs-code-explains-errors-in-Jupyter-Notebooks/assets/82521518/8257b836-6a2e-4618-9b11-4501ddb59838)

### 3. Name Error
_NameError_ usually occurs when you try to use a variable that has not been defined before usage or it's out of scope. Sometimes it can be due simply to a typo, making the variable name declared and used not match, as in the code cell below.
![Name Error Example](https://github.com/carlotta94c/vs-code-explains-errors-in-Jupyter-Notebooks/assets/82521518/77e78a1c-bb63-449f-a16a-e039e17eec73)




