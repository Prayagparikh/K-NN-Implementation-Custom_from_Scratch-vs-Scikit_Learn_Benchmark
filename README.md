## K-NN Implementation
During my Machine Learning course CSE 6363 at the University of Texas at Arlington under Prof. Jesus Gonzalez, I completed my first Assignment,  where the professor wanted students to build K-Nearest Neighbor(K-NN) model from the scratch using python(without using Scikit-learn) and comparing that model with the model built using Scikit-learn. In this assignment, two values for k have been used k=3 and k=dataset_length/2 (reason is described in the YouTube video and link is in the References of the PDF report file).

## Accuracy using K-Fold cross validation
Accuracies are measured using k-fold, here 10-fold cross validation method, which is quite effective method for measuring accuracies.

## Datasets
1. Hayes Roth Dataset:
-> Find the Hayes roth dataset folder and the original files have been converted to .csv files for train and test datasets.
   Dataset download link: https://archive.ics.uci.edu/dataset/44/hayes+roth.

2. Breast Cancer Dataset:
-> Total 10 attributes in the data where the first column (no-recurrence-events/recurrece-events values) is the output class. String values of the attributes are converted to the integer values ranges in the code. For example no-recurrence-events=0 and recurrence-events=1. 
   Dataset download link: https://archive.ics.uci.edu/dataset/14/breast+cancer

3. Car evaluation Dataset:
->  Total 7 attributes where last column with 'unaccepted'/'accepted'/'good'/'vgood' is the class attribute with 4 possible values. Here also string values are converted to the respective integer values, so that it can be used further for the calculation for K-NN model, during eucledian_distance measurements, because integer values can be used to calculate distance and then sorting them in ascending order.
   Dataset download link: https://archive.ics.uci.edu/dataset/19/car+evaluation

## Results
Accuracies using 10-fold cross validation have been stated and described in the Final_Word_Report_PA1.pdf 

## Notes: 
1. Download all the required libraries from pip install before running files.
2. References to build this project have been mentioned at the end of Report pdf.

   

