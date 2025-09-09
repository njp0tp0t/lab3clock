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

Q5. NumberDisplay hours = new NumberDisplay(24);
    hours.increment();
    When the value hits 24, it rolls over 0.
    
Q6. NumberDisplay minutes = new NumberDisplay(60);
    minutes.increment();
    When the value hits 60, it should roll over to 0 and increment should be called on the hours project.
    Eg: 11:59 -> 12:00
    When value = 0, increment hours by 1.

Q7. NumberDisplay display = new NumberDisplay(6);
    display.getValue()
    display.increment();
    
Q8. No, both calls to setValue did not result in a change to the stored value, because
    