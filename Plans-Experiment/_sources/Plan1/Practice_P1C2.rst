=============================================
"Check If Empty" Plan - Practice #2
=============================================

Sometimes, we want to **determine if an input is empty before we do something with it**. 
When we want to achieve a goal of this type, we use the "Check if Empty" plan.

Please complete this practice problem before moving on. You may look at the example on the previous page.


    In this problem, your goal is to **determine if the uploaded song is empty before saving that song**.


.. parsonsprob:: PracticeP1C2_2
       :noindent:
       :adaptive:

       The code below is mixed up and contains extra blocks that are not needed.  Drag the needed code from the left to the right and put them in order with the correct indention so that the code would work correctly. 


       -----
       themesong = uploadSong()
       =====
       if length(themesong) == 0:
         error("No notes in song!")
       =====
           error("Too many notes in song!")
       =====
       else:
           save(themesong)
       =====
       inventory = error("Incorrect input") #distractor
       =====
       if length(song) >= 0: #distractor
       =====
       play(themesong) #distractor

