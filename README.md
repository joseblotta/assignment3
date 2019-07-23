# assignment3
Assignment 3 / Angular Intro

Jose Molinari Blotta / 991496251 / molinajo / Davis Campus FOR SYST24444

Assignment 3 (10%) / Angular Intro
Create a new Angular project called yourLoginNameA3 / This mobile assignment will need to be formatted for both landscape and portrait views.
See New Project-DefaultSetup for a review of how to start a new project with class defaults

Create a header component and a footer component
Format both header and footer components (tags to be used; ex. h1 and h3) to the same formatting in regard to background and text colour plus any other formatting of your choice; You can format each .css for header and footer or use the styles.css to create global styles for your tags

Create a file in the app folder called yourLoginName.ts in the app folder. In this file, create a class called YourLoginName that includes the following definition with your choice of label and type (see student.ts file in our in-class example as a reference):
Your student number, your name, your login name, your campus, and assignment title
In both the header and footer component .ts files, import and create a variable to fill in the class data with your information.
Note: For this assignment, you will duplicate the data in the header and footer components; we will learn later how to set it once and use in multiple components
In the header component html file, use string interpolation from your personal class data to display assignment title / your name in an HTML header tag (not hard-coded).
In the footer component html file, use string interpolation from your personal class data to display your name / your student number / your login name / your campus in an HTML header tag (not hard-coded)
Note: You may need to stop the node server and start up again after creating a class. Use Ctrl+C to terminate batch job then "ng serve" again after class file is created.
Be sure to update your app.component.html with the components you want to display

Create another .ts (example: songInfo.ts) file in your app folder to hold another class for songs that will include the following definition (your choice of file name and class name):
song name / artist / genre / year released / picture
Create a data file (hard-coded) called mySongs.ts. Create data for 4 of your favourite songs with the data from the class created (use myClasses.ts in our in-class exercise for reference)
Note: Pictures will need to be included in the images folder created for the default setup. The picture itself can be anything you want.
Create a component called detail. Create a structure using a grid-area that include a navigation section that goes across the screen then 2 areas (one on the left and one on the right) under the navigation section. One side will hold a picture and the other will hold song details. For Portrait mode, display all sections vertically (Navigation on top of song details on top of picture)
Be sure to import your song data into the detail.component.ts and setup a variable to hold the data (see class-list.component.ts in our in-class project for reference)
In the detail.component.html, setup a directive (*ngFor) to create 4 buttons in the nav section; be sure to include an index so you can capture which is selected so you can display detail data and the picture from the data file based on the button clicked; also be sure to include a (click) event to call a function to find correct song data.
Note: You can use *ngFor not only with list items (as we did in our in-class exercise) but also with buttons or any other HTML tag.
How I will be grading the assignment...

I will be using Chrome's Toggle Device Bar for iPhone 6/7/8 in Landscape and Portrait modes using your submission URL
Remember, this is a mobile site so formatting and layout should reflect this; too much scrolling or whitespace will reduce your mark.
What to submit...

You will be submitting your cPanel or github URL to the comment area and a ZIP of your project's src folder in the SLATE dropbox
For help with publishing/deploying, see the AngularDeployment Headout

Each assignment must be done individually.
    I will be checking for copying especially if the assignments look similar and will file an academic integrity breach if necessary

This is not an assignment that should be started the day it is due.
    Since you have 2 weeks to complete the assignment, NO EXTENSIONS to the due date will be given.
Grading Rubric...

Header and Footer Components / Setup plus formatting	1
Class creation with your personal data and inclusion in the header and footer components	1.5
Song class creation plus data file	1.5
Detail Grid Layout and formatting	2
Detail Data including working buttons	4
If the project is not published in cPanel or github, 5 marks will be deducted before grading even begins
