# Milestone1
team Github repository: https://github.com/lianh9/Milestone1.git

Team member names and Github users :

Lian Huang, lianh9

Wisely Chan, wiselyc

Pulos Gorgees, PolusG

# Use Case Description

Date:9/15/2021

Product Name:

Problem Statement:

Non-functional Requirements:
1. The response time should be within 2 seconds.
2. The App shoule be user friendly and easy to use.
3. App should be able to install on Windoms or Mac.


# Use cases
1.Muti-language

2.User register and login

3.Delete account

4.Share notes with other people

5.Input a markdown file and output flash cards

6.Share flashcards (add to their account)

7.Render markdown notes

8.convert markdown notes to pdf

9.Todo tracker

10.Visualize hours worked and projects

11.Visualize time blocks

12.Create graph of connections between notes



Use Case Name: Change system language 
## Summary
A user who logged in can change the system language 
## Actors
actor : User, system
## Preconditions
* The student/user logged in
## Triggers
The student/user selected “language” option
## Primary Sequence
1.System prompts the user other available languages list.

2.User selects the language they want.

3.System changes the language.
## Primary Postconditions
* The user changed the system language
 
Use Case Name: User register and login
## Summary
A student or potential user can make an account and log in.
## Actors
actor : Student/User
## Preconditions
* The student/user download this study app.
## Triggers
The student/user clicked the “register” option
## Primary Sequence
step 1 action: System prompts makeup username and password window.

step 2 action: User creates their unique username and password.

Step 3 action: System save their account information.

Step 4 action: User login with their account information.

Step 5 action: System verify user login information, login user if information match otherwise fails to login.
## Primary Postconditions
* The user created an account and can log in with the account information.
 
Use Case Name: Delete account
## Summary
The user can delete their account information.
## Actors
actor : Student/User
## Preconditions
* The student/user logged in.
## Triggers
The student/user clicked the “delete” option under account information.
## Primary Sequence
step 1 action: The user deletes their account.

step 2 action: System deletes the user’s account information.
## Primary Postconditions
* The user deleted their account and can’t log in with their account information anymore.
 
Use Case Name: Share notes with other people
## Summary
The user can share their notes with other users.
## Actors
actor : Student/User
## Preconditions
* The student/user logged in.
 
* The people the user sharing notes with also has an account.
## Triggers
The student/user clicked the “share” option.
## Primary Sequence
step 1 action: The user chooses the notes to share.

step 2 action: The user enters the information who receives the notes.

Step 3 action: The system sends out the notes to the person the user entered.
## Primary Postconditions
* The user shared their notes with other users.

Use Case Name: input a markdown file and output flash cards:
## Summary
Let the user type in a text file and the file turns into a flash card.
## Actors
The user
## Preconditions
* User has to be logged in
## Triggers
Customer selects create flash card option
## Primary Sequence
1. App asks the user if they want to create a flash card
2. User types whatever they want on the text file
3. User can select if they want to add something on the back of the flashcard.
4. User selects “Done” if they are finished creating the flashcard.
5. System creates the flashcard.
## Primary Postconditions
1. The user creates a flashcard

 	a) Flashcard is saved to folder 
 
	b)Flashcard can be viewed whenever they want
 
2. The user does not create a flashcard

 	a)Flashcard is not created
	 
## Alternate Sequences
* The user leaves the text file blank

	a) The text file is deleted.

	b) Tells the user to put something in the text file.
 
### Alternate Trigger
### Alternate Postconditions

Use Case Name:Share flashcards (add to their account)
## Summary
Allows the user to share their flashcards to other users
## Actors
users
## Preconditions
* The user has logged in
* The user created flashcard(s)
## Triggers
User clicks on the “share” button
## Primary Sequence
1. The user selects a flashcard to share
2. Select who they want to share the flashcard to
3. App confirms that flashcards are shared.
## Primary Postconditions
* The flashcard gets shared
* The flashcard does not get shared
## Alternate Sequences
*The user shares with an account that does not exist

 	a)The system displays an error message
 
 	b)The system tells user to share with real account
### Alternate Trigger
### Alternate Postconditions

Use Case Name:render markdown notes
## Summary
Allows the user to type into text box and create notes
 
## Actors
user
## Preconditions
* User has created an account
## Triggers
User clicks on the “create notes” button 
## Primary Sequence
1. User types in the text box
2. Clicks on “done” when finished writing notes
3. App confirms note is created.
 
## Primary Postconditions
* Markdown note is created
 
## Alternate Sequences
### Alternate Trigger
### Alternate Postconditions

Use Case Name: convert markdown notes to pdf
 
## Summary
Grabs the markdown notes the user created and converts it into a pdf file
 
## Actors
User
System
 
## Preconditions
* The user is logged in
* User has already created a note
 
## Triggers
User clicks on the “Convert note to PDF”
 
## Primary Sequence
1. User selects a note that they created
2. User selects the “Convert note to PDF”button
3. The System grabs the markdown text file and converts it into a pdf file
4. PDF file turns into a downloadable link
 
## Primary Postconditions
* The markdown note turns into a pdf file
 
## Alternate Sequences
### Alternate Trigger
### Alternate Postconditions

Use Case Name: Todo tracker
## Summary
A student who has logged in can see what tasks there are to complete and are already completed
## Actors
The student.
## Preconditions
The student has logged in and there is at least one task.
## Triggers
Student selects to view tracker.

## Primary Sequence
1. The system displays the task to be completed and marks the completed tasks.
2. The system prompts the student to the next available task.
3. The student confirms they wish to proceed with the task.
4. The system leads the student to the task.
5. System returns “You are on the task [tasnk name]”.
6. The system displays the completion percentage of the task.

## Alternative sequence
The student does not select a task.
The system displays a message to remind the student.

## Primary Postconditions
The student starts a new task
The selected task is displayed
OR
The student does select a task.
Todo list remains the same

Use Case Name: Visualize hours worked and projects
## Summary
A student who has logged in can see how many hours they have worked in total and for each project
## Actors
The student.
## Preconditions
The student has logged in.
## Triggers
Student selects to view hours worked.

## Primary Sequence
1. The system displays the projects.
2. The system displays the total hours worked.
3. The system can choose to view the hours worked on a specific project.
4. The student clicks to visualize the hours worked.
5. The system shows a chart to the student with information on hours worked.

## Alternative sequence
The student does not visualize.
The system does not display anything.

## Primary Postconditions
Student tracks the hours worked
The student chooses to visualize the hours worked
A chart is displayed.
OR
The student does visualize.
Screen remains the same.



Use Case Name: Visualize time blocks
## Summary
A student who has logged in can view a calendar-like view to see their tasks for the week.
## Actors
The student.
## Preconditions
The student has logged in.
## Triggers
Student selects to visualize time blocks.

## Primary Sequence
1. The system prompts the user for the option to visualize time blocks.
2. The student confirms to visualize time blocks.
3. The student views the items to do for the week.
4. The student clicks a task and accesses the task.
5. The system crosses the tasks completed from the visualization.

## Alternative sequence
The student does not visualize.
The system does not display anything.

## Primary Postconditions
The student visualizes the time blocks
A calendar view is presented to students with tasks to complete
The student selects a task.
OR
The student does visualize.
The screen remains the same.


Use Case Name: Create graph of connections between notes
## Summary
The system will create connections between notes using a graph algorithm.
## Actors
The system.
## Preconditions
There are at least one note to serve as a note.
## Triggers
Automatically triggered.

## Primary Sequence
1.The system checks the server for the existence of notes.
2.After confirming the existence the system will place the notes as nodes..
3.The system will create a bi-directional graph where the edges will serve both ways.

## Alternative sequence
There are no notes
The system does not do anything..

## Primary Postconditions
The system creates the graph
Now both the system and the student can easily navigate between notes and can be used to implement new features
OR
The system does not create a graph.
The system will wait until there is enough note(s).

Use case name: find text in files
##Summary
The student logged in the app can find a specific text in files.
##Actors
The student and the file.
##Pre condition
The student is logged in and has the file open.
##Trigger
The student clicks command + f.
##Primary sequence
The system prompts the student to enter letters.
The Student writes the word or letter they are looking for.
System checks if what the student entered is available in the file.
System highlights the word the student entered throughout the file.
Student checks all the highlighted text.
##Alternative sequence
The student entered text not available in the file.
System sends the student a message indicating that the text is not available in the file.
##Post condition
The student looks at the text highlighted by the system.
##Non functional requirements
The system highlights the text entered within 0.5 seconds.
The system tells the student to enter a different text.
##Functional requirements
The system can highlight the searched text.
The system can show many times the text entered is mentioned in the file.

Use case name: Change order of flash cards based on how often user got answer correct.
##Summary
The system shuffles the flash cards when a student gets a correct answer.
##Actors
The student and the flash cards.
##Pre condition
The student logged on.
##Trigger
Student picked the correct answer.
##Primary sequence
The student gets the correct answer.
The system shuffles the remaining flashcards.
The system finds the student another flashcard chosen at random.
##Alternative sequence
The student gets the incorrect answer.
System does not shuffle cards and tells the student to try again.
##Post condition
The student gets the correct answer and moves on to the next flashcard.
Or the student gets the incorrect answer and tries again.
##Non functional requirements 
The system takes 1 second to shuffle the cards.
##Functional requirements 
The system successfully changes the order of flashcards if the student gets the correct answer.
The system moves on to the next flashcard available.

Use case name: Use pomodoro timer
## Summary
The system helps the student with their time management by organizing a period of time in which the student is working and a period of time in which the student takes a break.
## Actors
The student and the pomodoro timer.
## Pre condition 
The student is logged in.
##Trigger
The student clicks on “use pomodoro timer” button.
## Primary sequence
The student activates the pomodoro timer by clicking the button.
The system tells the student to do a certain task for 25 minutes.
After 25 minutes the system makes a ringer noise for 5 seconds and tells the student to enter how far they got into the task and take a 5 minute break.
After a 5 minute break the system rings again notifying the student to get back to work for another 25 minutes.
After four 25 minute work periods the system tells the student to take a longer break (15-30 minutes).
The system repeats the cycle until the student turns off the pomodoro timer by clicking the “turn off pomodoro timer” button.
## Alternative sequence
The student accidentally exits the app.
The pomodoro timer pauses.
## Post condition 
The student uses the pomodoro timer to better manage their time and work more efficiently.
## functional requirements 
The system activates a ringer when the timer goes off.
The pomodoro timer has an option to pause and continue the timer.

Use case name: creating time blocks(using markdown)
##summary
Using markdown, the student can make time blocks to help organize their schedule.
##Actors
Student and markdown.
##pre condition
Student has logged in.
#Trigger
The student clicks a button at the top of the app to open a file. Once the file is opened the student can then access time blocks.
##primary sequence
The student open a file by clicking on the markdown button at the top of the page
In the file the student can enter < !-- Time Blocks -- >.
After that the student can enter ~~ science ~~ (or it could be any other subject or a specific project.
The student clicks enter.
The system will display a message, for example “from 3pm-5pm work on science.”
## Alternative sequence 
The student enters text the system can not read.
System displays a message “unvalid text entry.”
## post condition
The student has time blocks to help them study.
## non functional requirements
The system responds within 1 second.
## functional requirements
System displays a message. 

