# Multiple-Drug-Resistance Categorization & Case-Count Report Program

###### Author: Eric Zhewen Li

###### Boni Lab, Center for Infectious Disease Dynamics, Penn State Huck Institutes of the Life Sciences

###### Contact: eric@zhewenli.com

This repo contains all the Jupyter Notebook files showing the outcome measure calculation functions for the Multiple-Drug-Resistance (MDR) Analysis.

## Introduction

The main program, called `BoniLabMDR.ipynb`, contains a series of functions that parses, processes, and analyzes the output txt file from Boni Lab's stochastic Malaria simulation models. The program also provides a series of visualizations to intuitively show the emergence of drug-resistance for Malaria.

The program is open-sourced under MIT License. There is much freedom with MIT License, but you must include the original license here and properly cite this as your source.

## How to use the program

The program, written in Python, is available and presented by Jupyter Notebook and hence in `ipynb` format. You can either download the file and run it locally, or you can use [Google Colab](https://colab.research.google.com) (recommended) to open and run, by using its GitHub import function.

When you open the program, go to the "Main Function - Start Here" section, where it shows a sample scenario of the program usage prepared by me. If you would like to run the program using your own file, you need to first run all the functions defined in the "Function defs" section, uploading your file if you are using Google Colab, and change variable to the your filepath. Then you can use the program and get results by calling corresponding functions with proper arguments.

## About archives

This program could not be developed without my Summer Internship at Boni Lab of Penn State's CIDD. All the testing codes and notebooks (May-Aug 2019) are archived in the folder for references. A separate data-visualization web app is also under development.