# Table of Contents

1 **Introduction**

	1.1 Overview

	1.2 Goals and Objectives

	1.3 Scope

	1.4 Definitions

2 **General Design Constraints**

	2.1 Project: Chat Protocol Application Environment  

	2.2 User Characteristics  

	2.3 Mandated Constraints

3 **Nonfunctional Requirements**

	3.1 Operational Requirements

	3.2 Performance Requirements

	3.3 Security Requirements

	3.4 Documentation and Training

	3.5 External Interface

		3.5.1 User Interface

		3.5.2 Software Interface

4 **Functional Requirements**

	4.1 Required Features

		4.1.1 Use Case: 1

		4.1.2 Use Case: 2

	4.2 Optional Features

		4.2.1 Use Case: 3

		4.2.2 Use Case: 4  


## 1 - Introduction

#### 1.1 - Overview
The _Project: Chat Protocol_ will be a pc application available for Windows and Linux alike.
The application will provide the user with the ability to create an account and connect to a chat server to communicate with other users using simple text messages. They will also be able to check which users are online and to choose whether to write to a single user, multiple users or all active users at that specific moment   

This document provides information on the requirements for the _Project: Chat Protocol_ application.
Project goals, scope and definitions are given in the introduction. Design constraints and application environment are described in the following section.  Non-functional requirements are outlined for later verification.  Functional requirements are given to show the system features and expected user interaction.
Project constraints will be included in separate documentation.  The Software Project Management Plan will give specifics on project budget and schedule.  A separate Test Plan document will address test specifications and procedures.

#### 1.2 - Goals and Objectives
This project's main objective is to test the development team's ability to define internet protocols. The app's main and only purpose is to allow people in the same network to communicate with each other.

The _Project: Chat Protocol_ application is expected to:
1. Provide a visual interface on pc to be able to see all online users and manage chats with them
2. Be functional but simple to use and understand
3. Provide users with the tools to chat with anyone who uses the same application and server

#### 1.3 - Scope
The _Project: Chat Protocol_ application will provide users with the ability to create an account and connect to a server in which they will be able to chat among other users from a pc connected to the same network of said users. During the registration process, users will be able to input their profile info and set a password to ensure protection. Moreover, after logging into their account they will be able to view a list of all users they can interact with. Currently none of the functions of the app will be accessible without creating and logging into a valid account.

#### 1.4 - Definitions
_**Project: Chat Protocol**_: The application that is being described; the software system specified in this document; the final product.

_**Project**_: The activities that will result in the development of the application

_**User**_: The person who will interact with the Application

_**Use case**_: Describes a goal-oriented interaction between the system and an actor. A use case may define several variants called scenarios that result in different paths through the use case and usually different outcomes.

_**Scenario**_: One path through a user case

_**Actor**_: User or other software system that receives value from a user case.
