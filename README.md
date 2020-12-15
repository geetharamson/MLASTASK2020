# MLASTASK2020
### Author : GEETHA KARTHIKESAN (G00376320@gmit.ie)
### Repository: [GitHub](https://github.com/geetharamson/MLASTASK2020.git)
Machine Learning And Statistics module, Data Analytics Course, GMIT 2020
This repository contains one single jupyter notebook called TASKSMLS.ipynb which contains my solutions to four tasks that were assigned in this semester. Each task is  contained within its own section of the notebook with the references, I had used for research is at the end of each task section. 

---------------------------------
## HOW TO DOWNLOAD THE REPOSITORY
* Go to GitHub.
* Go to my repository: [GitHub](https://github.com/geetharamson/MLASTASK2020.git)
* Click the [`Code`](#code) button which is colored green.
* Click on HTTPS and copy the link that is shown.
* Open the command line on your machine, navigate to the directory where you would like to clone the repository down to.
* Enter the command: git clone followed by the URL of the repository.
* The repository will be cloned down to your current working directory.
* You will need to navigate to this folder location on the command line in order to run the program.
* Details on how to view my jupyter notebook are described in the next section below.
__________________________
## How to run the jupyter notebook
___________________________
+ On the command line navigate to the folder location where the repository has been downloaded and saved to using the cd change directory command.
+ Type jupyter notebook on the command line and press enter
+ After a short wait jupyter notebook will open in your web browser.
+ Open the **TASKSMLS.ipynb** notebook in the browser and the notebook containing the code and comments that I wrote for this assignment will be displayed.
+ If you want to run the code in any cell hold down the shift key and press enter and the command will run and the output wil be displayed in the next cell.
+ To change between edit and read mode at any time press the ESC key.
+ If you wish t run the entire notebook click Kernel in the toolbar at the top of the screen and then click Restart and run all. The notebook will refresh and all code cells will be executed from top to bottom.
+ When you have finished viewing the jupyter notebook close the web browser and return to the command line. Press Ctrl + C on the command line to kill the program.
______________________________________________________________
The software can be downloaded and run on a machine as follows:

Clone the repository with the following command
      
     git clone [GitHub](https://github.com/geetharamson/MLASTASK2020.git)

Run Jupyter Notebooks from the repository with the following command:

     jupyter notebook

Jupyter Notebooks should open in your default web browser!

    # Task 1
Write a Python function called sqrt2 that calculates and prints to the screen the square root of 2 to 100 decimal places. Your code should not depend on any module from the standard library or otherwise. You should research the task first and include references and a description of your algorithm.

    # Task 2
The Chi-squared test for independence is a statistical hypothesis test like a t-test. It is used to analyse whether two categorical variables are independent. The Wikipedia article gives the table below as an example, stating the Chi-squared value based on it is approximately 24.6. Use scipy.stats to verify this value and calculate the associated p value. You should include a short note with references justifying your analysis in a markdown cell.
 
 
|               |     A   |    B   |    C   |   D  |  TOTAL  |
| ------------- | --------| ------ | ------ |----- | --------|
| White Collar  |    90   |   60   |   104  |  95  |  349    |
| Blue Collar   |    30   |   50   |    51  |  20  |  151    |
| No Collar     |    30   |   40   |    45  |  35  |  150    |
| Total         |    150  |  150   |   200  | 150  |  650    |




    # Task 3

The standard deviation of an array of numbers x is calculated using numpy as np.sqrt(np.sum((x - np.mean(x))** 2)/len(x)) . 
However, Microsoft Excel has two different versions of the standard deviation calculation, STDDEV.P and STDDEV.S. The STDDEV.P function 
performs the above calculation but in the STDDEV.S calculation the division is by len(x)-1 rather than len(x).

    # Task 4

Use **scikit-learn** to apply  *k-means clustering to Fisher’s famous Iris data set*. You will easily obtain a copy of the data set online. Explain in a Markdown cell how your code works and how accurate it might be, and then explain how your model could be used to make predictions of species of iris.


 Geetha Karthikesan :rocket:
