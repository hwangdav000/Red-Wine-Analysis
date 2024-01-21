# Red Wine Analysis 
This was the capstone project for CSCI 5525 
[Red Wine Report](Red_Wine_Analysis.pdf)

This is a project using specififcally the red wine dataset from the vinho verde wine samples
where the objective is to link the wine's chemical to its overall quality.
[Red Wine Dataset](https://archive.ics.uci.edu/dataset/186/wine+quality)

Using this dataset I first clean the data and check for any missing values and drop any outliers. Then I 
check for class imbalance with the quality of the wine. To correct this I use
boxcox transformations. Then through exploration data analysis I perform 
correlation analysis and drop highly correlated features. 

For modeling the dataset I utilized 10 fold cross validation and used
- Gaussian Naive Bayes
- Multinomial Logistic Regression
- Neural Network

 For more information on the results please take a look at the paper.

 ![image](https://github.com/hwangdav000/Red-Wine-Analysis/assets/29682356/8cf83a90-2c14-4500-805b-ff168a96a65c)

 ![image](https://github.com/hwangdav000/Red-Wine-Analysis/assets/29682356/20b12479-6404-4004-bb8e-c39106184ab6)
 


