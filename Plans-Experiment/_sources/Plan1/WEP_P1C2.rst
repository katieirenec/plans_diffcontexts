=============================================
"Check If Empty" Plan - Example & practice #2
=============================================

Sometimes, we want to **determine if an input is empty before we do something with it**. 
When we want to achieve a goal of this type, we use the "Check if Empty" plan.

Please view the example and complete the practice problem before moving on.

-----------------------
Example & practice #2
-----------------------


.. reveal:: revealExampleP1C2_2
    :showtitle: Click here to view an example
    :hidetitle: Hide example

    Here's an example. 

    I am playing a song. A song is made up of notes.

    My goal is to **determine if the song chosen by the user is empty before saving that song**. 

    Here is the code I would write to achieve that goal:

    .. image:: ../../_static/WorkedExampleP1C2_2.png


    Watch this video to see how the code achieves the goal:

    .. youtube:: AcJRzmMQOl8
        :height: 315
        :width: 560
        :align: left



.. reveal:: revealPracticeP1C2_2
    :showtitle: Click here to practice
    :hidetitle: Hide practice

    Now that you've seen an example, you will do some practice.

    In the practice problem below, your goal is to **determine if the uploaded song is empty before saving that song**.


    .. parsonsprob:: PracticeP1C2_2

       The code below is mixed up and contains extra blocks that are not needed.  Drag the needed code from the left to the right and put them in order with the correct indention so that the code would work correctly. 


       -----
       themesong = uploadSong()
       =====
       if length(themesong) == 0:
         error(“No notes in song!”)
       =====
           error(“Too many notes in song!”)
       =====
       else:
           save(themesong)
       =====
       inventory = error("Incorrect input") #distractor
       =====
       if length(song) >= 0: #distractor
       =====
       play(themesong) #distractor

          

