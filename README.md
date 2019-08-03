# gs
Revised Print Divider for assisting when coding R projects in Jupyter.

Oftentimes when coding in Jupyter, it's easy to lose track of which line of code printed what output to the screen.

It can be hard to distinguish where the start  and end of the printed code occurs.

This simple little App is a function that prints  XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX across the screen when the function is called.

The function call is made to be easy, gs() , is the function call.  An arguement is required to be passed with the function call.

The function call arguement cannot be empty.  The three types of call arguements follow:

1) integer arguement,  gs(3)

Results in the following output:

XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX

[3]


2) character arguement, gs("This print section is from str(df) " )

Results in the following output:

XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX

[This print section is from str(df)]


3) function arguement, gs(dim(df$varName) 

Results in the following output:

XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX

[10 4]  *


* Note: when passing a function as the arguemnt, the function will be executed. The function result will be printed as shown.
