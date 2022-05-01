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

The second notebook is labeled Wildfire_Cause_Classification. The notebook follows my learning process
as I started fairly simple and then added complexity to the model as I went. There are various sections
to the notebook including an unsupervised learning section, a binary classification section which follows 
the Classification tutorial we did in class, and finally, a random forest classification section. 

The Wildfire_Cause_Classification notebook can be run all the way through but sections of it (such as 
the hyper-parameters tuning section) will be very computationally expensive. That section takes multiple 
hours to run on my laptop. That section could be sped up by increasing n_jobs when calling the 
RandomSearchCV function. n_jobs = 2 was the most that my laptop could handle without shutting down but 
other computers may be able to handle more. If you wish to run the entire project quickly, I recommend 
commenting out the hyperparameter tuning sections. It makes sense that the dataset training, and 
especially the tuning, takes a long time because the dataset has around 1 million datapoints in it.

Note: I tried to make a unit testing suite in a separate notebook/Python file that would test the main
code base. Unfortunately, I could not figure out a way to unit test the main notebook without re-running
it which would have taken many more hours. Instead, I decided to include the unit testing suite at the 
bottom of the main code-base notebook to save some time. I understand the advantage of having a separate
test suite, however, and in a more official project setting, I would do that instead. 

Thanks for a great class! I feel like I learned a lot. 
