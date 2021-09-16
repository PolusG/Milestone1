# Milestone1
team Github repository: https://github.com/lianh9/Milestone1.git

Team member names and Github users :

Lian Huang, lianh9

Wisely Chan, wiselyc


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

