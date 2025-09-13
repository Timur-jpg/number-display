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

Answers:

Part 1

5. NumberDisplay hours = new NumberDisplay(24);
   hours.increment();

6. NumberDisplay minutes = new NumberDisplay(60);
   minutes.increment();
   I should look at the terminal window to see if the minutes are set back to 0

8. The greater value stayed the same although the lower value changed.   

9. I think the answer will be zero.

10. Error: non-static method getValue() cannot be referenced from a static context
    
11. Error: '.class' expected
    To correct the error, I only needed to delete the type "int" 

12. The reason for the difference is that with "<=" the value equal to the limit is accepted while with "<" the value equal to the limit is rejected because it isn't less than the limit.

13. 0 is the only valid parameter value.

14. Some of the invalid parameter values that would now be able to set the field are negative numbers and numbers greater than or equal to the limit.

15. The expressions "! false" and "(34 != 33) && ! false" return true

16. The expression "a == b" evaluates to true when a and b are either both
    true or both false.
    
17. The expression "a ^ b" evaluates to true when only one of a and b is
    true, and that is false if a and b are both false or both true.
    



    