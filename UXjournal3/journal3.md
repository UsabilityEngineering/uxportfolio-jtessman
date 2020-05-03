<h1> Journal entry 3 </h1>

**LittleBrother repository:**
https://github.com/jtessman/LittleBrother

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;For my last journal entry, I'd like to talk about my thought process for incorporating the UX terms that we have learned about into my senior project. Even though I intended for this project to be a tool for my own personal use/to show off my coding skills on Github to potential employers, I did consider the possibility of someone actually setting up my project and using it because they want a free and open source security camera manager for Ubuntu Linux. Creating software that can actually be used by someone is a great feeling, and a major motivator for this project throughout the semester.

![Alt text](/uxportfolio-jtessman/UXjournal3/LittleBrother.png)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;For starters, one of the most obvious things that I implemented was a README.md file (a staple of any programming project). In it, I describe the libraries that are needed in order to make my project run properly. This is something that any experienced programmer would do. I do not know as to whether or not this counts as **learnability**, as I would count this as more of a one-time setup instead of the time it takes for a user to be fully oriented with all of the features of the project. Nevertheless, something like this is crucial for both the average user, as well as my fellow programmers. Something that I can potentially add to it is listing out the libraries that the libraries depend on.

![Alt text](/uxportfolio-jtessman/UXjournal3/README.png)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Most of the features that I implemented for the sake of UX were in the final few weeks of this semester, as I wanted to focus 100% on functionality first. The first thing that I implemented purely for UX reasons were pop-up dialogue boxes for when the user tries to make the program detect a camera that is not there. This may seem very miniscule, but the way I was conveying this task first was I had the error only print out to command line. The user may not be paying attention to the command line, and therefore this could have potentially been a great source of frustration on the users behalf. Plus, pop-up boxes are a well-known convention in applications. I therefore would put this feature under the **satisfying** category.

![Alt text](/uxportfolio-jtessman/UXjournal3/DialogueBox.png)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;One of the features that was more challenging to implement but was absolutely worth the trade-off, was email notifications. Every time the camera detects motion, it captures a short video of said motion and then sends a picture of the motion to the specified email address. This was one of the more important features to implement in my opinion, as it drastically enhances the **usefulness** of the program.

![Alt text](/uxportfolio-jtessman/UXjournal3/MotionDetection.png)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The last two features that I implemented from a purely UX perspective, are the abilities to change the folder in which the videos and pictures are saved, as well as the email address that the email notifications are sent to. These are implemented as a button, and an entry field at the bottom of the GUI. I coded it so that the label of the button changes to the name of the folder that the user chooses, in order to make it abundantly clear what it's for. Because of this, I would file this feature under the **effectiveness** feature. As of right now, the user has to re-enter the email and folder name every time they open the application up, and something that I could implement in the future to make it even more effective is a very small sqlite file that stores the user's email and folder name. 

![Alt text](/uxportfolio-jtessman/UXjournal3/FolderSelection.png)
