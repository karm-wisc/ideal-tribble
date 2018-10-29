# X-Team 36 Food "Table"

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
When hosting an event, event holders usually need to prepare the food for all event attendees. However, the lack of communication with the attendees and the event holders/caterers will result in some food preferences not being fulfilled or met. It is also very hard for the preparation of the food. We want to design a program to fix it. First we let the attendees enter their first and last names and their food preferences (allergies, vegans, etc.). We will have serveral meal options available, and we will develop a method to match the attendees' inputted preferences to the meals that the caterers are providing. Then we will store their food choices in a hashtable, their first and last name would be the key and their food choices as the value. The event holder will then know how many each kind of food they need to prepare, while the attendees can have the food that fullfill their preferences. 

## Questions to answer for Exercise #2

1. Name: 

Food "Table"

2. Output:

The output data for our program will be the total number of event attendees having the same food preferences (E.g.: 25 people have dairy allergies, 36 people are vegetarian, etc.). Once this data is outputted and grouped by food preferences, the caterers can identify and match which groups of people will have which meal the carterers will be providing. 

3. Input: 

When creating the event, the input data for our program will include the name of each participant and their respective dietary restrictions. We will import the name of the of the person as a string, and the input of the dietary restriction will be from their selection they choose on the registration form. For example, name would be "Alex Smith" and selection 3 which would point to Vegan. You will be able to select multiple food restrictions too. During the event, the input data for the program will include just the name of each participant. For example, just the name "Alex Smith"

4. User Interface: 

Implement a simple graphic user interface that would preferably work on mobile devices. The UI will act as a registration form. The UI will have users click on the check box options corresponding to sets of questions. An initial text box will be used for the user to input their name.

5. Types List: Break your solution idea down into units that you think can be implemented with a single class.

HashTable.java - Contain our own implementation of a hash table.
Node.java - Contain information on individual attending event.
Main.java - Executes the entire program.
UserInterface.java - Contains code to display user interface.




## Edit and Submit this file and any figures referenced by this document.

