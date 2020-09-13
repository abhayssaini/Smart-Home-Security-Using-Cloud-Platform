# Smart-Home-Security-Using-Cloud-Platform

# Introduction

 This home security project is build using cloud platform which will alert you "Someone at the door" no matter where you are. When the camera detects any human face then code will capture the face and simultaneously his/her img file will be uploaded in cloud database and will display in web application showing who is at the door. Apart from this, we will also get SMS alert in mobile phone.


## File contains:- 

### 1.Project Code.py

This python file contain the main code of the project which includes capturing of image (openCV) along with code which connects us to IBM cloud  services (data base, object storage, fast2sms service, etc)


### 2.Node-Red Flow.json

This json code contain Node-Red flow connections used for this project.Basically this is used for (web application). Node-Red is the service given by the IBM Cloud platform. Here this service fetching the data from the cloud. 

## Working:- 

 The project code.py code file run the camera application and capture the face whenever human face is detected in real time. After that, this captured face was stored in cloud platform and displays in web application the person in front of the door along with that we also get sms in the mobile with alert message for the same. 

 
