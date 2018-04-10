=====================
Guarded Replacement
=====================


Replace all short heights with 10. A short height is less than 10.


.. timed:: posttest2-parsons_timed
    :timelimit: 5
    :nofeedback:


    Section 1: Parsons Problem
    ::::::::::::::::::::::::::::


    Parsons Problem
    ----------------

    .. parsonsprob:: replacementnumberParsons

        Match the labels to the appropriate parts of the code.

        heights = measureHeights()

        for i in range(len(heights)):
          if heights[i] < 10:
             heights[i]=10

       print(heights)

       -----
       Collect input list
       =====
       Go through all elements in the list
       =====
       If that element meets the criteria
       =====
       Replace it with a new value
       =====
       Show the changed list
       =====
       Go through one element in the list #distractor
       =====
       Keep the old value #distractor
       =====
       If that element does not meet the criteria #distractor

