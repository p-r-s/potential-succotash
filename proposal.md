# X-Team 43 Digital Scheduling Assistant Proposal

See https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#code for tips on using *Markdown* tags to format __.md__ files

## Goal

Work as a team to create a project proposal for your X-team to complete together.
The project does not have to be extremely difficult,
but there must be work to do for each member of your team.
You may reference figures using "See figure 1".  
Be sure to submit corresponding image files, i.e. figure1.png (or figure1.jpg) for each figure.

## Grading: To earn full credit, your team's proposal must include:

* (md) documentation: [this file] describing purpose and use of your program

* Description of a program that has:

  ** a main Java program class in a file named Main.java
  
  ** a custom data structure designed and built by your team
  
  ** comprehensive testing of individual units
  
 Caution: You are not being asked to implement this program, at least not yet. 
 We just want your group to make a proposal or pitch for your program.
 
 Tip: Your custom data structure can be composed of or extensions of data structures that you have learned and used in previous programming assignments.  We're looking for decisions about how to build a high-level data structure that will likely have lower-level components.

## Problem Description

Briefly describe a problem that your team would like to solve.  
Describe at a high level a program that could solve that problem.

The problem we would like to solve is coming up with an efficient and effective way for a college student to manage their weekly schedule. We all agreed that having a digital software to manage everything from class schedules to exams and homework would be invaluable to someone struggling with time management. Physical planners can add weight to your backpack, lose pages or get damaged, and often online calendars do not allow you to track your assignment progress with ease. We propose a solution that includes the best of both worlds.

Our program will store user input to help organize weekly tasks for a high school or collge student. The user can input a class list (where each class is an object of type subject) and within each class can submit data regarding class schedule, test dates and homework due dates. The program will provide a text menu to interact with that includes things such as today's classes, tasks list, this week's exams and more. Students can also update tasks to "done" when they are completed and this will show up when the tasks list is printed. 

## Questions to answer for Exercise #2

1. Name: Give your project proposal a name (and edit the top line of this file)
 * Digital Scheduling Assistant


2. Output: Describe the output your program will produce.  Include and example format of the output produced.
 * The output produced by this program is a concatenation of all classes, tasks remaining, or exams on a given day.
 * After interacting with the text menu to input their data, the program will organize the information and present it in a     clear and organized way. 
 * Example output may look something like the following:
   * Tasks Completed: 1, Tasks Remaining: 3
   * Today's class schedule:
     English Lit: 8:00-8:50
     Spanish: 13:00-13:50
     Math: 14:30-15:20
   * Exams this week: 
     You have no exams this week.


3. Input: Describe the data that is needed to solve your problem. Include an example format of the input data. 
 * Start and end dates for classes, homework assignments, and exams
 * Input for markers that indicate an assignment or exam is either "to-do" or completed
 * Input that displays specified information, such as: class list, class schedule for specific day, to-do list, compeleted list
  * Example Input: 10/30/2018 __(enter)__ 11/2/2018 __(enter)__ 14:30 __(enter)__
    * Example input from a user for a homework assignment - this includes starting date, due date, and hourly time due


4. User Interface: Describe a user interface for your program.  Use text menus or a simple graphic user interface.



5. Types List: Name each interface or class and briefly describe its function or purpose.
* Date: Represents a date, containing members to hold the date, month, and year of a particular date.
* Time: Represents time in 24-hour format.
* Task: Represents a task the user would like to add to their schedule, including the date and time due, subject, and type of task.
* Subject: Represents the subject that the user would like to add a task for. 
* Schedule: An object of type Schedule contains all tasks that the user has added, along with their types, deadlines, and subjects.



## Edit and Submit this file and any figures referenced by this document.

