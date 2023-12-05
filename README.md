# Qoala-OCR-app


**Qoala-Assignment Details **

Create an OCR (Optical Character Recognition) App that can recognize thai id cards and get the required information. Save this information for retrival later.

Objective
Develop an application that utilizes Optical Character Recognition (OCR) to analyze thai id cards and extract relevant data. This app should integrate with Google Vision API for OCR processing and then parse the response to interpret the OCR results, returning the final data in JSON format.
Along with this we would like you to choose a database of your choice and save the results in the db. We would need a CRUD api to create the ocr data, if needed we can modify some data, filter them or delete certain id cards(soft delete).

Sample Thai ID Card Data:
The id cards you'll be analyzing can contain various data fields such as:

Name
Last Name
Identification Number
Date of issue
Date of expiry
Dagete of birth

sample image which is used

![Screenshot 2023-12-05 140548](https://github.com/spkumawat/Qoala-OCR-app/assets/89294297/b19fe393-f15f-4c41-8040-65b197af1938)


CR Processing:
Integrate the application with Google Vision API to perform OCR on id card images. https://cloud.google.com/vision/docs/ocr#optical_character_recognition_ocr

Ensure that the OCR can accurately read text from different thai id cards.

Database and REST API Endpoints

Create a New OCR Record
Update Existing OCR Data'
Retrieve and Display OCR Data
Delete OCR Records

JSON Output:
The final output should be a well-structured JSON object containing all the extracted data.
Ensure accuracy and readability of the JSON output.


Developed with the software and tools below 
javascript 
reactjs
nodejs
expressjs
mongoDB
multer


TABLE OF CONTENT :
OVERVIEW
FEATURE 
FOLDER STRUCTURE
GETTING STARTED
ACKNOWLEDGEMENT

-> OVERVIEW
This project aims to develop an application utilizing Optical Character Recognition (OCR) to extract information from Thai ID cards. The app integrates with the Google Vision API for OCR processing, extracting key data fields like name, last name, identification number, date of birth, date of issue, and date of expiry.




