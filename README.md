App Design Project - README 
===

# UCSB Study Rooms
### Team Members: Vanessa Salgado, Luis Miguel, Dylan Cocoletzi 

## Table of Contents
1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)
2. [Schema](#Schema)
3. [Video Walkthrough](#Gif)

## Overview
### Description
This app is intended to provide alternative UCSB study spaces. For each study space a user can access different amenties of each study space. 

### App Evaluation
[Evaluation of your app across the following attributes]
- **Category: Social Networking**
- **Mobile: This app will be primarily for mobile users similiar to a yelp app. Most attributes and function will only be for mobile users.**
- **Story: Provides study spaces for users primarily UCSB students. In the future, they will be able to give recommendations and rate the study spaces they been to. **
- **Market: Anyone can use the app but it is dedicated to USCB students for an opportunity to find their study space.**
- **Habit: User can use it as often as they like, but if they have explore all study spaces, the app may not be useful for them anymore.**
- **Scope: First we will use display an image of the study spaces but after we may include different spaces like restrooms or places to eat. In addition, users will have the ability to review and rate different spaces.**

## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**

* Can see icon image
* Can see styled launch screen
* User can see a list of Buildings 
* User can click on a Building that send them to a list of study rooms in that building
* User can scroll down on study rooms list
* User can click on the image of study room and send to a new screen where a bigger image and more description is provided
* User can access details of a study room such as larger image, location, hours, and different amenities

**Optional Nice-to-have Stories**

* User can log in and log out
* User can upload a recommended study space
* User can rate a study space
* User can filter through study spaces


### 2. Screen Archetypes

* Buildings Scrolling Screen(Selection)
   * User can see and scroll through Buildings and their names 
   * User can scroll up and down the screen
* Study Room Scolling Screen(Selection)
   * User can see and scroll through room images and number/name
   * User can see room rating 
   * User can go back to the previous screen with the back button
* Study Room  Screen(Detail)
   * User can see larger image of the study space
   * User can see location(map), hours, ammenities such as noise leve, outlets, supplies, technology availble
   * User can go back to the previous screen with the back button
   * User can rate down on study space 
* Search Building Room Screen(Search)
   * User can search for a specifc building or room 
   * If user searches for building, it allows user to go directly to building's list of rooms 
   * If user searches for rooms, it allows user to go direclty to room's profile
* Submisttion Form Screen
   * User can submit image, name, and amenities of a room
   * User can click on submit button
* Pop Up Library Waitz Website()
   * User can see a pop up screen of UCSB Library Waitz Website


### 3. Navigation

**Tab Navigation** (Tab to Screen)

* Home 
* UCSB Library Waitz
* Search 
* Submit Option 

**Flow Navigation** (Screen to Screen)

* Scroll screen
   * click a study space
* Study space screen
   * Get to see a poster and text

## Wireframes
![Wireframe Sketch](/Images/Basic-Wireframe.jpeg)


### [BONUS] Digital Wireframes & Mockups

### [BONUS] Interactive Prototype
*
## Schema 
[This section will be completed in Unit 9]
### Models

### Video Walkthrough
![Screen Recording 2021-11-19 at 6 50 10 PM](https://user-images.githubusercontent.com/86747062/142712218-18bc3de6-2b5b-4095-9c48-a1e8f406744f.gif)


Building 
| Property  | Type | Description |
| ------------- | ------------- |  ------------- |
| image  | file | imag eof building  |
| name  | string  | name of building  |

Room 
| Property  | Type | Description |
| ------------- | ------------- |  ------------- |
| image  | file | image of room  |
| name  | string  | name of room  |
| rating  | number | number of likes  |
| various amenities | bool | availability(true or fals)|
### Networking

- [Add list of network requests by screen ]

* Home Feed Screen
   * 

* Building Feed Screen
   * (Read/GET) Query of all Buildings
* Room Feed Screen 
   * (Read/GET)  Query of all Rooms of Building 
   * (Read/GET)  Query of Rating

* Room Profile Screen
   * (Read/GET) Query of image, name, location, amenities
   * (Create/POST) Create a new like on a Room

- [Create basic snippets for each Parse network request] ? 
- [OPTIONAL: List endpoints if using existing API such as Yelp] ?do we need this
