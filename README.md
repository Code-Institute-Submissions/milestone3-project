<img src="/static/Images/responsive.png" style="margin: 0; width: 80%;"><br>

# Data Centric Development - Code Institute/O Akerele – Milestone3 Project 

***Preamble***<br>
This is my Milestone3 project. It is a **Jargon Dictionary** that is designed to accommodate different<br> professions. The site is designed to allow registered members to contribute populate the dictionary. They can<br> perform the following operation in the dictionary: Create, Read, Update and Delete (CRUD operation).<br> 
Similarly, there is an administrator privilege who has the power to perform the CRUD operation and additionally, the<br>
only one that could introduce a new category before registered members could begin to perform the CRUD operation<br> on the newly created category. Furthermore, it is noteworthy that this site is work-in-progress as there is still<br> a lot of room for improvement. For example, password restriction, populating the Profile Page with User personal<br> profile together with his/her word contributions and adding a search button to the All Word Page.

# Table of Contents
1. [UX](#ux)
    - [Project Goal](#project-goal)
    - [User Goal](#user-goal)
    - [Developer Goal](#developer-goal)
    - [User Stories](#user-stories)
    - [Design Choices](#design-choices)
2. [Wireframes And Mockups](#wireframes-and-mockups)
3. [Existing Features](#existing-features)
    - [Home Page](#home-page)
    - [All Words Page](#all-words-page)
    - [Register Page](#register-page)
    - [Log In Page](#log-in-page)
    - [Profile Page](#profile-page)
    - [New Word Page](#new-word-page)
    - [Manage Category Page](#manage-category-page)
    - [log Out Page](#log-out-page)
4. [Features To Implement](#features-to-implement)
5. [Technologies Used](#technologies-used)
6. [Testing](#testing)
7. [Deployment](#deployment)
8. [Credits](#credits)
    - [Content](#content)
    - [Media](#media)
    - [Acknowledgments](#acknowledgments)

# UX
## Project Goal
The whole idea behind this project is to provide **Jargon Dictionary** where external users will be able to<br> search for words/meanings and particularly for the users to be able to contribute their own words and definitions<br> to the dictionary.<br>
## User Goal
The User goal is to be able to lookup for jargon according to their profession and the meaning of such a word.<br> Also, the user will be able to populate the dictionary by adding new words and meanings.<br>
## Developer Goal
The Developer's goal is mainly to collect good definitions of professional jargon which is to eventually be<br> published into a dictionary in form of a book.<br>
## User Stories
1. As a User, I want to be able to search for jargon and find the meaning of the word.<br>
2. As a User, I want to be able to contribute my quota e.g. if I know a new jargon that is not already in the<br> dictionary, I want to be able to add it.
3. As a User, I want to be able to Edit/Update my contributions to the dictionary.<br>
4. As a User, I want to be able to Delete any of my contributions.<br>
## Design Choices
Bearing in mind the three main purposes of design i.e. communication, aesthetics and functionality, I choose to<br> use grey and light grey with white background to build a beautiful and attractive user interface. Green, red, and<br> light grey colors are used for the buttons.     

# Wireframes And Mockups 
* Sketching
* Drawings
* Features
* Design with Balsamiq

<a href="static/Images/home&all-words.png">Sketch1</a><br>
<a href="static/Images/home&all-words2.png">Wireframe1</a><br>
<a href="static/Images/register&log-in.png">Sketch2</a><br>
<a href="static/Images/register&log-in2.png">Wireframe2</a><br>
<a href="static/Images/profile&new-word.png">Sketch3</a><br>
<a href="static/Images/manage-category&log-out.png">Sketch4</a><br>
<a href="static/Images/desktophome&all-words.png">Sketch5</a><br>
<a href="static/Images/profile&new-word2.png">Wireframe3</a><br>
<a href="static/Images/manage-category&log-out2.png">Wireframe4</a><br>
<a href="static/Images/desktophome&all-words2.png">Wireframe5</a><br>
<a href="static/Images/responsive.png">Mockup for Home Page</a><br>
<a href="static/Images/allwords.png">Mockup for All Words Page</a><br>
<a href="static/Images/register.png">Mockup for Register Page</a><br>
<a href="static/Images/login.png">Mockup for Log In Page</a><br>
<a href="static/Images/addword.png">Mockup for New Word Page</a><br>
<a href="static/Images/manage-category.png">Mockup for Manage Category Page</a><br>

# Existing Features
There are 8 key pages on this website:
* [Home Page](#home-page)
* [All Words Page](#all-words-page)
* [Register Page](#register-page)
* [Log In Page](#log-in-page)
* [Profile Page](#profile-page)
* [New Word Page](#new-word-page)
* [Manage Category Page](#manage-category-page)
* [Log Out Page](#log-out-page)

Every page is designed to show the navbar displaying the name of the dictionary and the interactive pages at the<br> top right. The mobile phone is designed to display the pages in a collapsible manner because of the number of<br> pages to be displayed, the minimum of which is four and maximum of six and some pages have lengthy name e.g.<br> Manage Category. In the middle are the sections that display the message/information for the page.  The navbar<br> was designed with the help of Materialize (materializecss.com).<br>

## Home Page

The Home page is an introductory page for the **Jargon Dictionary.** It contains the navbar and only four pages<br> viz: Home, All Words, Log In and Register. The main page contains an introduction to what the dictionary is<br> all about. It defines Jargon and the types of users which have been broken into Type 1 and Type 2.<br>

## All Words Page

This page like the previous page displays the navbar. The main body is the container for all the words contained<br> in the dictionary and they are arranged in alphabetical order. This is the page where all the new words contributed<br> to the dictionary are recorded. It is designed to show the word with a drop-down arrow by its side, it is an accordion<br>element that expands when clicked on to show:<br>
1. word meaning,<br>
2. the category that the jargon belong to and<br>
3. the name of the creator.<br>

## Register Page

This page allows a new user to register and become a contributing member. A username and a password are required<br> and once that is acceptable, the user can always log in to use the dictionary at any time.

## Log In Page

This is the page that allows a registered user to log into their profile account page from where they can add their<br> own words (Create), search for all words (Read), edit their own words (Update) and delete their own words (Delete).<br> In other words, perform CRUD functionality. A username and a password are required to sign in.

## Profile Page

This is the page that a user is directed to upon signing in. This page is meant to contain the about-me of the user<br> and all the words contributed by him or her to the dictionary. It is worth noting, however, that this page<br> is still a work-in-progress.

## New Word Page

Whenever a user wants to add a word to the dictionary, he or she opens this page and do the following:<br>
1. Choose a category (the profession that the jargon belongs to),<br>
2. Supply the word/jargon,<br>
3. Supply the meaning and<br>
4. Click add word.<br>

That particular word then registers in All Words with the name of the user as the creator and it also registers in<br> the user's Profile Page.

## Manage Category Page

The manage category page is a reserved page for the Administrator of the Dictionary. The administrator has the<br> privilege of being the only one that can populate the Categories and can perform the CRUD functionalities on the<br> whole dictionary. It is noteworthy, that anyone with the administrator password can act in that capacity.

## Log Out Page

This button should be clicked whenever a user has finished using the dictionary. When it is clicked, the user is<br> taken to the sign-in page with a flash message "You have been logged out".

# Features To Implement

As earlier stated, the website is a work-in-progress and can still be improved upon. In the new version, the user<br> will be able to search for word meaning by:<br>
1. Word,<br>
2. Profession and even by<br>
3. Creator.<br>

through the introduction of the Search button at the top center of the All Word Page. The password will be with some<br> restrictions i.e. requiring it to include letters, figures, uppercases and characters and others noted above such<br> as the Profile Page.  

# Technologies Used

The following technologies were used to create the website:
* Gitpod full template - workspace
* HTML5 - used to create the basic code for the pages.
* CSS3 - Used to style the elements of the pages.
* Materializecss 1.0.0 - used to simplify the structure and to make it responsive.
* JavaScript - For the logic of some of the elements.
* jquery 3.4.1 - used to reference Javascript and menu components.
* Flask Framework - Used as the main framework for the website.
* MongoDB - Used to store and retrieve the data created from the website.
* Python version 3.8.7 - Used for routing and support alongside MongoDB and interaction between pages
* Google Chrome browser Developer Tools - Used for testing during development.
* Balsamiq - the tool used to create the wireframe.

# Testing
## Navbar/Header
  
The header has the name of the Dictionary on the left-hand side and the pages on the right-hand side. Every name<br>on the navbar has a link to their main page. For example, the name of the dictionary in the navbar takes you<br> straight to the All Words page and the same holds for the others. This has been tested manually and it works<br> nicely across all the devices. Materializecss technology was used to achieve this.   
  
## Home Page 
The home page is an introductory page that contains only text which is meant for reading only. However, from the<br> navbar, both a new user and a registered user can navigate straight to All Words, register or login as the case<br> may be. This was tested across all the devices and it works fine.

## All Words
This is the page that contains all the words in the dictionary and both a registered and non-registered user can<br> lookup word and meaning from this page. All a user needs to do is look for the word, drop down the accordion to<br> see the meaning, category and creator of the word. This fulfills the first user story. It has been tested across<br> all the devices and it renders nicely.

## Registration Form
As a new user, you need to register to be able to contribute to the dictionary. In the registration form,<br> if you try to submit the form without filling any of the required filled, an error message appears asking "Please<br> fill out this field". Furthermore, if you supply an unacceptable password i.e. lesser characters, an error message<br> pops up asking "please match the requested format" and if you attempt to supply more characters than allowed, it<br> will not accept it and when you try to register already registered details, it will report back that "Username<br> already exists".<br>
There is a light blue line separating the required fields, this changes to red during filling in of the fields<br> and changes back to blue when correctly filled-in otherwise it remains red to remind the user of the next step. Also,<br> a link is at the bottom of the form to redirect registered users to the Login page. All these controls have been<br> manually tested and found to be working effectively. 
 
## Login Form
If a wrong username or password is supplied an error message returns with a new login page saying "Incorrect<br> Username and/or Password and if you try to submit the form without filling any of the required filled, an error<br> message appears asking "Please fill out this field". There is a light blue line separating the required fields,<br> this changes to red during filling in of the fields and changes back to blue when correctly filled in otherwise<br> it remains red to remind the user of the next step. Also, a link is at the bottom of the form to redirect new users<br> to the Registration page. All these functionalities have been tested and found to be working properly.

## Profile

This page is still a work-in-progress. In the meantime, the page renders nicely and a user can navigate through<br> other pages from there.
 
## New Word Form

This is where all the words in the dictionary are generated. The form is designed similar to the other forms, there<br> is a light blue line separating the required fields, this changes to red during filling in of the fields and<br> changes back to blue when correctly filled in otherwise it remains red to remind the user of the next step. Also, if<br> you try to submit the form without filling any of the required filled, an error message appears asking "Please<br> fill out this field". When all the fields are correctly filled out and the Add Word button is pressed, it takes<br> that user to his/her All Words Page with a message "Word Successfully Added". I have manually tested all these and<br> they are working very fine.

## Manage Category

This page is the exclusive preserve of the administrator. From here, the administrator can perform the CRUD<br> operation on categories which is why the page is named Manage Category. He/She can also perform CRUD<br> operations on All Words. Only the administrator is meant to see this page where categories are built not even the<br> registered members can access this page. This was manually tested and it renders nicely.<br> 

## Log Out

This page is designed to open up the login page when the logout is clicked on the navbar with a message "You have<br> been logged out". This has been tested and it works fine. 

## SPELLING & GRAMMAR

Jargon Dictionary text content and this Readme file have been tested for grammar and spelling mistakes<br> through Grammarly.

## The code has been validated using:

#### W3C Mark-up Validation Service and
#### W3C CSS Validation Service

The check carried out by W3C Mark-up Validation service showed that there is a closing p tag -</p> without the corresponding opening p tag -<p>. When I checked through, I discovered it wasn't true. I provide the screenshot to prove this. Also, it warned that that the section in my base html has no heading. This I considered un-necessary because it's not going to be displayed on the website. The screenshot for this is also attached as follows:
<img src="/static/Images/html-checker.png" style="margin: 0; width: 50%;">  
<img src="/static/Images/html-check.png" style="margin: 0; width: 50%;">

The W3C CSS Validation Service gave a clean bill of healthas shown below.
<img src="/static/Images/css-check.png" style="margin: 0; width: 50%;">  

This site has met the objective of creating an online presence with minimalistic design and content but providing<br> enough information and platform to enable fast contact.<br>
The website has been tested across multiple browsers (Chrome, Safari, Firefox) and different screen sizes<br> 
(Galaxy C5, various iPhones, Huawei, iPad, iPad Pro and laptops) to make sure it is responsive. Materialize has been used to achieve this.<br>
All fonts, images and other attributes have been changed accordingly to fit different screen sizes. Media queries have<br> been used to make them work.


# Deployment 

The site was developed using Gitpod full template - workspace to commit and push to GitHub.<br>
GitHub Pages is a static site hosting service that takes HTML, CSS, and JavaScript files straight<br>
 from a repository on GitHub, optionally runs the files through a build process, and publishes a website.

## The following steps can be taken to access my page from the GitHub repository. 

On Github navigate to my-first-milestone-project<br>
From the menu at the top click on settings<br>
Scroll down to the GitHub pages section<br>
Under the Source section click on the dropdown menu and select Master Branch as your GitHub Pages publishing source.<br>
Select save.

## To Clone the Repository
Navigate to the Github remote repository: oakerele-web.github.io<br>
Click 'Clone or Download'.<br>
Copy the clone HTTPS or SSH by clicking on the copy button.<br>
Open Git Bash.<br>
Change the current working directory to the location where you want the cloned directory to be made.<br>
Type git clone, and then paste the URL you copied.<br>
Press Enter. Your local clone will be created.<br>

***The URL for this project is as follows:***

https://github.com/oakerele-web/milestone3-project


# Credits 

## Content 

All the text contents in this project are original because they are written by me.  

## Media 

All icons are from the Bootstrap website including the styling while the font styling is from Font Awesome website.<br> 
The Logo was formed and designed by me through Placeit.org using the fake name formed for the gym.<br>
Pictures used in the gallery page and the home page were copied from existing websites of gyms on the internet<br>

## Acknowledgments 

The Codeinstitute Resume project by Matt Rudge is what inspired this project and I chose this project from a list of<br>
other proposed projects by the Institute.<br>
Special thanks to Maranatha Ilesanmi - my course mentor - first for his objective view of the project at the selection<br> 
stage then assisting me with applications for my Wireframe/Mockups and finally this Milestone 1 project which he has helped<br> 
me a lot to review, re-structure and suggested solutions to my pertinent questions. I also thank Claire of the Student Care<br> 
department for her support and understanding when I needed adjustment to my calendar. I am also grateful to all our colleagues<br>
in Slack, thank you.   

## Disclaimer 

*The content of this website is for educational purposes only.*
