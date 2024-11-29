<!--
File: Readme.txt
GUI Assignment: Homework 4, Part 1: jQuery Validation
David Lee, Umass Lowell, david_lee2@student.uml.edu
Date: 11/28/2024
Description:
For this assignment we were responsible for implementing the validation method present in the jQuery library.
Similar to the error checking that we implemented when we first started our third assignment, here we were required to create error messages which would display on the right hand side of the input space.
I implemented the following changes to my code: in index.html I removed the function call generateTable from the form and instead relied on document ready in my script. I added new constraints and messages 
that would pop up if the user put in any invalid inputs. To account for the changes I shifted where the table would display to the bottom of the page and the area for user input to be more towards the top. 
I made some changes to my style.css as well as inlining some css to account for spacing for my margins/padding. Here are some the resources that I consulted to get a better understanding of the validate method:
- jQuery validate syntax, etc: https://jqueryvalidation.org/validate/
- I referred to the lecture notes/slides for some basic syntax related stuff more specifically document.ready which we learned in class.
I added additionally another script src line which can be observable towards the top of the html document.
The main observable change in Part 2 can be observed where I wrote the script directly underneath the body in the html file, which likely isn't best practice.
-->
