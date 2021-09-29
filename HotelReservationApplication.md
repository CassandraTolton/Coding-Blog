# Hotel Reservation Application
## Languages: C#, .NET framework, Window Forms

### Goals:
1. Create an Application that can read in files that keeps track of users, rooms and occupancies
2. Practice and Advance C# knowledge by incorperating advanced C# methods and classes
3. Create a presentable project that can be added to my portfolio

### To-Do:
- [ ] Create the main layout of the Form
- [ ] Creating the functionality of the buttons on the main page
- [ ] Read in the files needed for the data of the rooms, customers and occupations
- [ ] create the classes needed for each
- [ ] display all data on the main page of the form
- [ ] create seperate forms for adding and removing customers and changing rooms occupancy
- [ ] create excpetion handling for all user input to assure quality

#### **Day 1**: September 26, 2021
Progress: 
I created a sketch of the basic layout and then created a more detail wireframe containing everything that i need and how i wanted the project to function. i then created a new project in C# windows form and created the inital form, the buttons, menu strip and listbox. i created functions for every event that i will need and created the basic functionality for displaying clients and rooms.

#### **Day 2**: September 27, 2021
Progress: 
i expanded on linking all the files that will be needed in order to keep track of client data, rooms and occupancies. im still trying to figure out how im going to seperate the different types of rooms but im thinking about created an extra variable (dont know if ill make it a string or bool yet) so when the time comes i can be ready to sort through them.
i also switched out the list box for a grid view, as i wanted headers and rows that can be sorted with needing extra buttons, however because i am not using a SQL database i had to do additional research on how to add data and clear data from the table. i got the rooms to be properly displayed (i still need to add all of them, as of right now only one room is added for testing purposes). i also had the files read in and added the data extracted into their respective arrays (for the rooms i am using a dictionary, for the clients im using a string array).
