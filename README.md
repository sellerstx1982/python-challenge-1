# Kyle's Food Truck

My coding project uses Python to create a menu ordering application for a
for a fictional food truck. I completed this task when I was learning Python. 
I wanted to see how I can use dictionairies to navigate the food truck menu, 
select items, establish how many items, and calculate the total price of my 
order. 

## Throughout this experience I learned how to:

1) Assign variables
2) Format string literals
3) Use the `input` function
4) Use the Python String isdigit() Method
5) Include `for`, `while`, and nested loops



To begin the process, press the run button on any source code editor compatible
with Python. Once the code starts to run the customer is welcomed to a 
fictional food truck called Kyle's Food Truck, and asked which menu item 
category the customer would like to select from. A number between 1 and 4 is
required, otherwise the response is invalid. If the response is invalid, the
customer is asked if they would like to continue ordering. After continuing
the order and selecting a valid response for the menu category, the menu items
from the selected menu category are listed and a number correlates with each 
menu item. Once a menu item is chosen the program asks how many of the selected 
menu item the customer wants. The program stores the response before asking
if the customer would like to keep ordering. If yes is selected, the customer
is looped back to the beginning where they are asked to select a menu item
category. If no is selected, the customer's order is completed by thanking them
for their order, stating, "This is what we are preparing for you," before
showing them the list of items, with the quantity, and price.