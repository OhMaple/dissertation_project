# dissertation_project
Dissertation project for BSc Computer Science 2023

This project contains 2 finished audio classification models with the purpose of identifying and classifying respiratory illnesses.
The following is how the project is organised:

---------------------------

## Folders:

Data: Due to space restrictions, this file contains the altered COPD dataset. 

Final Products: This folder contains the code used to produce the final trained models, with 'Respiratory CNN (1.0) - MFCC' being the notebook used to create
the model trained on features extracted using Mels Frequency Cepstral-Coeffecient, 'Respiratory CNN (1.3.1) - ML' being the notebook used to create the
machine learning model trained on self-learnt features. 'MFCC Model' is the trained model file for the MFCC notebook. 'Average Files' is the code
used in order to find the average number of files in each class folder, and randomly choose this amount of files from the COPD dataset, to create a new,
smaller dataset.
Finally 'Final Gantt Chart' is a PNG file of the finalised Gantt Chart.

Previous Attempts: This folder contains previous previous notebooks created during the process of the project, that did not result in
successful trained models.

---------------------------

## How to run the Models:

- Install and set up an IDE that supports IPython Notebooks such as PyCharm or Jupyter Notebook, and a Python environment (such as Anaconda).
- Open up the root folder of the project (the main folder containing all other folders including this text file) within your chosen IDE.
- Open one of the two trained model notebooks and run all the cells.

If dependencies are missing:
If a library is missing, for example tensorflow, create a new cell/code block and type:

!pip install tensorflow (replace tensorflow with the name of the desired library if needed)

Wait for the install to finish, and run the initial cell once again.
