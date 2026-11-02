# Splatnet-3-Gear-Notifier

### Project Goal

The goal of this project is to create a Java application that automatically checks the Splatnet 3 shop for specific gear that users want. When the gear becomes available, the program sends an email notification. This saves users time by eliminating the need to constantly check the shop manually.
<br>
<br>


### MVP Scope

The Minimum Viable Product (MVP) will include the following features:

A Java script that retrieves shop inventory from the Splatnet 3 API.
A way for users to choose which gear they want to be notified about.
A JSON file to save selected gear preferences.
A system that compares available shop gear with the user's saved preferences.
An email notification system that alerts users when wanted gear appears.
Automatic shop checking at regular intervals.
Future Plans
<br>

#### The following features are planned for future versions of the project:

Add filters to sort gear by brand, ability, or gear type.
Allow users to create accounts and save their gear preferences.
Add a notification history so users can see previously found gear.
Tech Stack
<br>
<br>


### Programming Language 

**Java** – Used to build the application and handle the shop-checking process.
Libraries and Packages

**Java HTTP Client (java.net.http)** – Sends requests to retrieve shop information from the API.
Gson – Reads and organizes JSON data received from the API.
JavaMail – Sends email notifications when wanted gear is found.
Data Storage

**JSON files** – Store the user's selected gear preferences and other necessary information.
External Data Source

**Splatnet 3 API** – Provides shop inventory information.
Java HTTP requests will be used to retrieve the available gear data.
Notification System

**JavaMail** – Sends an email when the program finds gear that matches the user's saved preferences.
Project Status
<br>
<br>
<br>
<br>
This project is currently in the planning and development stage. Features will be added and tested as development progresses.
