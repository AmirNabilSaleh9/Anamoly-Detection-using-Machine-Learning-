# Anamoly-Detection-using-Machine-Learning-
Dataset Preprocessing

The code is tested on the reduced version of AWID2 dataset with 154 features

The performed preprocessing operations are: 

1.	Replace the '?' string in the DataFrame with a NumPy NaN value

2.	Drop the column that has over 60% of its values is null, 

3.	Drop the columns that have over 50% of its values as Constant

4.	Remove columns with no variation (zero values or only one unique value in it)

5.	If there are no values or only one unique value in a column,
remove that column because it is not useful for distinguishing between normal and attack type

6.	Drop the rows with at least one nan value in it


Notes 

•	The output number of features are 59 + the class label

•	The output file name is preproc_dataset

•	I developed two versions , first deals with CSV files and the second one deals with a compressed version of the input dataset 
