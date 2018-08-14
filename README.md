## Fire Mountain Gems & Beads Web Developer Evaluation
**Introduction**

Hello, applicant. This project will evaluate your skill level in several different categories involved in the day-to-day life of a web developer at Fire Mountain.

The goal of the project is to create a fully operational, web-based customer service ticketing application from scratch as best you can within the allotted time based upon the following acceptance criteria. Feel free to use whatever third-party libraries you think will assist in achieving this goal.

When the project is complete, or the time allotted for completion has expired, please create a pull request against the master branch to have your attempt evaluated. ***Good luck, applicant!***

Let's move on to some preparatory steps:

 1. Clone this repository.
 2. Create a new branch from the master branch with your first and last name included.
	 Example: jerry-smith-fmg-test
 3. Complete as much of the project to specification as you can within the time allotted.

**General Requirements**
 - The back-end of the website must be implemented in .NET using C#. The .NET version can be whatever you prefer from 4.5.2 to whatever the latest version, to include Core, is at the time of your evaluation.
 - With the exception of extra credit features, the website must use the MVC or MVVM patterns
 - All work must be completed as a part of your named branch.
 - All features within the acceptance criteria must be included in the project.
 - At least two features within the list of optional features must be completed.
 - Feel free to attempt any additional features from the list of extra credit features.
 - You must include statements to generate objects for whichever database in which you persist application data (tables, stored procedures, view, etc.).
 - While research before, during, or after the evaluation is encouraged - always keep learning! - please do not simply copy and paste StackOverflow answers. We all know what Jon Skeet's code looks like, and it deprives both you and Fire Mountain of valuable time and resources.

**Acceptance Criteria**
 1. Users must be able to view a list of tickets submitted in the past.
    1. List must include status of each ticket
    2. List must include indication that a ticket has been updated (ex. badge or field)
 2. Each ticket will have the following fields:
    1. ID
    2. Status - restricted to a list of: New, Assigned, & Closed
    3. Category - restricted to a list of: Networking, Software, Hardware, & Facilities
    4. Title
    5. Description
    6. Customer Service Representative
    7. Assigned Technician
 3. Each user has a separate list of tickets
 4. User must be able to submit new tickets
    1. All fields are user-populated with the exception of the following which are, other than Status, initially blank:
       1. ID
       2. Status: Populated with 'New'
       3. Customer Service Representative
       4. Assigned Technician
    2. Tickets persist between user sessions
 5. All forms must use some kind of common sense validation of field content and prevent the user from submitting until the entire form is valid.

**Optional Features**

*Please pick two of the following:*
 - Each ticket, when viewing status, contains a persistent collection of comments. These comments come from the assigned technician, the customer service representative, and the submitting user.
 - A user's list of tickets is filterable by any field except Description.
 - The application uses authentication to secure its contents.
 - The application has a second user role of Customer Service representative. These representatives must be able to view, edit, and respond to any tickets assigned to them. The representatives must also have the ability to assign tickets to technicians.

**Extra Credit**

 *Time to show off a little:*
 - Comments are transferred between client and server in real-time.
 - Application is completely responsive and displays nicely on mobile devices.
 - Some part, or all, of the application is actually a single-page application (Angular 1/2, Vue.js, Ember, etc.)
 - The application's back-end exposes its data via a REST API for consumption by other clients.
 - The application's sytling is defined using a CSS pre-processor such as SASS or LESS.