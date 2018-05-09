# KWIC Techincal Summary

## What criteria did you use to decompose the first design?
* I broke different tasks into their own methods
* I used good names to keep it clear what the code did
* I made an outline before coding it up

## What criteria did you use to decompose the second design?
* I used the template to create classes for file in/out as well as managing the lines
* I kept concerns separate across different files
* I made many methods for things that might not have even been used

## Which design is more resilient to change? And why?
* The second design because it has a different class for the in/out as well as a different class for management of the lines
which allows it to change the storing data structure as well as how the lines are read in. This gives it the ability to change 
much easier.

## What would have to change in the first design/implementation if the file were changed out for a database?
* I would have to change the input and output methods to read in from a database as opposed to a file into the correct
arrayList object

## What would have to change in the second design/implementation if the file were changed out for a database?
* I would have to change/create a new input/output class that used a database instead of a file which would not 
be too difficult

## What would have to change in the first vs second design/implementation if we wanted to use a graphical user interface instead of the traditional console UI (System.out)?
* Not much would have to change, it would just have to add in a place to ask the user for the file type as well as file name
and then instead of outputting to the console I would make it output to the UI

## Identify another change that may happen in the future, and how does design 1 compare to design 2 when it comes to impact of the change?
* Another change that might happen is that you might want to switch the last word back to the front. If this happened design 2
already has methods to change the lines like that, design 1 would basically have to rewrite or add a new method for 
adding to the beginning instead of the end.

## Which design/implementation is easier to understand?
* I think design two is easier to understand because it is more seperate and has more details making it easy to see
how it gets from one point to anther

## Which design/implementation is better performing?
* I think they are both about the same because deep down they do they same sort of things they are just split up in 
different ways which makes number 2 easier to change

## How does the principle of information hiding relate to all of this?
* In design 2 the entire in/out is it's own class as well as line management. This allows for those to change later on which
hides their information from the regular class making it more hidden.