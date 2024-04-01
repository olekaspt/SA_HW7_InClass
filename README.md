# SA_HW7_InClass

## Read through the entire assignment and generate your estimate for your estimation assignment.  It is important to read through all steps first to understand the end state desired.  

This assignment is revisit C4 diagrams as well investigating the MVC architectural pattern.

We are working on a Email program similiar to outlook.  It will be able to work purely from the cloud (website) as well as a cloud connected desktop application.

Keep in mind the KISS principle, keep it simple silly :)   You should not need much many blocks in your diagrams.  If you have questions how this shoudl work, write it down as assumption.  That is don't ask me if this have X.  Write down your assumption about X, and proceed with your diagram.

## Web site
Make a C4 diagram, C1 and C2.  Which the C2 focusing on the component of the web page, and use the MVC, and use the MVC pattern.

## Cloud Connected Desktop Appplication
Make a C4 diagram, C1 and C2.  Which the C2 focusing on the component of the desktop application, and use the MVC pattern.

## Data access object
In lecture I talked about Data Access Object, and some of the concerns with about representing data.  

It can be argued the View\Controller can be thought of a Data Access Object.  And the emails in the model are the actual data.  What are requirements for the this product offering we should consider.  Think about performance issues with both the web and desktop application.  Also what about disk space usage \ memory useage.

## Entity Component System
I don't think it would make sense to this in practice, but for intersting thought experiment.  But make a diagram similar to https://en.wikipedia.org/wiki/Entity_component_system#/media/File:ECS_Simple_Layout.svg

If we we decided to make an "Office" suite, and were going to store the the digital items in in a ECS.

1) If we have emails, which can have graphs and spreadsheets.
2) If we workbooks, which can have graphs and spreadsheets
3) If we slide decks, which can contain graphs, spreadsheets, slide text
4) If we docs, which can have doc text, graphs, spreadsheets

And we will have a way for the user to make querries for individual elements.  For example, show me all graphs I have authored.

Show we what the ECS might look like with some data (reference the picture link above, or the slide deck).


PDF Report:  
1) List your assumptions used in the diagrams
2) Your C4 diagrams
3) Discussion about Data Access object paradigm issues
4) ECS diagram

## Participation Rubric
PDF:
The usual rubric of your partners particpation.

## Deliverable \ Rubric

20% Readability of code and Report
20 % Assumptions for diagrams
20 % C4 Diagrams (just C1 and C2 for both, so 4 diagrams)
20 % Discussion of Data Access Object paradigm
20 % ECS Diagram


Submission
1) PDF with desired information specified above.
