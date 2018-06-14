=============================================
"Check If Empty" Plan - Example & practice #3
=============================================

Sometimes, we want to **determine if an input is empty before we do something with it**. 
When we want to achieve a goal of this type, we use the "Check if Empty" plan.

Please view the example and complete the practice problem before moving on.

-----------------------
Example & practice #3
-----------------------


.. reveal:: revealExampleP1C3_3
    :showtitle: Click here to view an example
    :hidetitle: Hide example

    Here's an example. 

    I am saving a picture. A picture is made up of pixels.

    My goal is to **determine if the screenshot is empty before saving the screenshot**. 

    Here is the code I would write to achieve that goal:

    .. image:: ../../_static/WorkedExampleP1C3_3.png


    Watch this video to see how the code achieves the goal:

    .. youtube:: aN28V3bedxE
        :height: 315
        :width: 560
        :align: left



.. reveal:: revealPracticeP1C3_3
    :showtitle: Click here to practice
    :hidetitle: Hide practice

    Now that you've seen an example, you will do some practice.

    In the practice problem below, your goal is to **determine if the profile picture from the webcam is empty before displaying the picture**.


    .. parsonsprob:: PracticeP1C3_3

       The code below is mixed up and contains extra blocks that are not needed.  Drag the needed code from the left to the right and put them in order with the correct indention so that the code would work correctly. 

       -----
       profile_picture = fromWebcam()
       =====
       if length(profile_picture) == 0:
       =====
           error(“Picture is empty!”)
       =====
       else:
       =====
           display(profile_picture)
       =====
       picture = pickPicture() #distractor
       =====
       if length(picture) >= 1: #distractor
       =====
       print("Webcam isn't working") #distractor

          

