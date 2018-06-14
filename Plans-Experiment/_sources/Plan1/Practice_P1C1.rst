=============================================
"Check If Empty" Plan - Practice #1
=============================================

Sometimes, we want to **determine if an input is empty before we do something with it**. 
When we want to achieve a goal of this type, we use the "Check if Empty" plan.

Please complete this practice problem before moving on. You may look at the example on the previous page.


    In this problem, your goal is to **determine if the inventory entered by the user is empty before updating**.


.. parsonsprob:: PracticeP1C1_1

       The code below is mixed up and contains extra blocks that are not needed.  Drag the needed code from the left to the right and put them in order with the correct indention so that the code would work correctly. 


       -----
       inventory = enterInventory()
       =====
       if length(inventory) == 0:
       =====
           error(“No products in this inventory!”)
       =====
       else:
           updateInventory(inventory)
       =====
       inventory = error("Incorrect input") #distractor
       =====
       if length(inventory) >= 1: #distractor
       =====
       print("Enter next item") #distractor
