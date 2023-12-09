# DS511_Journal

Each entry should answer these questions:

  * What were some things you learned in the module?
  
  * What do you think were the most important concepts?
  
  * What was challenging for you? How can you learn it better?
  
  * Which parts did you enjoy?

Each entry should:
  * Use full sentences to show good writing and clear thought process
  
  * Be limited to one or two paragraphs (it should be fairly brief)
  
  * File format: Use a Word doc or similar. Recycle the same file throughout the course. Action Item: Write a journal entry for this Module. It will be submitted later.

## Module 1
The most important thing I learned is some of the command function that are important to creating and using AWS to run my ubuntu instance.

List of tools that I used or thing that is important to use: 

* ssh -i kyd3zj_DS5111.pem ubuntu@<Public_IPv4> 

* 'vim Filename.file' was used to create makefile and anyother file such as python. 

* 'rm' -> remove a file or 'rm -rf' -> for directories to recursive force 

* 'mkdir' -> was to make a directory to that I used a lot. 


The challenging part was working at the command line. I have barely used the command line for coding and dealing with project in the past but most of the course deals with the command line. I am creating directories, creating makefiles, and many more at the command line. At first, when I made the makefile using 'vim makefile', I did not know how to save it. ':w' was the way to save a file that was opened using the 'vim'. When I opened the makefile later, I was not able to write in it until I hit 'esc'. To quit of the makefile, I had to 'q' and to save and quit, I had to ':wq'. These were new and important concepts that I need to pick up, but also challenging at first. I enjoyed learning what a makefile can do and the importance of it. 

## Module 2 - SW Skills 1
The things I learned this week in class and outside were some of the basics for programming, such as making sure the variables are named appropriately for easy understanding. I things that that is the purpose of the Eagleson’s Law. I found the class interesting when talking about memorization because it is important that people do not spend time repeating duplicate task. It is common in the work place to maybe work on the same thing as another person because the communication was not clear and it could be said in code as well. It is better to write in a way that someone does not need to do to extra work to understand something.

A few linux setup commands that are useful:

* “bin” for binary (executable function)
  
* “lib” for library
  
* “vendor” for external packages (mostly used for “env”)

One thing that is new to me or challenging is the decorators. I found this information new and challenging. Decorators are included on the line above the function with an “@” symbol. 

## Module 3 - SW Skill 2
I learned a lot from doing the assignment then I thought. I started off with a simple makefile and now I got to see what a simple makefile can do for me. After creating the repo, I organized the directory the way that assignment told me to. I worked with creating different directories and files with a simple “vim filename.filetype”. I had to used these files to come up with a makefile that could run the clockdeco_param.py file and test it with test_clockdeco_param.py. 

The biggest difficult I had for this module is understanding all the parts. When I was working on the assignment, I was not able to run my pytest or pylint. I learned that I needed to open up the env and work in it to get my test to pass. I found this an interesting lesson because I thought I can get everything to work without entering the environment that I created. I also had an issue with “;”, so when checking online, I found that “&&” has a similar idea to “;”. Even with all of these challenges, I was able to complete this lab and learned a lot from it. I found this lab helpful in understanding the whole command line and what it can do. 


## Module 4 - SW Skill 3
This week the focus is on TMUX and its purpose. In class, I was able to see a demo on the use of TMUX and how interesting it is, but I found it very hard to believe that it is an effective tool for collaboration. The idea of having everyone on in the group working on the same project at the same time was great, but when is this particle. Usually in the projects that I have worked on, we divide and conjure or use github to clone the repo and work on it on a separate branch and do a pull request. I never ran into an issue where 3 or more people had to work on a file at the same time.

 The idea and the concept were easy to understand, but getting the TMUX started was slightly confusing. You would need the people who are going to work on the TMUX session with you to provide their SSH key so they can be connected to the instance and file. I found this part harder to understand in the demo and wondering about the security concerns. The book goes in to details on how to start a TMUX session. Another interesting fact that I found is that the TMUX will keep running even after exiting the “your” shell, which makes it great when you have more people working on it. 

 
## Module 5 - Testing
This week is the about testing and learning about way to create tests for your code. I have done this time of work in my previous classes, but it feels new because I am doing this in bash. In class, I learned about different types of testing, such as quality control testing and gherkin type testing (never heard of this one). Unit testing is what I believe we have been taught because it focuses on testing function and programmers expected results. “seed” is an important part in testing, when dealing with random outputs to make it repeatable. Pytest is what is what we will be using for the class. 

When it came to the lab, I found the most difficult part was the different tests. One test to pass, one test that fails, conditional test, a skip test, and parameterized test. Note to self: All the tests have to start with “test”. I understand and can easily do the first two types of tests but the last three were new to me in some sense. I had to relearn how to write a conditional test, which required some reading and research on my part. The direction for the skip test was easy because of the decorators, which played a important role in creating tests. The parameterized test was harder to understand but with some digging, I was able to figure it out. The book did not do a good job with the parameterized testing. I understand the decorator being involved but not how the test needed to be created. I enjoyed this lab even if it provided me with challenges because I was able to see how to create interesting and new tests and play around with decorators and function I never did before.

![image](https://github.com/Lankalapallio/DS511_Journal/assets/111662645/0697c84e-8b59-45ae-9ee5-47fe5418061b)


## Module 6 - CI/CD

This week I learned about CI-CD, which is Continuous Integration and Continuous Deployment. These are new techniques/idea that I learn because I do not work with code as a profession or in the industry of handling code, so it is nice to hear and learn about them. For summary purpose, continuous integration (CI) is when coders test their code as they write them, such as unit or module tests. Then the code gets tested by other people to see if it can be integrated into the larger code, such as automation. Continuous delivery (CD) is when the testing passes and works as intended, the package will be pushed with new version. The whole process is like a sideways figure 8. I like these concepts because it helps me understand the industry that I want to get into and what they will except. After pushing with the validation.yml for my SW2_Lab, I learned or got an understanding the github actions. I would like to see ways we could use these more because I found them easy and fun to use, because I did not have to open AWS instance, login, and then run the code. I can do everything with a click of a button on github action. 


## Module 7 - Containers

## Module 8

## Module 9 - DBT (Data Build Tool)

## Module 10

## Module 11/ 12

