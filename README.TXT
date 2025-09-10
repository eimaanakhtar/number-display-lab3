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
Q9: When i set value to 10, the result getValue() was 0. This is because the rolllover limit is 10, so the numbers only go to 0-9.
Q10: The error message states that getValue() cannot be applied to the class NumberDisplay. This is because getValue() is an instance method so we have to use an object name like "digit.getValue()" instead of the class name.
Q11: The error message that shows when you type "display.setValue(int 5);" says 'Error class expected'. When calling a method, we only write the value (5). The correct call is "display.setValue(5);"
Q12: I changed the < operator to <= in setValue. Now the maximum value can be set correctly.
Q13: If >= is changed to >, the value of 0 will no longer set the field.
Q14: If && is replaced by ||, invalid values like -1 or values which are equal to or greater than the limit could incorrectly set the field.
Q15: True expressions: !false, (34!= 33) && !false.
     False expressions:  !(4 < 5), (2 > 2) || ((4 == 4) && (1 < 0)), (2 > 2) && (4 == 4) && (1 < 0).
Q16: (a && b) || (!a && !b) - true when "a" and "b" are both true or both false.
Q17: (a && b) || (!a && !b) - true when exactly one of "a" or "b" is true.
Q18: getDisplayValue works only for 2-digit numbers. For a limit like 1000, it still only returns only 2 digits.
Q19: There is no difference. Both return value + ""and"" + value conveert the integer into a string.
Q20:
    - 9 + 3 + "cat" -> "12cat"
    - "cat" + 3 + 9 -> "cat39"
This happens because in the first case, the numbers are added before turning into a string. In the second one, the string causes everything after to be treated as text.
