=============================================
"Check If Empty" Plan - Example & practice #1
=============================================

Sometimes, we want to **determine if an input is empty before we do something with it**. 
When we want to achieve a goal of this type, we use the "Check if Empty" plan.

Please view the example and complete the practice problem before moving on.

-----------------------
Example & practice #1
-----------------------


.. reveal:: revealExampleP1C1_1
    :showtitle: Click here to view an example
    :hidetitle: Hide example

    Here's an example. 

    I am creating an inventory for my store. An inventory is made up of products.

    My goal is to *determine if the inventory that was scanned is empty before updating*. 

    Here is the code I would write to achieve that goal:

    .. image:: ../../_static/WorkedExampleP1C1_1.jpg


    Watch this video to see how the code achieves the goal

    .. youtube:: VZcsqP4d0VY
        :height: 315
        :width: 560
        :align: left



.. reveal:: revealPracticeP1C1_1
    :showtitle: Click here to practice
    :hidetitle: Hide practice

    Now that you've seen an example, you will do some practice.

    In the practice problem below, your goal is to **determine if the inventory entered by the user is empty before updating**.


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
