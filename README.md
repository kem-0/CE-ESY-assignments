CE-ESY-assignments 

Assignment 1 : Circular Buffer

This is my code for the first assignment in the CE-ESY course & i built a circular buffer using C to handle character data  

What is in this repository:

    homework.c (the source code)  

    Screenshot_20260429_105533.png (terminal output screenshot)  

How I solved it:
I used a struct to organize the buffer with head and tail pointers and a counter for the items and i used the modulo operator (%) to make the indices wrap around which is the core idea of a circular buffer 

Testing:
I tested the buffer with a size of 10 to see how it handles different cases:  

    Overflow: I entered a long name and the program correctly showed an error when it ran out of space

    Success: I tried a shorter name and it printed the whole thing perfectly 

You can check the results in the screenshot i uploaded
