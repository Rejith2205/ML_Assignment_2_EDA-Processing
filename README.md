# ML_Assignment_2_EDA-Processing
***Importing all the necessary libraries***
![image](https://github.com/user-attachments/assets/91ea0813-b5b5-4549-95a2-222b626ef3bc)
***Load the dataset for EDA processing***
![image](https://github.com/user-attachments/assets/bb8011c8-12d0-4759-a8e9-ab456f728f87)
***To view the first 10 rows***
![image](https://github.com/user-attachments/assets/ac6fb994-ccd9-4db4-b149-667955a125a6)
![image](https://github.com/user-attachments/assets/1172b565-2731-4784-964e-87219ab75f12)
![image](https://github.com/user-attachments/assets/79788ab5-9b8e-4437-b65c-7430e92e32b6)
# Data Exploration:  
***Explore the data, list down the unique values in each feature and find its length.***   
***Perform the statistical analysis and renaming of the columns***

***To check dimensions of the DataFrame (number of rows and columns)***
![image](https://github.com/user-attachments/assets/ef139948-0f04-4af5-9ecd-2d775910df3f)
***Check data types***
![image](https://github.com/user-attachments/assets/8f2d609f-6238-4edd-8abb-f3379984e620)
![image](https://github.com/user-attachments/assets/b6b995bd-4518-4d89-a9f7-633b343325f9)
***Display the column headings (column names) of the DataFrame***
![image](https://github.com/user-attachments/assets/a0081f77-7d03-451a-9bb6-38e320705cb4)
***Display summary statistics***
![image](https://github.com/user-attachments/assets/594f4287-badb-471c-a0fa-b3a203c37cb7)
***print unique values of the dataset***
![image](https://github.com/user-attachments/assets/a4c6c205-e968-4bea-8357-4b3ae9b2a402)
![image](https://github.com/user-attachments/assets/7de88a25-b894-46ce-a80e-280b8e5fc999)
***change the  column name to upper case and  rename the 'PLACE" to "CITY"***
![image](https://github.com/user-attachments/assets/ef8a630a-ff82-418e-ba46-47b48b0d4b38)
# Data Cleaning:
***Find the missing and inappropriate values, treat them appropriately.***  
***Remove all duplicate rows.***  
***Find the outliers.***   
***Replace the value 0 in age as NaN.***   
***Treat the null values in all columns using any measures (removing/ replace the values with mean/median/mode)***  

***Check the Missing Values in the dataset***
![image](https://github.com/user-attachments/assets/6cefc9ab-92ff-4579-a6f3-1e98d97d0fee)
***check  '0' in each column***
![image](https://github.com/user-attachments/assets/64e028ea-4e18-4355-9d96-9dcd0b948a62)
***Keep a copy of the dataframe before doing any changes***
![image](https://github.com/user-attachments/assets/cad81aba-83cf-418f-a3e6-b07ddae22891)
***Check the duplicate records***
![image](https://github.com/user-attachments/assets/3d16ae78-0074-469a-a8db-f28150fdd920)
# Data Cleaning: 
***Check the unique records in the dataset*** & ***Remove duplicates***
![image](https://github.com/user-attachments/assets/2547f6b8-0dd4-4480-b4e7-f9f2c764e8a8)
***Number of records after deleting the duplicate & Dimensions of the DataFrame***
![image](https://github.com/user-attachments/assets/922abae2-4957-4e43-9e1f-f82b295dcbbe)
![image](https://github.com/user-attachments/assets/3634c95f-4c87-495b-ad2f-bc57fb982607)
## ***Replacing the missing values in the Numerical columns with the Median***
***Check the number of  "Nan" & "0"  in column "AGE" , update all the '0' values to "Nan" before updating all the "Nan" values with the Median value of "AGE"***
![image](https://github.com/user-attachments/assets/70b5d8a1-a6b4-4790-a456-2bd44268c174)
![image](https://github.com/user-attachments/assets/e1390504-5bd1-4177-8909-74d01c04c6bd)
![image](https://github.com/user-attachments/assets/b8ea1bf7-89a2-4624-a1e6-b0545c6064a5)
![image](https://github.com/user-attachments/assets/9307fae5-4160-4c4a-88ee-5a7138c576b1)
![image](https://github.com/user-attachments/assets/c9c17fa0-06b3-48e2-aac3-39abf056fdd3)
![image](https://github.com/user-attachments/assets/72547fa6-82ea-4ec9-ae8b-663c6a1414e4)
![image](https://github.com/user-attachments/assets/184ee5e2-5b1a-499d-a141-1aecb32218fc)
![image](https://github.com/user-attachments/assets/846a9489-0025-477e-bd28-9877f724f2f9)
![image](https://github.com/user-attachments/assets/397a5006-4f2f-467e-b885-315774508838)
![image](https://github.com/user-attachments/assets/4bd78a76-f5a0-44a1-8498-5d5670016db0)
## ***Replacing the missing values in the Categorical columns with the Mode***
![image](https://github.com/user-attachments/assets/5dfb5b73-1438-47db-871f-e201ab462119)
![image](https://github.com/user-attachments/assets/50e78a5b-b266-45a4-a908-fbad49650c7f)
![image](https://github.com/user-attachments/assets/256d82c0-aa20-4569-8759-6ae82854bfd1)
![image](https://github.com/user-attachments/assets/f9ea6495-ac49-4597-89d0-8ee10d80e8fa)
***Replace the value in the categorical column 'GENDER' with 0 =Male and 1= Female***
![image](https://github.com/user-attachments/assets/bac51ce0-422a-42a7-ab76-04e4241f7423)
![image](https://github.com/user-attachments/assets/66d4afd2-12e7-4e71-abf8-f58f18ab79ea)
![image](https://github.com/user-attachments/assets/0d71341b-7af3-46b2-a8db-779045dc294a)
***Find Outliers*** -------***BOX Plot Method***
![image](https://github.com/user-attachments/assets/99ab184d-01ca-40ff-ad80-e6e53c45a2fb)
![image](https://github.com/user-attachments/assets/01468d06-5e55-4183-906b-f6c68550bf78)
***IQR Method***
![image](https://github.com/user-attachments/assets/bf9d823e-36c7-4f74-b2d9-736e6a7c798a)
![image](https://github.com/user-attachments/assets/c4044fdf-3491-4097-9b4e-004839a206d3)
***From the above two method it is clear that there is no outliers in AGE and SALARY***

# Data Analysis:

***Filter the data with age >40 and salary<5000.Plot the chart with age and salary.Count the number of people from each place and represent it visually.***
![image](https://github.com/user-attachments/assets/f58bf214-3835-437e-9c24-4db711c07261)
***Plot the chart with age and salary***
![image](https://github.com/user-attachments/assets/fb1e5e36-f472-439c-8503-108d937450bc)
![image](https://github.com/user-attachments/assets/d4050bf4-3dae-454f-83ee-05c5c09b1702)
***Count the number of people from each place and represent it visually***
![image](https://github.com/user-attachments/assets/e11cca05-5028-4b3b-a061-acc0c76807bf)
![image](https://github.com/user-attachments/assets/18624e7e-59c6-4697-8297-6c6de743e1cb)
![image](https://github.com/user-attachments/assets/daa1c9e1-fee5-44f4-9791-982c325ee059)

# Data Encoding: 
***Convert categorical variables into numerical representations using techniques such as one-hot encoding, label encoding, making them suitable for analysis by machine learning algorithms.***

![image](https://github.com/user-attachments/assets/a150edd6-fe4c-4eb2-9a6c-959abc441e4c)
![image](https://github.com/user-attachments/assets/e26ab6f3-77be-4da1-84d7-90ba3fbdb8db)
![image](https://github.com/user-attachments/assets/cf34bbdb-bf71-4fd2-a4d9-fe9d45c58cbb)
![image](https://github.com/user-attachments/assets/77e20a30-5b50-4136-8783-ef3123e0e45f)
# Feature Scaling: 
***After the process of encoding, perform the scaling of the features using standardscaler and minmaxscaler***

![image](https://github.com/user-attachments/assets/42c12d9e-f41a-4db9-9a0e-e83d3bb7efb0)
![image](https://github.com/user-attachments/assets/b77af660-3cf1-4d73-a81f-2f39bf889808)
![image](https://github.com/user-attachments/assets/2240da21-9f74-4213-a607-f3dbd9507fde)

