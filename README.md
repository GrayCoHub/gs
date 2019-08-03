# gs()

The revised Print-Divider is useful for assisting when coding R projects in Jupyter.

Oftentimes when coding in Jupyter, it's easy to lose-track of which lines of code are outputed to the sreeen.  It can be hard to

distinguish where the printed output from one line of code starts and printed output from another line of code ends.  


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


* Note: when passing a function as the arguement, the function will be executed and the function result will be printed as shown.
