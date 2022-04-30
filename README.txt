Elizabeth Ruddy
Computational Physics 5070
May 1, 2022
Wildfire Cause Classification

Included in this repository are two Jupyter notebooks. Collectively, they contain my project.
I was not able to upload the SQLite dataset to GitHub because it was too large. Therfore, the 
dataset should be imported from (https://www.kaggle.com/datasets/rtatman/188-million-us-wildfires)
before either of the Jupyter notebooks is run.

The first of the notebooks is Wildfire Data Analysis. This notebook includes some preliminary data 
analysis completed with the goal of exploring the dataset and investigating some of the relevant
features. The notebook includes many histograms and bar plots. This notebook can be run all the
way through and should run fairly quickly.

The second notebook is labeled Wildfire Cause Classification. The notebook follows my learning process
as I started fairly simple and then added complexity to the model as I went. There are various sections
to the notebook including an unsupervised learning section, a binary classification section which follows 
the Classification tutorial we did in class, and finally, a random forest classification section. 
The notebook can be run all the way through but sections of it (such as the hyper-parameters tuning 
section) will be fairly computationally expensive. That section took >1 hour to run on my laptop.
