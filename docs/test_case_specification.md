## **Test Case Specification for Team 5**

##### _January 8, 2020_

#### **Table of Contents**

---

#### 1 INTRODUCTION

#### 2 TEST CASES: Windows Application

#### 3 TEST CASES: iOS Application

#### 4 TEST CASES: TCP Server

---

#### 1) Introduction

This document provides the test cases to be carried out for the Project: Chat
Protocol application. Each item to be tested is represented by an individual
test case. Each case details the input and expected outputs.


#### 2) Test Cases: Windows Application

Test ID | 1.1
---|---
Title | Correct Login
Feature | Login to the chat server with the application
Objective | Confirm that proper username and password input leads to access to the chat server
Setup | Windows device has the Project: Chat Protocol code and a proper python interpreter
Test Data | Login information <br> Username = LoginTest <br> Password = Pr0ject
Test Actions | 1. Start the Chat Application <br> 2. Enter the valid Login information in the login page <br> 3. Press the login button
Expected Results | System displays the main page with Chat, View Users and Logout options.

Test ID | 1.2
---|---
Title | Incorrect Password
Feature  | Login to the chat server with the application
Objective | Confirm that valid username but invalid password denies access to the website and prompts a retry
Setup | Windows device has the Project: Chat Protocol code and a proper python interpreter
Test Data | Correct username, incorrect password <br> Username = LoginTest <br> Password = Pro!ect
Test Action | 1. Start the Chat Application <br> 2. Enter the invalid Login information in the login page <br> 3. Press the login button
Expected Results | System displays error alert and prompts the user to either retry or close the app, then displays the empty forms once more

Test ID | 1.3
---|---
Title | Incorrect User Data
Feature  | Login to the chat server with the application
Objective | Confirm that invalid username and password denies access to the website and prompts a retry
Setup | Windows device has the Project: Chat Protocol code and a proper python interpreter
Test Data | Incorrect username, incorrect password <br> Username = L0ginTest <br> Password = Pro!ect
Test Action | 1. Start the Chat Application <br> 2. Enter the invalid Login information in the login page <br> 3. Press the login button
Expected Results | System displays error alert and prompts the user to either retry or close the app, then displays the empty forms once more

Test ID | 1.4
---|---
Title | Select Option Chat
Feature | Select a user and start a chat with them
Objective | Confirm that the app is able to recognize the target username and send a text message
Setup | Two Windows devices connected to the same network, the app code and an interpreter
Test Data |
Test Action | 1. Start the Chat Application on both devices <br> 2. Have both devices logged into different accounts <br> 3. Have one of the users type the other's username in the provided form and press "chat", then type a test message and send it <br> 3. have the other user check for messages to retrieve the test message
Expected Results | User 1's message arrives to User 2, who's notified of this, can see the message and is prompted to reply if he so chooses.
