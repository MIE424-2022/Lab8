# Lab8

## Creating an Environment from an environment.yml file

When a project is expected to be run across different machines, having the same environment as your collaborators is necessary to ensure that there are no package conflicts.
Fortunately, there exists a way to keep track of which packages were installed and how to set up an environment based on these packages. In Anaconda, this is the
environment.yml file. To create an environment based on the model, you need to run the following command: <code>conda env create -f environment.yml</code>.

## Using argsparse

In this Lab, we will be using a package called argsparse which comes preinstalled with python (like other libraries such as collections, etc.). The purpose of argsparse
is to be able to select variables for our code directly from the command line using flags. For example, if we wanted to run the code with 5 epochs, we will be able to
run the following command in our command line: <code> python main.py --epochs 5 </code>. This allows us to be more general when writing the code and then to chose these
parameters later on when we are running our code.
