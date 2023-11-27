# Project_4
Our group chose to work with a CSV file from Kaggle that classified patients into two separate categories, Abnormal and Normal, based on 6 different anatomical attributes. These attributes and their normal measurements are related to normal pelvic function and thus were classified as Normal. When attributes were outside of normative ranges due to disc herniation or Spondylolisthesis, patients were classified as abnormal. 
Our group extracted the data and then discussed what the data meant and how it could be transformed and loaded to reach useful and meaningful conclusions. We then loaded the data into dataframes which made the values more workable. Due to the fact that all of the values were numeric for this CSV file the transformation of the data was fairly straight forward. 
After loading the transformed data, an Orthopedic Prediction Logistic Regression Model was created that produced the following results in regards to accuracy. 
![Screenshot 2023-11-26 221216](https://github.com/kwlayton1/Project_4/assets/132946452/6c19886a-556f-45ae-8931-ebbde9d9be9f)

# Attributes of Consideration 
The 6 attributes that were taken into consideration for this data set included: pelvic incidence, pelvic tilt, lumbar lordosis angle, sacral slope, pelvic radius, and grade of spondylolisthesis. 

# Pelvic Incidence
Is a numerical value that represents the measure of an angle of two planes of the pelvis. In simple terms the pelvic incidence provides a numerical value to represent the relationship between an individual's pelvis and their spine. Each person's measure of lordosis is unique because no two people have exactly the same spine and pelvis. For this reason the norm is from +/- 10 degrees from the measures of each individual's anatomical landmarks. This measure increases as people develop and walk upright more often. Pelvic incidence is related to a condition called lordosis, which is a inward curvature of the spine that exceeds normative values. 
![image](https://github.com/kwlayton1/Project_4/assets/132946452/82a7194d-ea29-4567-a1e1-1e536fe6baaf)

# Pelvic Tilt 
Pelvic tilt is the result that happens when your pelvic muscles lean excessively to one side. Typically for both men and women they experience anterior pelvic tilt. This condition is most often caused by shortening of the hip flexors, lengthening of the hip extensors, spending too much time sitting, sedentary lifestyle, poor posture, and weak core muscles. For those of us who work long hours sitting at a desk typing or working on the computer this is a condition to work to avoid through strengthening of hip extensors, walking, posture correction, and core strengthening. 

# Lumbar Lordosis Angle 
Simply stated this is the inward curve that is located in the lower portion of your back. This image displays different categories of lordosis depending on the angle size. 
![image](https://github.com/kwlayton1/Project_4/assets/132946452/2c9aed25-8a87-474e-aac8-82020dbef444)

# Sacral Slope
From a mathematical standpoint, the sacral slope is the pelvic incidence - pelvic tilt. The following image displays an example of where a sacral slope is located anatomically and which vertebrae are included in it's measurement. 
![image](https://github.com/kwlayton1/Project_4/assets/132946452/e0f16d18-6102-4fe7-abe8-6bddf768511a)

# Pelvic Radius 
Based on the resources available, this measurement is a combination of the conjugate, transverse, oblique, and diagonal conjugate measurements obtained from measuring the different areas within the pelvic bones. 

With the models and visuals that our group has created we feel that our model could accurately predict whether a patient could be classified as having Normal or Abnormal lumbar anatomy which could assist in the diagnosis and treatment of patients with a variety of conditions. 
# Grades of spondylolisthesis
Spondylolisthesis is a condition where one vertebrae comes into contact with the vertebrae below it. Spondylolisthesis is categorized into 5 different grades. The following image depicts the different grades of spondylolisthesis and the their corresponding percentages. 
![image](https://github.com/kwlayton1/Project_4/assets/132946452/0de820d8-816e-4f84-9a3f-6f6d9e1d524a)

