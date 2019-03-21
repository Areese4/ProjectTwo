**Author:**
Andrew Reese

**Email Address:** 
a.reese626@gmail.com

**Phone Number:** 
(205)-577-7642


# ProjectTwo
The Second Project for CS304

## Overview

This project was made in NetBeans for a 100-point grade in one of Jacksonville State University’s computer classes. The class titled Computer Fundamentals two focused on the main principles of the coding language, Java. The program isn’t very extensive but is a good example of many things we learned in the class. The best way for this to work on your computer is download a Java compatible IDE; i.e. NetBeans. Download link provided below.

https://netbeans.org/downloads/8.2/

## What Does the Program Do?

Once the program is run, the system gives the user two options. This will look something like this.

```
Enter option 1 or 2 to test the function: 

Option 1 will test Palindromes.
Option 2 will test Pascal's Triangle. 

You are choosing option:
```

The first option is going to give you a prompt to enter a word, then it is going to check and see if it is a palindrome. A palindrome is a word that is spelt the same way front ways or back ways. For example, racecar would be a palindrome because it spells racecar both forward and backwards. Example of this will look like:

```
You have chosen to test Palindromes! 

Enter a word to check if it's a palindrome.
Enter stop to quit the loop. 

You're checking the word:
```

The second option is also going to prompt the user for an input but this time it will not be a word but a number. This number the user gives will dictate which line of Pascal’s Triangle will be given to the user. Google describes Pascal’s Triangle as a triangular array of numbers which those at the ends of the rows are 1 and each of the others is the sum of the nearest two numbers in the row above. At the bottom of the page an example of what this looks like will be given. An example of what the first step is:

```
You have chosen to test Pascal's Triangle! 

Which line number of Pascal's Triangle?
```

## Installation

From the following link, https://github.com/Areese4/ProjectTwo, you can get to the repository for the Project Two. Once there, you can click either the title of the code which is “ProjectTwo.zip” or you can click the green button that is titled “Clone or Download”. Once you have clicked the “Clone or Download” button you can click “Download ZIP”. You should be able to choose where the ZIP file is downloaded to for easier access when trying to run the program. 

After downloading the ZIP file will be where you saved it at and you should be able to right click on the file and choose “Extract All” which will extract all of the files you will need to compile and run the Java Program.

## Running

After the installation process you are now able to run the program. The easiest way to do this is to open the recently installed NetBeans Program, if you previously did not have it. Once you have NetBeans up and running you will need to do the following steps:

>1.	File
>2.	Open Project
>3.	Find ‘ProjectTwo’ where ever you extracted the files at, then select the one file with Java logo next to it. Picture is shown below for your help
>4.	Once the project has been chosen, click “Open Project” and you should have the left most tab open with Project2 now
<img width="1280" alt="Opening" src="https://user-images.githubusercontent.com/37488517/54752354-c77f2480-4bab-11e9-8a9f-bfa32b1232a4.png">

Now that you have done those four steps to get the code into NetBeans, it is good practice before running the code to hit the ‘Clean and Build Project’ button. This is located on the top bar of NetBeans; the button looks like a hammer and a broom. That should only take a couple of moments, you can check the progress bar at the bottom of the page in NetBeans to know when it is done.

Once the Clean and Build is finished, and no errors occur, which none should for this project. You can choose the ‘Run Project’ button which is just right of the ‘Clean and Build Project’ button. It looks like a normal play button or a somewhat rounded out triangle facing right. Once clicked it will start to run and do what was previously stated in this readme.

## Examples of the Second Option for Reference

```
Enter option 1 or 2 to test the function: 

Option 1 will test Palindromes.
Option 2 will test Pascal's Triangle. 

You are choosing option: 2
You have chosen to test Pascal's Triangle! 

Which line number of Pascal's Triangle? 11
Line 11 of Pascal's Triangle is: 1 10 45 120 210 252 210 120 45 10 1
```

As you can see I am running the program, and then when I am given the opportunity to pick which option I want to use I chose the second one. Once the program recognizes I have chosen that option it proceeds with the next step in the code which asks what line number of the triangle I would like to see. So, I told it to show me the eleventh line which it did.

**Side Notes**

Now the code is downloaded and opened in NetBeans if you want to you can open and look at the executable code.  If you choose to do so double click ‘Source Packages’, then double click ‘Project2’ inside that ‘Source Packages’ folder you will see the three Java files that contain the code. If you highlight all three of them and right click you will see the ‘Open’ option, click that. Now that you have the code open, which is three separate Java files, you can see what each one does.

You may have noticed that there is more than one file that could be selected in the project2 subfolder. That is because StepOne.java and StepTwo.java are both different classes used in the main project file. 

StepOne.java is going to deal with the palindrome test setting up and making sure that each letter is the same backwards and forwards.

StepTwo.java is going to deal with Pascal’s Triangle given line. Which is taking the number, our input, and doing the math to figure out what line that is.
