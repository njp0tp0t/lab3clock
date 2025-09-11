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

Q9. Since the rollover limit is 10 and the setValue is 10, the getValue will return 0.

Q10. Error: non-static method getValue() cannot be referenced from a static context

Q11. Error: '.class' expected
     Correct way: display.setValue(5);
     There was int before 5, thats why there was an error.

Q12. < means that the maximum valid is one less than the limit.
     <= means that the limit itself is valid too.
     
Q13. 0

Q14. Any negative number or any number above the limit.

Q15. ! (4 < 5) and (34 != 33) && ! false

Q16. (a && b) || (!a && !b)

Q17. (a && !b) || (!a && b)

Q18. The getDisplayValue method returned a three-digit String.

Q19. Yes there is a difference.
    Ex: if written with the original return "" + value;--> "6" + 7 = 67
        if written with return value + ""; --> 7 + "6" = 76
        
Q20. 9 + 3 + "cat" = 12cat
     "cat" + 3 + 9 = cat39
     
Q21. 
