# Machine-Learning TD
By Corentin Meyer, PhD Student @ CSTB - iCube, 04/10 ESBS

# Prerequisite  
In this TD you will learn how to perform a full end-to-end data analysis using machine-learning. You will import and format biological data, create an AI model and evaluate its performances.  
However first you will need to get familiar with 3 prerequisites:  

1. **Git**  
Git is command-line software used in informatics to do code versioning (tracking modifications and updates). In any informatics project you WILL be using it. In this TD we will only use Git to download the TD Code from a GitHub Repository using the command:   
`git clone https://github.com/lambda-science/Machine-Learning-TD-ESBS.git`.  
This code will also be availiable on Moodle in a zip folder for people struggling with git.  

2. **Anaconda envrionnement**  
Anaconda is a python distribution and package manager. It is the prefered way for data-scientist to install Python. We will use Anaconda to install our **python environnement**. An environnement is a python installation with a specific set of library installed. This way we can insure that we all have the same package installed with the same version.  
In any Python project, you WILL be using Anaconda environnement. It's is crucial for reproductibility, sharing and tracking.  
**To install our environnement**  
If not already done, install Anaconda from: [Anaconda Download Page](https://www.anaconda.com/products/individual#Downloads)  
After cloning the Git repository, you will find a file named `environment.yml` containing all informations for the Anaconda envrionnement. You can now create the environnement using:  
`conda env create -f environment.yml`  
Note: If an error occurs such as `conda is not a valid command` you might need to use anaconda prompt for the command. Also environnement are heavy (1.5-2gb here) and can take some time to install.  
You can now activate your environnement in your current terminal using:  
`conda activate TD_ML`  

3. **Jupyter Notebooks**  
Jupyter Notebook is the main tool of any data-scientist. It allows you to write and run python code dynamically without reloading all the code, data and variables everytime.   
It is structured as blocks of code that you can run and edit independantly. In this TD, our main worksheet will be the `TD_Machine_Learning.ipynb` Jupyter Notebook.  
You have several option to open Jupyter Notebooks.  
**The Easy way:** Activate you conda env if not already done. Then run:   
`jupyter-notebook`  
You browser should automatically open a windows on Jupyter or you can simply click the link. Please check if you can open the ipynb file and the folder.  
Note: Don't close the terminal prompt as it would shutdown the Jupyter Server.  

### **Congratulations** you should now be ready to code for the TD.