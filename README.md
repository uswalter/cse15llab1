# cse15llab1
Remote Access
CSE 15L Lab 1

Wangkai Qiu
09/30/2022

![alt text](http://url/to/img.png)

 
 
Part 3 – Visual Studio Code - 10 mins
Write down in notes: Everyone should share a screenshot of VScode open – help folks figure it out if it won’t install. If someone gets stuck, take a screenshot of the error message



Part 4 – Remotely Connecting - 15 mins
Write down in notes: When you’re done, discuss what you saw upon login. Take a screenshot or copy/paste the output. Did you all see the same thing? What might the differences mean? Note the results of your discussion in the notes document.






Tells us that there are 3 hosts with the current time, number of users, and the load averages. 


Part 5 – Run Some Commands
Write down in notes: Copy at least one example from each group member, with an explanation, into your shared notes doc.



Pwd = print working directory. Tell us that we’re on linux. Then the rest of the file path including my username. 


Cd = change directory, moving from one “folder” to another




ls lists the directories/files and cd let’s us change directories
Part 6 – Moving Files over SSH with scp
Write answer in notes: Try to get a screenshot of everyone successfully *using scp and ssh. If someone can’t, no worries! Get a screenshot of where *they got stuck (don’t try to resolve an error for more than a few minutes) and *put that in the notes so we can help with it later.


This tells us the operating system, the user name, and the user profile. 




The outputs between the client and the server are different as they both show different operating systems, user name, user home, and directory. This means that getProperty gets certain information pertaining to the system that the command is being run on.

Write answer in notes: What’s different about the output when you run this on the client vs. the server? What does this mean for what getProperty does?

Running the java file through SSH tells us the user which is cs15lfa22ol and the operating system which is Linux. The other properties that are retrieved through the getProperty method are the user.dir (user directory) and user.home. 
 
The client will show the local operating systems and properties of the machine that the client is on, but running it on the server will show the properties of the server that the program is run on.The difference is the operating system and the user name change.  
Write an answer in notes: How long did it take you? (Not everyone has to do this, but someone should.) Assume you’d have to do this process 100 times over the course of a PA. How long would you spend copying and running the file?

It took us a minute to do this because we forgot to put the ~/ for the file path. Knowing the process now it should only take a minute to copy each file to the server. This only changes based on file size and upload speed. 

It took me not very long because scp, compilation, and program running all went smoothly - J.L.
Part 7 – SSH Keys
Write down in notes: Try to get everyone to the point where they can do this, and take a screenshot of logging in without a password. If you can’t, share a screenshot and description of where you got stuck!

 
 
 
Write down in notes: Repeat the timing experiment of editing and running WhereAmI.java now that you don’t have to use a password. How much time is saved per run?

 
 
Part 8 – Making Remote Running Even More Pleasant
Write down in notes: First try using just what we learned in this lab, and document the best process you came up with. Try to get the total time for a run after editing and saving to under 10 total keystrokes/mouse clicks, including all typing. A “keystroke” is pressing one key on your keyboard. For example, pressing the up arrow counts as one keystroke, and typing “java” counts as 4.

