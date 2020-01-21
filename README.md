# datascience-python-with-jupyter

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/8310fdb0e3e54dbe8c2b2ae8a4222a2a)](https://app.codacy.com/manual/TheDarkTrumpet/datascience-python-with-jupyter?utm_source=github.com&utm_medium=referral&utm_content=TheDarkTrumpet/datascience-python-with-jupyter&utm_campaign=Badge_Grade_Dashboard)

## Introduction

This repository is a selection of Jupyter notebooks that demonstrate various ways of loading, processing, and working with data within a Jupyter Notebook environment.

Why Jupyter?  I've worked with many wet-lab scientists, and I found that Jupyter is a very useful program to not only demonstrate how to work with their data, but also how to "play with" their data to learn more about it.  Jupyter supports a multitude of programming languages through the use of Kernels.  Including R, Python, C#, F#, and so on.  Jupyter isn't intended for making full blown programs, or libraries - but using existing libraries to interact with data.  This gives a huge benefit due to the technical curve being lower than other solutions.  Furthermore, from a scientific perspective - the code used, the documentation surrounding, and the results generated can appear in the documents.  These documents can be shared through email, exported to a number of file formats, or even access to the server given, to end users who need to interpret said data.

## Using and Getting Started

Eventually I'll include my setup scripts (which are largely developed already), that'll setup the environment for you.  But, for now, I recommend that you clone the repository and run `jupyter lab` within that directory and play with the examples.  Some scripts will require additional architecture largely outside this repository, but a lot of the data processing will include data sets within the repository so you should be able to run it without much difficulty.

Another option to see how Jupyter works is to open each ipynb file within github's browser.  One factor in my releasing and developing of this repository is that Github now supports rendering of Jupyter files within the browser.  While you can't edit the files directly and rerun, you can get a good idea of what you can do by just looking at the files.

Another option is to use Azure Notebooks.  Available at: https://notebooks.azure.com/  There will be some more instruction on this in the long run, but for now that's an unsupported option - but - it should work with most examples provided here.

## Contributing and Feedback

I appreciate any feedback people have to offer on any of my repositories.  The easiest way to provide feedback is to open an issue.  While I'm incredibly busy as of late, it shouldn't take too long for me to respond.

I also appreciate assistance in developing this repository.  If you have examples that you feel like a good fit, they should:
1.  Largely be self contained (no random libraries outside the core dependencies), and the data set should be contained with the repository and loading using relative URIs.
2.  Be documented.  This includes an introduction at the very top of each file that explains the purpose of it, any extra setup that may be required, and so on.
3.  Be organized.  One large cell with output is not useful to the end user to understand what's going on.  While there will have to be functions, pay attention to organization of your notebook.  Includes at the top, setup next, helper functions next, and interaction options at the bottom.  Remember, this repository is designed to be a teaching aid, so utilize the KISS (Keep It Simple Stupid) principle whenever possible.
    - Also note the directory structure. 
If you have example scripts you'd like to contribute, please create a pull request and add your notebooks.  Before doing the final commit, please "Restart Kernel and Run All Cells"  (Under the Run option in Jupyter Lab) and commit that result.  This ensures that the entire notebook can run from start to finish, and the results are included so people can review without rerunning themselves.
