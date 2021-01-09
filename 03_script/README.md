# My Datascience Pipeline
This folder structure contains my preferred workflow for a data science project.
This folder structure contains folder that do the following:
- libs: Maintains customs built libraries/modules that can be repurposed for other projects
- load: Contains functions that are responsible for base processing (i.e. importing and cleaning data into a tidy format) as well as analysis specific processing (e.g. for NLP)
- analyze: Stores all code for running the required analyses in your project (e.g. Kmeans, topic modeling, PCA, etc.)
- visualize: Holds code for running visualization for descriptives, exploratory, analytics-based, and reporting graphics
- aux_lang: this is a template folder for any auxillary language leveraged in this project. If the base language for this project was R, the python code would be stored in this folder with no structure as we assume you will not be writing nearly as much code for your auxillary languages as for your main language.

All of the functions stored in the folders listed above will be run from the main.R/py file. This file should contain only a few lines in the code for each step in the data science pipeline to make sure it is easy to source the pipeline in a concise manner. It allows you to run the pipeline in large steps as well, in case, you are walking someone through your project as a high-level. 
