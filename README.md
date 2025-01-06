# work-ds-curriculum-020-Apartment-Sales-in-Buenos-Aires

## Purpose
The real estate market is a crucial aspect of any economy and understanding the factors that impact property prices can be of immense value to both buyers and sellers. The purpose of this project is to create a predictive model that estimates the prices of apartments based on various features such as surface covered, location, and borough. This project is focused on predictive data science and aims to provide insights into the real estate market.

## Data
The data used in this project was obtained from open sources and contains information on properties. The data was pre-processed to remove any missing or irrelevant information. The main columns of interest after the cleaning process include:

* Price
* Surface covered
* Latitude and longitude
* Boroughs
The cleaning process was extensively documented in the project notebooks to ensure transparency and reproducibility.

## Methods
Two notebooks were used for this project, the first one was used for the initial walkthrough and wrangling, while the second was for modeling and deployment.
The following methods were used in this project:

* Ridge Regression: Ridge Regression is a type of linear regression that adds a penalty term to the loss function to prevent overfitting. Overfitting occurs when a model learns the noise in the data instead of the underlying patterns, leading to poor generalization performance on new data. Ridge Regression adds a penalty term that discourages large coefficients and helps to prevent overfitting.

* OneHotEncoder: This is a feature preprocessing technique that converts categorical variables into a binary representation suitable for use in a machine learning model. Categorical variables are variables that can take on one of a limited number of values. In this project, the borough column was converted into a binary representation using OneHotEncoder.

* SimpleImputer: This is a feature preprocessing technique that replaces missing values with a specified statistic (e.g. mean, median, etc.). Missing values can be problematic for machine learning models as they reduce the amount of data available for learning. SimpleImputer replaces missing values with either the mean or median value of the column, depending on the specified strategy.


## Results
The results of this project were communicated as follows:

* A visualization of the most important boroughs based on the model's predictions. This visualization provides insights into which boroughs have the highest and lowest predicted apartment prices.

* A function (make_prediction) that takes 4 arguments (surface covered, latitude, longitude, and borough) and returns the model's prediction for an apartment price. This function can be used to make predictions for new apartments based on their features.

* An interactive widget made with Jupyter widgets, which can be adjusted to see how predicted apartment prices change based on different input values. This widget provides an interactive way to explore the model's predictions and understand the impact of various features on apartment prices.

## Usage
It is important to note that this project is for educational purposes only and the results should not be used for real-world decision making without proper verification and validation.

## Conclusion
In conclusion, this project aimed to create a predictive model for apartment prices using data science techniques. The results of the project provide insights into the real estate market and can be used to make informed decisions about property investments. This project serves as an example of how data science can be applied to real-world.

## Notebook

![Capture01](https://github.com/user-attachments/assets/ecea66ba-aac9-40e2-bd79-da69b3403b71)

![Capture02](https://github.com/user-attachments/assets/0d547552-0755-4039-8dc9-5306f7cc49c9)

![Capture03](https://github.com/user-attachments/assets/17ea19f1-8726-4f0d-b5cd-e99400f9fa2a)

![Capture04](https://github.com/user-attachments/assets/e7b17e8f-f56f-48cd-b31d-7ea7701ab2b0)

![Capture05](https://github.com/user-attachments/assets/e3e810ce-eacc-485a-a797-d966ba2966e9)

![Capture06](https://github.com/user-attachments/assets/9a0a90a8-180b-4dcd-ad16-94294a6f360a)

![Capture07](https://github.com/user-attachments/assets/9c83f83c-6b82-4b5d-b375-64d13ef385cf)

![Capture08](https://github.com/user-attachments/assets/a79cd09e-f531-458f-9925-708c9ee9e02a)

![Capture09](https://github.com/user-attachments/assets/2cfeca0d-bd1e-4439-9a94-418fb2503c85)

![Capture10](https://github.com/user-attachments/assets/280ed2be-189c-4b6b-a8d7-60f0abcd180e)

![Capture11](https://github.com/user-attachments/assets/9beaf369-5edb-4b03-8917-6349ad9e4308)

![Capture12](https://github.com/user-attachments/assets/d2cd2ead-b2cc-4abf-a9ed-ae7a3c8a8e1f)

![Capture13](https://github.com/user-attachments/assets/c9360abe-7f64-473f-abeb-805087914790)

![Capture14](https://github.com/user-attachments/assets/0d0a8447-95ee-4a04-910c-ff20f2961dc7)

![Capture15](https://github.com/user-attachments/assets/df518e58-c8e6-4ca4-a9d8-0bf02437be6b)

![Capture16](https://github.com/user-attachments/assets/0efb79b5-06f9-4910-8213-03540dfd81ef)

![Capture17](https://github.com/user-attachments/assets/603814fa-eba4-4012-b8e4-7b4c7b0122b4)

![Capture18](https://github.com/user-attachments/assets/2f0e41b0-b23f-4f99-8b61-72eb85ecdf18)

![Capture19](https://github.com/user-attachments/assets/259dbdcc-67b9-49da-9489-cb262150dccb)










