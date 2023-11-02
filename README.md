# To-Do List

## Table of Contents

### [1. Introduction](#Introduction)
   - #### [Summary](#brief-summary)
   - #### [Product Value](#product-value)
   - #### [Intended Audience](#intended-audience)
  
### [2. Description](#description)
  - #### [User Prerequisites](#user-prerequisites)
  - #### [Visual Structure](#visual-structure)
  - #### [Menu Options](#menu-options)
  - #### [Architecture](#architecture)






## Introduction

### Brief Summary
This document is made for the purposes of documenting the requirements of making the accompanying project: a web-based application that allows one to make and save their To-Do Lists online. The document covers various aspects of the mentioned web-app, such as the functionality, use-cases, test-cases, software used to construct the application, etc.

### Product Value

The purpose is to make a to-do list web-application that helps its audience maintain neat and minimal-yet-aesthetic to-do lists that consist of their itineraries and schedules for any span of time- be it a day, week, college semester or even a year. This app is designed such that its interactive elements and the overall design is built in an intuitive and easy manner so that anyone from any field can use this app if they have a device with an access to the internet. The app, by extension, also aims to abstract its underlying logic from its usability so that even the newest of users do not find it intimidating to start using it.


### Intended Audience

The app is meant to be user friendly, so anyone with the aim of organising their schedules/itinerary in a more efficient manner can use this to-do list app. Be it professors, students, professionals, travelers, etc., this app is bound to help anyone from any fields of life. Moreover, this web-app is meant to be versatile to suit multiple purposes, making the target audience more generic in nature.

---

## Description

### User Prerequisites

- A device connected to the internet
- A stable internet access
- An account (existing, or sign up)
- An email account (for sign-up purposes)

### Visual Structure

The To-Do List application will consist of the following primary components:-

- A sign-up/sign-in page for old/new users respectively. 
  (Loads the home screen post the sign in/sign up operation.)

- A sidebar for navigation. Menu options:-

  - Home
  - Profile
  - Folders
  - Priority To-Do's
  - Upcoming Reminders
  - Calendar
  - Shared Lists [Not Implemented]
  - Help

- A display pane to display the menu and to-do list contents.

### Menu Options

#### 1. Home </br>
The main page that opens up after signing in/up. Used to make new to-do lists, view all to-do's, sort and filter memos/folders on the basis of date, priority etc. 

#### 2. Profile

The user's profile information. Consists of generic options such as logout, delete account, changing accounts, website theme options, and so on.

#### 3. Folders

Gives the user a means to create different folders for different to-do lists/memos. The user can keep track of their folders in this option. Allows means to add/delete/modify memos in a folder, to make new folders and add to-do lists to them as well.

#### 4. Priority To-Do's [Work in Progress]

This is a feature of the To-Do app where users can create a priority label for their notes based on their own logic. These priority labels will show up in decreasing order of urgency/deadline dates (depending on the user) in this menu. This allows a cleaner top-level view of the more essential/urgent notes if the user is using the app for multiple purposes of varying importance levels.

#### 5. Help

Consists of FAQs (Frequently Asked Questions) and a way to contact the developer(s) and/or maintainers in charge of handling this app.

### Architecture

This web-application will be built on Django templates for the frontend framework.
Django is the backend framework used in this project.

The database running in the backend is a SQLite (relational) database.


Top-Level Database Architecture: [Database Architecture](https://docs.google.com/spreadsheets/d/1oU1autaJD3snmLhX60DujXwDM8RktoUeoWphQgmxX3Y/edit?usp=sharing)
