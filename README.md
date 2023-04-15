# Churn_prediction

__Churn prediction__ has got some considerations ...

**About this project**

This paper says, this churn prediction is based on behavior type of customers. So, in the following we will discuss that how I encompass this project.

**0- Download the dataset**

**1- Cleaning dataset ** (data preparation) 

explanation : first convert Timestamp feature into standard time and then based on this feature categorize behavior time in 17 variables which mentioned in the paper.
 customers’ shopping behaviors happened in different time periods, this work divided the time when shopping behaviors occurred.
Our definitions were 00:00 to 06:00 is Daybreak; 06:00 to 12:00 is AM; 12:00 to 18:00 is PM; and 18:00 to 00:00 is Night. Then, the shopping behavior of each customer in these four
time periods was counted.The behavioral data in the dataset are PV number, Buy number, Cart number, and Fav number. The behavioral data were further subdivided, and the data types were finally sorted, with 17 types of variables. Specifically, the items were Categories, Daybreak PV,Daybreak Buy, Daybreak Cart, Daybreak Fav, AM PV, AM Buy, AM Cart, AM Fav, PM PV,PM Buy, PM Cart, PM Fav, Night PV, Night Buy, Night Cart, and Night Fav.



**2- K-means segmentation** 

**3- feature selection using random forest**

**4- unbalaned data processing using SMOTE**

**5- churn prediction with SVM and LR**
