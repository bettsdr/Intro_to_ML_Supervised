Using a dataset obtained from Kaggle which includes 4,680 images and labels of handwritten physician scripts, use a variety of classifier approaches to be able to classify these handwritten prescriptions into a common set of Generic Medicine Names or actual Medicine Names. There are 15 Generic Names in the dataset which are mapped from 78 actual Medicine Names.

The data set was sourced from Kaggle at the following URL - https://www.kaggle.com/datasets/mamun1113/doctors-handwritten-prescription-bd-dataset

This project is submitted by David Betts as the final project for CSCA5622.

The datasets loaded here in the folders include the data downloaded from Kaggle. There are a series of .csv files here in the repo which are incomplete as the training data files were too large for inclusion.
Upon launching and running the notebook, the MedData() constructor will check if all files required are present, and if so, it will load the class with pre-cleaned data from the disk. Otherwise, it will rebuild the data files from the source data within the folders.
This process to rebuild the data can take awhile, but once rebuilt, it will write all necessary files to local disk for easy access.

Motivation: I was once given an incorrect medication at a pharmacy from a handwritten prescription. While in this case, the outcome would have been at best uncomfortable, but at worst it could have been life-changing. Since that time, I am grateful for the advent of electronic prescription ordering which has taken the guesswork out of trying to decipher the notoriously bad handwriting of physicians. Nonetheless, this was the motivation for this project. Can a machine do better than a person with this task?

Observation: I have included my observations in the Jupyter notebook along with the models that I built to try to answer the core question, but at the end of the day, I concluded that, at least with these relatively brute force models, deciphering physicians' handwriting is still a relatively hard task.

Approach: I used multiple different classifiers throughout this project to see if I could get a good outcome. These include k-nearest neighbor classifiers, decision trees and support vector machines. I even tried a rudimentary neural network approach. The notebook contains the results of this exploration.

Conclusion: Either physicians' handwriting is truly indecipherable, and the notoriety is well deserved. Or, the models that I have deployed are simply not up to a challenging task. There are some additional observations about the approach and the data included in the notebook, and I will leave the reader to follow along.

Be forwarned that some of the analyses included in the notebook may take some time to run. I'm confident that if you have the libraries installed correctly, and patience (or a nearby coffeemaker) is in good supply, you can fiddle with the models further yourself and offer suggestions or changes that, perhaps, could make them fit better. For now, this was sufficient for me given my time allocation to this task. 

Please provide your feedback at david.betts@colorado.edu if you should have other ideas, insights or just want to share a perspective. 
