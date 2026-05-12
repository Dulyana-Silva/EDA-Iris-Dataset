## About Iris Dataset
This Dataset is one of the most famous and widely used datasets in machine learning and data analysis, introduced by British statistician and biologist Ronald Fisher in 1936.

<img width="890" height="300" alt="image" src="https://github.com/user-attachments/assets/53a8e4a5-50e8-4567-a696-122cc8742e70" />

---

It contains 150 samples of iris flowers, evenly split across 3 species (50 samples each):
- Iris setosa
- Iris versicolor
- Iris virginica

There are 5 Attributes (Features) in the dataset :
- Petal length
- Petal width
- sepal length
- sepal width
- Species of the flower

All numaric values are measured in cm.

## Exploratory Data Analysis on Iris Dataset

EDA is a technique to analyze data using visuals. By conducting an EDA, We can get detailed information about the statistical summary of the data. We will also be able to deal with the duplicates values, outliers and also see some trends or patterns present in the dataset.

### Relation between Variables.

1). <img width="550" height="380" alt="image" src="https://github.com/user-attachments/assets/528bec4b-4ed8-4659-a9ed-4fd86fc83276" />

#### Interpretation
- Setosa species has smaller sepal lengths but larger sepal widths.
- Versicolor species lies in the middle of the other two species in terms of sepal length and width.
- Virginica species has larger sepal lengths but smaller sepal widths.

--- 
2). <img width="550" height="380" alt="image" src="https://github.com/user-attachments/assets/f65e75ff-5191-4197-97ae-14c5e1f55852" />

#### Interpretation
- Setosa species has smaller petal lengths and widths.
- Versicolor Species lies in the middle of the other two species in terms of petal length and width.
- Virginica species has the largest of petal lengths and widths.

--- 

3). Pairplot shows relationships between all the attributes (columns). It can be used for multivariate analysis.
<img width="700" height="500" alt="image" src="https://github.com/user-attachments/assets/c4fb9e80-03ee-4f1a-97d9-ef84091933a1" />

#### Interpretation
- We can see many types of relationships from this plot such as Setosa species has the smallest of petals widths and lengths. 
- It also has the smallest sepal length but larger sepal widths. Such information can be gathered about any other species.

---

4). Histogram shows the distribution of the data in relevant columns. It can be used for uni and bi-variate analysis.
<img width="500" height="450" alt="image" src="https://github.com/user-attachments/assets/92b6b5f6-02b0-4371-bed9-fede18d2bb8d" />

#### Interpretation
- The highest frequency of the sepal length is between 30 and 35 which is between 5.5 and 6
- The highest frequency of the sepal Width is around 70 which is between 3.0 and 3.5
- The highest frequency of the petal length is around 50 which is between 1 and 2
- The highest frequency of the petal width is between 40 and 50 which is between 0.0 and 0.5
  
---

5). Distplot = Histogram + a smooth KDE curve (Kernel Density Estimate) on top. It can be used for the univariant visualizations.

<img width="450" height="550" alt="image" src="https://github.com/user-attachments/assets/02688415-ca08-4dcb-bfd7-37e8ce323cd7" />

<img width="450" height="550" alt="image" src="https://github.com/user-attachments/assets/8c8cd9c5-4182-4cdb-b346-fec2d26913e2" />

#### Interpretation
- In the cases of Petal Length and Petal Width, there is a very little amount of overlapping.
- In the cases of Petal Length and Petal Width, there is a very little amount of overlapping.


 So we can use Petal Length and Petal Width as the classification feature.

----
### Handling Correlation

<img width="550" height="450" alt="image" src="https://github.com/user-attachments/assets/b4656559-b89f-479c-a882-5013ce5c5c00" />

#### Interpratation
- Petal width and petal length have high correlations.
- Petal length and sepal width have good correlations.
- Petal width and sepal length have good correlations.

----
### Identifying Outliers.

<img width="500" height="400" alt="image" src="https://github.com/user-attachments/assets/6e2b614d-7f71-4cd6-8a49-7eb6dfc10bd1" />

- There're outliers in sepal width column data.
<img width="500" height="400" alt="image" src="https://github.com/user-attachments/assets/3d86339c-c3e6-440c-be1b-e43c37754437" />

- After removing outliers using IQR.
<img width="500" height="400" alt="image" src="https://github.com/user-attachments/assets/2d208e34-79b6-4c67-9de6-4d42707a7882" />

## Training and Testing for several models.

<img width="700" height="400" alt="image" src="https://github.com/user-attachments/assets/032244aa-546e-47ef-b62e-5e409cc697d9" />

Above accuracy is for Logistic regression model. Now let's try few more models.

<img width="600" height="250" alt="image" src="https://github.com/user-attachments/assets/f1359319-88a4-480e-b3aa-2635920ed0e6" />

High-level models work better with dataset.

<img width="600" height="250" alt="image" src="https://github.com/user-attachments/assets/c5265a58-8a79-485f-8d84-b6fc22f3ff38" />

### Using the model for predictions.
<img width="700" height="200" alt="image" src="https://github.com/user-attachments/assets/59d8b7ae-e32d-4d3b-9894-6e25fcdcbde2" />


## Further Improvements.
- Perform the model evaluation using precision, recall, and F1-score as well.
- Compare the accuracy of each training models and find the best one for the dataset.

