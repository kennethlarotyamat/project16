This is the place where 
I will work and upload project 16

...

[Project 16 Requirements]

Page 1. Project: Security
Sanitized Variables & Relative Paths
Goals
By the end of this project you will:
Restrict user inputs
Validate user inputs
Sanitize user inputs
Include a file using a relative path
Introduction
This project aims to bring together your knowledge on the use of localhost and basic web security tactics.
Business Context
There are many ways to add forms to websites that vary according to context and platform. Nevertheless, your ability to build a basic form in HTML and improve its security using JavaScript will serve you well no matter which context you ultimately develop in.
Next

Page 2. Instructions
Instructions
Begin with the Newsletter sign up form developed locally in Day 2, Lesson 1 Defending against XSS.
Add a phone number field to your Newsletter Signup form.
Use maxlength attribute to further restrict user inputs.
Create a JavaScript function to retrieve the phone number input from the user.
Check that the phone number input is not blank.
Check that the phone number contains only numbers and dashes.
If there are any issues with the phone number field, prepare an error message for the user.
If there are no problems with the phone number input, sanitize it before submitting the form.
Submission steps:
Before you click on "Mark as Completed":
You need to do one of the following: either upload all of your files to Codio or deploy a GitHub Page for this project.
Also, if you mark this project as complete but any of the boxes are blank, your TA will be unable to grade your project.
Codio upload:
Make sure all of your project code has been uploaded to Codio.
If you did not write your code in Codio, you will need to import all of the required files into your workspace file tree.
You can do this by going to File => Upload Files, and either manually importing each file, or dragging and dropping your project folder.
Please refer to this video if you are unsure of what to do.
GitHub Pages:
If you would rather upload your project to GitHub, please make sure to have the project deployed as a GitHub page so we can thoroughly test it.
If you are unsure of how to do this, please follow these instructions.
It is important to understand you will need to make a separate repository for every project. You cannot deploy multiple pages from the same repository, even with different branches.
Also, no matter whether you uploaded your files from your computer or not, make sure to thoroughly test your code! This only takes a few minutes, but will prevent the amount of resubmissions because you missed something.
GitHub Repo & Pages
If your project is uploaded to Codio, simply type "N/A".

Submit Answer!
Mark as CompletedBack to dashboard

...

1. Project: Algo Practice & Add to Personal Website
Overview

For Project 13, you will get a little bit of practice tackling coding questions, 
upload the code for your attempts to GitHub, and also add to your website’s project session!


Step One


Complete the following:

Sign up for free accounts on 
LeetCode, [done]
Hackerrank, and [done]
CodeWars [done]

Create a GitHub repository [done]

with 3 folders (one for each of the above platforms), 
LeetCode, [x]
Hackerrank, and [x]
CodeWars [x]


and a brief README file [x]

with at least 2 sentences describing your repo [x]

[ i really don't want to create a new repository]

[https://kennethlarotyamat.github.io/miscellaneous/]

[I will continue working on this project directly in the above repository as of 10/26/2023 09:47 PM]

Work on 2 - 3 beginner level challenges from any of the above platforms (or one from each!)

Push all of your code to the GitHub repo you created

Submit a link to your repo and, if it’s a private repo, add your TA as a collaborator

NOTE: Try your best to solve the coding challenges, using comments to describe the thought 
process behind your approach. You can also ask your TA for help with these. But even if you 
can’t arrive at a solution that’s okay! The only requirement for these challenges, in terms 
of this project submission, is that it’s evident that you employed critical thinking and attempted a solution.

Step Two

Add the calculator mini project (from Lesson 1.3), or another project you completed 
outside of class, to the projects section of your website. The styling is up to you, but 
you should include a screenshot, a title, a brief description, and a link to the code on GitHub. 
Finally, submit the GitHub link below (again, if it’s a private repo, be sure to add your TA as a collaborator).
Happy coding! 🚀
GitHub Link - Algo Practice
Submit Answer!

GitHub Link - Additional Code Project (calculator or other)
Submit Answer!
The only thing worse than not knowing why some code breaks is not knowing why it worked in the 
first place! It’s the classic “house of cards” mentality: “it works, but I’m not sure why, so nobody 
touch it!” You may have heard, “Hell is other people” (Sartre), and the programmer meme twist, “Hell is other people’s code.”
I believe truly: "Hell is not understanding my own code.”
― Kyle Simpson, You Don’t Know JS: Async & Performance
Mark as CompletedBack to dashboard

...


























...

I usually don't start on a project until the day it's due, but that's lead to challenges. so I'm going to 
at least take a look at it today.

I'm honestly still refining project 12, even though I've already turned it in, and my TA has already graded it.

...

1. Project: Algo Practice & Add to Personal Website
Overview
For Project 13, you will get a little bit of practice tackling coding questions, upload the code 
for your attempts to GitHub, and also add to your website’s project session!
Step One
Complete the following:
Sign up for free accounts on LeetCode, Hackerrank, and CodeWars
Create a GitHub repository with 3 folders (one for each of the above platforms), and a brief 
README file with at least 2 sentences describing your repo
Work on 2 - 3 beginner level challenges from any of the above platforms (or one from each!)
Push all of your code to the GitHub repo you created
Submit a link to your repo and, if it’s a private repo, add your TA as a collaborator
NOTE: Try your best to solve the coding challenges, using comments to describe the thought 
process behind your approach. You can also ask your TA for help with these. But even if you can’t 
arrive at a solution that’s okay! The only requirement for these challenges, in terms of this project 
submission, is that it’s evident that you employed critical thinking and attempted a solution.
Step Two
Add the calculator mini project (from Lesson 1.3), or another project you completed outside of class, 
to the projects section of your website. The styling is up to you, but you should include a screenshot, a 
title, a brief description, and a link to the code on GitHub. Finally, submit the GitHub link below (again, 
if it’s a private repo, be sure to add your TA as a collaborator).
Happy coding! 🚀
GitHub Link - Algo Practice
Submit Answer!

GitHub Link - Additional Code Project (calculator or other)
Submit Answer!
The only thing worse than not knowing why some code breaks is not knowing why it worked in the first place! 
It’s the classic “house of cards” mentality: “it works, but I’m not sure why, so nobody touch it!” You may have 
heard, “Hell is other people” (Sartre), and the programmer meme twist, “Hell is other people’s code.”
I believe truly: "Hell is not understanding my own code.”
― Kyle Simpson, You Don’t Know JS: Async & Performance
Mark as CompletedBack to dashboard

...

... [Start Solution Area]
... [End Solution Area]

... [Start Working Area]

















[ I have an idea, and my idea is to use my carousel project, repurpose it, and use it to display my answers.]
[but there was something else too, I need to figure out how to make it scrollable.]
[it works well enough for images, but it doesn't work that well for iframes]
[I'm tired and I'm going to come back around to this my expectation is that this shouldn't be too hard]
[considering that i've already done 2 seperate ones.]

[LeetCode Solution Start]

                            var x = 121;

                            var digits = x.toString().split('').reverse(); 
                            var reverseDigits = digits.map(Number)
                            console.log(reverseDigits);

                            var joinreverseDigits = reverseDigits.join('');
                            console.log(joinreverseDigits);

                            function isPalindrome() 
                            {    
                                if (joinreverseDigits == x){
                                    return true
                                } else {
                                    return false
                                }
                            } 
                            isPalindrome("");

                            console.log(isPalindrome(""));

[LeetCode Solution End]

[CodeWars Solution Start]

                            function isPalindrome(x) {


                                var testString  = x ;
                                var splitString = testString.split(""); 
                                var reverseArray = splitString.reverse("");  
                                var joinArray = reverseArray.join("");     
                                var lcArray = joinArray.toLowerCase();
                            
                                

                            if (lcArray === testString.toLowerCase()) {
                            return true;
                            } else {
                            return false;
                            }

                            }

[CodeWars Solution End]






















... [End Working Area]

[ I have an idea, and my idea is to use my carousel project, repurpose it, and use it to display my answers.]
[but there was something else too, I need to figure out how to make it scrollable.]
[it works well enough for images, but it doesn't work that well for iframes]

...

I think this is the project where we had to add eachother to eachothers github repositories.

I'm going to remove myself from chris's repository.

...

DBPF                   1¢`1¢`          (                                                   °   û 6á  ô   à  á ˆ ž  • #DãGrapevine ntry CplubÄ  ÞàDefaÇóèctoŽ  ¤€)HB„wŒ ´  ‚…Ì  ÿÌ  ÿÄ  ½áMid Citi²€?esà’Ñ  €Ž³qžÛà  
°‚à   Á
BÌ  ÿÌ  ¿ünÝ©nÝI   6  nÝ©nÝI   `   °   ïkèïkèk(     