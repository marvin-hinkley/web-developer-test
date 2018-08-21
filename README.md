## Fire Mountain Gems & Beads Web Developer Evaluation
**Introduction**

Hello, applicant. This project will evaluate your skill level in several different categories involved in the day-to-day life of a web developer at Fire Mountain. It should take you around 2-3 hours to complete. Please try to spend no more than 4 hours in total.

The goal of the project is to create a fully operational, web-based customer service ticketing application from scratch as best you can within the allotted time based upon the following acceptance criteria. Feel free to use whatever third-party libraries you think will assist in achieving this goal.

When the project is complete, or the time allotted for completion has expired, please create a pull request against the master branch to have your attempt evaluated. ***Good luck, applicant!***

Let's move on to some preparatory steps:

 1. Clone this repository.
 2. Create a new branch from the master branch with your first and last name included.
	 Example: jerry-smith-fmg-test
 3. Complete as much of the project to specification as you can within the time allotted.

**General Requirements**
 - The back-end of the website must be implemented in .NET using C#. The .NET version can be whatever you prefer from 4.5.2 to whatever the latest version, to include Core, is at the time of your evaluation.
 - The website must use the MVC or MVVM patterns
 - All work must be completed as a part of your named branch.
 - All features within the acceptance criteria must be included in the project.
 - At least two features within the list of optional features must be completed.
 - You must include statements to generate objects for whichever database in which you persist application data (tables, stored procedures, view, etc.).
 - While research before, during, or after the evaluation is encouraged - always keep learning! - please do not simply copy and paste StackOverflow answers. We all know what Jon Skeet's code looks like, and it deprives both you and Fire Mountain of valuable time and resources.

**Acceptance Criteria**
 1. Users must be able to view a list of tickets submitted in the past.
    1. List must include status of each ticket
    2. List must include notification of communications regarding each ticket
 2. Each ticket will have the following fields:
    1. ID
    2. Status
    3. Category [Networking, Software, Hardware, Facilities]
    4. Title
    5. Description
    6. Customer Service Representative
    7. Assigned Technician
 3. Each user has a separate list of tickets
 4. User must be able to submit new tickets
    1. All fields are user-populated with the exception of:
       1. ID
       2. Customer Service Representative
       3. Assigned Technician
 5. Tickets persist between user sessions
 6. All forms must use some kind of common sense validation of field content and prevent the user from submitting until the entire form is valid.