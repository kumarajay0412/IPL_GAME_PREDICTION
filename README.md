# ML_Final_Project
**Setup**
In your Google Drive, create a directory with the name _"ML_Project"_ (No double quotes) and in it, copy both the CSV files in the datasets directory of this repository: MBM.csv and BBB.csv
Download the DreamTeam.ipynb file and open it using Google Colab

**Running**
Simply run all the cells in order. It might seem long and tedious, but several cells are essential and preprocess the data while giving several plots for better data visualization
The 5th last cell defines the dream team (using metrics defined in the cells before it) and calculates the team's features
The 4th last cell creates a dataset matching every team against our dream team
The 2nd last cell trains the dataset using an inbuilt Random Forest Classifier using our preprocessed datasets
The last set finally finds what percentage of matches our dream team wins (using a set of labels which say that our team should always win)
