# Operations_Intelligence_CaseStudy


The following exercise will guide you through a typical transformation and data analysis to prepare data from an IT system for operation intelligence. 
The description is availabe in the pdf file.


## <a name="info">General info</a>
Repository Structure

- 'ADD_Tier-CaseStudy.ipynb' is the file you will be running in your Jupyter Notebook
- 'OI Case study - data.xlsx' is the data you will be importing in the Jupyter Notebook
- 'packagesADD.yml' are the list of requirements you will be installing in [GetStarted](#req) to be able to run the Jupyter Notebook 
- 'OI Case study - outline.pdf' is the document with the description of the excercise
- The folder '_images' containes the .png files generated in the notebook



## <a name="req">Get started</a>
### Installation

You will want to have Anaconda installed. More information here: https://docs.anaconda.com/anaconda/install/

The environment has been saved to the file: packagesADD.yml

1. Go to the directory in the commandline where you have placed this repo.

2. This file may be used to create an environment using:
-------------------
$ conda env create --file packagesADD.yml
-------------------

This environment was created using the platform: win-64 

3. Activate the enviroment with:
------------------
$ conda activate envADD
------------------

4. Open Jupyter notebook from your envADD active environment through your commandline with:
------------------
$ jupyter notebook
------------------

### Run on local machine

- Activate the environment using 
----------------
$ conda activate envADD
-----------------
- Open the file `ADD-Preprocess event data for analysis.ipynb` and run all cells

