# Proposal

## What will (likely) be the title of your project?

Run Data to CSV Converter for Slay the Spire 2

## In just a sentence or two, summarize your project. (E.g., "A website that lets you buy and sell stocks.")

Slay the Spire 2 is a game that stores data in the form of multiple JSON files. I would like to write a python program that gets the data from the JSON files and combines the data into one CSV file.

## In a paragraph or more, detail your project. What will your software do? What features will it have? How will it be executed?

Slay the Spire 2 is a rogue-like game, a genre of game which consists of "runs" of the game, where failure sends you back to the beginning. The game stores data from each of these runs in a separate JSON file in a file in the game's directory. I would like to write a python program which accesses this file and iterates through each of the JSON files to gather specific data and combine it into a singular CSV file so it can be easily analyzed in software I am familiar with, such as R and Tableau. To achieve this, I will likely need for or while loops to iterate through the saves folder, and file reading and writing along with specific indexing from each of the JSON files. Beyond this, some features that could be included are basic analytics based on the data from the files.

## If planning to combine 1051's final project with another course's final project, with which other course? And which aspect(s) of your proposed project would relate to 1051, and which aspect(s) would relate to the other course?

NA

## If planning to collaborate with 1 or 2 classmates for the final project, list their names, email addresses, and the names of their assigned TAs below.

NA

## In the world of software, most everything takes longer to implement than you expect. And so it's not uncommon to accomplish less in a fixed amount of time than you hope.

### In a sentence (or list of features), define a GOOD outcome for your final project. I.e., what WILL you accomplish no matter what?

I will, at a bare minimum, accomplish a program that gathers data from one JSON file at a time.

### In a sentence (or list of features), define a BETTER outcome for your final project. I.e., what do you THINK you can accomplish before the final project's deadline?

If I can get the program to read one JSON file, I think I can get the program to iterate through all files in the saves folder.

### In a sentence (or list of features), define a BEST outcome for your final project. I.e., what do you HOPE to accomplish before the final project's deadline?

I hope that I will be able to include some basic analytics based on the data in the CSV file by incorporating them into part of the python code.

## In a paragraph or more, outline your next steps. What new skills will you need to acquire? What topics will you need to research? If working with one of two classmates, who will do what?

I will likely need to learn how to iterate through multiple files in a folder. I should also do some research on how exactly Slay the Spire 2 saves its data, as the folder contains backups, and I would like to make sure I don't screw up the data contained in the files while trying to read it and write it onto another file. As for an outline for how I will go about creating this program, I will likely need to go through one JSON file and find what data I want to take from it, then write a program to index that data and write it to a separate file. Then I will need to use a for or while loop to iterate through each JSON file in the saves folder. Finally, once I have the basic program working, I can add some basic data analytics to the CSV file to make it easier to start working on.
