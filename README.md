# RetinoAssist
RetinoAssist is a Diabetic Retinopathy detection system for doctors to manage and diagnose patients with diabetic retinopathy that causes blindness. This system aims to provide features such as managing patients and their details, performing examination on eye scans and generating results, viewing past results etc.


![image](https://user-images.githubusercontent.com/61086579/150742940-3fd24358-bff6-4dfb-8dd6-8822e9407708.png)

# Features of RetinoAssist
1. Add Patient - This feature allows doctor to add a new patient into the system. 
2. View Patient - Allows the doctor to view the details of a patient and his past history whenever he wants.
3. Perform Examination - This allows doctor to perform diabetic retinopathy examination on patient and generate analayis and report.
4. View Reports - Allows the doctor to view past reports of the paitents by using their patient ID's.

# Setup
1. Download the Classifier file from https://www.kaggle.com/souravs17031999/blindness-detection-pretrained-weights-pytorch and put it inside Input folder in Model directory.
2. Setup MySql Databse following instructions below.
3. insert a user into mysql database using commandline and remember username and password
4. Launch the login file in the project from netbeans and login into the system using the credentials. 

# How to Create Database 
1. Create databse named retinet
2. Create table named patient_details with following description ![image](https://user-images.githubusercontent.com/61086579/150745218-496ff00e-f834-4a92-b17c-c91bcd9c2cd5.png)
3. Create table named user_info with following decription ![image](https://user-images.githubusercontent.com/61086579/150745395-fe4f3948-ff13-475e-91a3-a256827e593f.png)
