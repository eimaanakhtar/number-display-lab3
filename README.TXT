Project: number-display
Authors: Michael Kölling and David J. Barnes

This project is part of the material for the book

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling

It is discussed in chapter 3.

To use this project, create an instance of class NumberDisplay. Then inspect this 
instance and leave the inspector window open. With the inspector window open, 
call the object's methods, such as increment and setValue.

Part 1 - number class.
Q1: Class diagrams show blueprints of classes, object diagrams show actual objects at a moment in time.
Q2: This only changes when you change the code, like adding or removing feilds or methods.
Q3: Objects diagrams can change when objects are created, deleted, or when references between objects change during the running program.
Q4: private Instructor tutor;
Q5: Creating NumberDisplay "hours" with a limit of 24. When calling increment() a few times, this increases the value from 0 -> 1 or depending on the times you click increment().
Q6: I have sucessfully created a NumberDisplay object, named it "minutes" and setting its value to 60. When i call getValue(), it showed me the current value (for example 1). The terminal window is blank since there wasnt any System.out.println() which is expected.
Q7: Created a NumberDisplay object with a limit of 6. In the Code Pad below i added "NumberDisplay display = new NumberDisplay(6);" along with "display.getValue()" and "display.increment();". It shows the get value display at "0 (int)", however once you call increment() it increases by 1 each time.
Q8: When calling a value with the setValue less than the limit 3, it succesdfully updates the store value. Wehn calling steValue with a greater number then its limite example 10, it does not change the stored value because it exceeds the limit.
Q9: 
