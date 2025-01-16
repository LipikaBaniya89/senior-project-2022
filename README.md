# iLearn 

## What is the app 'iLearn' about? 

Project for Siam Commodities Group to improve image recognition through human-cognition-based deep learning. 

Development: Jan 2022 - April 2022

Language: HTML/CSS/JavaScript

Platforms: Visual Studio Code (Development) & Figma (Protoype)

Many companies want to gather data from their customers or users but are unable to do so because they might be small companies. Big companies like Facebook and Google have enormous amounts of data about all their users but face many privacy issues and concerns. Small companies don’t want enormous amounts of data but just enough to help with their research. That is the problem we’re going to solve. As a solution, we will build a platform for companies to host surveys on a website and gather user’s opinions and data. A web scraper will help gather images to display to the user while a search expansion will help analyze the user’s responses and scrape better images to display while also increasing the accuracy. For our senior project, our system will scrape images from the internet, take survey answers from users as well as perform search expansion for higher accuracy and performance.

# User Interface Design
The UI is designed to support both dark and light theme modes. Its a practical design that clearly showcases all the features of the application. 

## 1. Home Screen
The first screen user will see is the Home Screen as shown in Figure 1. This screen is just to let the user know about the application and what it does.
![LightMode](https://github.com/user-attachments/assets/2b4a2a61-cfcc-4feb-b413-6b3aedc4631a)
![DarkMode](https://github.com/user-attachments/assets/2ea9808a-37d4-4aaf-8299-de867e34451c)

   Figure 1: Home Screen

## 2. Survey Categories Screen

This is the 2nd screen of our application Where many different categories of surveys will be displayed for users to choose from.
![image](https://github.com/user-attachments/assets/a9188cf6-6503-4fa3-959c-56388efa720c)
   
   Figure 2 : Survey Category Screen

## 3.  Survey Question Screen
Once the user chooses a category from the previous screen, they can answer some surveys. If the user has signed up, they will be able to see the survey question and the images as shown in Figure 3. 6 images will be displayed randomly from the database and users can select 0-6 images as they wish. Once they click the Submit button, their response will be sent to the API and another 6 images will be displayed for that category. This process will continue until the user clicks the Exit Survey button to end their survey. However, if the user did not sign up for the application, an alert message will be prompted asking the user to sign up as shown in Figure 4.


![image](https://github.com/user-attachments/assets/b2f692d5-d1c8-41c3-845b-1bdb9b52f7dd)


 Figure 3.1 : Survey Question Screen


![image](https://github.com/user-attachments/assets/c7d5798c-b6df-4c9f-adb1-090535d70be1)
                            
 Figure 3.2 : Alert Message

## 4. Profile Screen
The last screen of the application is the user profile screen which is for the user to sign out from the application.

![image](https://github.com/user-attachments/assets/07b8fa43-e280-48c7-8579-1bc1ba7513ae)

Figure 4 : Profile Screen
