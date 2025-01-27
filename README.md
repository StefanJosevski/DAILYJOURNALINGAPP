# DAILYJOURNALINGAPP
1.)PROJECT NAME: Daily journaling app 
Team name: Solo independent 
Team Members: Stefan Josevski 


2.) I am building a user-friendly Daily Journal App that allows individuals to record 
thier daily thoughts, experiences, and goals. It will contain features such as journaling, 
categorization of entries, reminders, and to reflect on past entries. 

3.)I want to build this because jouranling has proven mental health benefits, such as 
reducing stress, boosting memory, and making people more self aware. It will make journaling 
a habit while providing digital space and secure reflections. 


4.) What wil it be used for? 
Keeping track of daily events and emotions.
Enhancing mindfulness and productivity.
Setting and tracking personal goals. 
Reflecting on past entries to observe personal growth. 

5.)How it will be used 
Users will log in and reigster for the app 
Create, edit, and delete journal entries. 
Categorize entries with tags ("work," "gradtitude," "travel") 
Set reminders to journal regularly. 
Search for and review entries using a calender or keyword search. 

6.)UML CLASSES that I will use 
Classes/Interfaces and Fields/Methods

User

Fields: userID, username, password, email
Methods: register(), login(), resetPassword()
JournalEntry

Fields: entryID, title, content, dateCreated, tags
Methods: createEntry(), editEntry(), deleteEntry(), searchEntries()
Tag

Fields: tagID, name
Methods: addTag(), deleteTag(), listTags()
Reminder

Fields: reminderID, userID, reminderDate, message
Methods: setReminder(), editReminder(), deleteReminder()
ExportManager

Fields: exportType (e.g., PDF, Word)
Methods: exportToPDF(), exportToWord()

7.) Planning: I will first gather everything like my notes, software, and the scope 
Next I would design the database and bring in core features ( user interfacxe and journal entry operations) 
To continue I would develop additional features like tagging, reminders, and exporting functionality. 
Test the app, fix bugs, and deploy. 
