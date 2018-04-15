=====================
Practice Test
=====================






String - 1: Match Logic and Code
:::::::::::::::::::::::::::::::::::

Sum up the length of everyone's names.

.. code-block:: python

    names = getClassNames()
    sumLetters = 0

    for i in names:
      sumLetters += len(n):


    print(sumLetters)


.. parsonsprob:: sumallstringParsons

    Match the labels to the appropriate parts of the code.

    -----
    Collect input list
    =====
    Start sum with zero
    =====
    Go through all items in the list
    =====
    Add that value to the sum
    =====
    Show the sum
    =====
    Go through one element in the list #distractor
    =====
    Keep the old value #distractor
    =====
    If that element does not meet the criteria #distractor



String - 2: Fill in the Blank
:::::::::::::::::::::::::::::


Choose the correct choice to fill in the blank of the code:

.. code-block:: python

     names = (1)
     sumLetters = 0

     (2)
        sumLetters += len(n)


    print((3))




.. mchoice:: post1_1
    :correct: d
    :answer_a: get
    :answer_b: num > 0
    :answer_c: getClassHeights()
    :answer_d: getClassName()
    :answer_e: for n in names




.. mchoice:: post1_2
    :correct: b
    :answer_a: num <= 0
    :answer_b: for n in names
    :answer_c: if length(names) > 0
    :answer_d: if n in names
    :answer_e: num > 0




.. mchoice:: post1_3
    :correct: a
    :answer_a: sumLetters
    :answer_b: pickNotes()
    :answer_c: heights =
    :answer_d: num
    :answer_e: sumHeights













String - 3: Write Code
:::::::::::::::::::::::::


.. activecode:: replacementstringActivecode

   names = getClassNames()




   print(sumLetters)






.. Notes

Sum up the duration of all the notes.

Notes - 1: Match Logic and Code
::::::::::::::::::::::::::::::::::

.. code-block:: python

     notes = getNotes("happybirthday.midi")

     sumDuration = 0

     for i in notes:
        sumDuration += duration(n)


.. parsonsprob:: sumallnoteParsons

    Match the labels to the appropriate parts of the code.

   play(sumDuration)
   -----
   Collect input list
   =====
   Start sum with zero
   =====
   Go through all items in the list
   =====
   Add that value to the sum
   =====
   Show the sum
   =====
   Go through one element in the list #distractor
   =====
   Keep the old value #distractor
   =====
   If that element does not meet the criteria #distractor





Notes - 2: Fill in the Blank
:::::::::::::::::::::::::::::


Choose the correct choice to fill in the blank of the code:

Sum up the duration of all the notes.


.. code-block:: python

     notes = getNotes("happybirthday.midi")

     (1)

     for i in notes:
        sumDuration += (2)

     (3)


.. mchoice:: post1_1
    :correct: a
    :answer_a: sumDuration = 0
    :answer_b: number = getNumber()
    :answer_c: duration(n)
    :answer_d: sumDuration = notes
    :answer_e: print(notes)







.. mchoice:: post1_2
    :correct: b
    :answer_a: volumne(n)
    :answer_b: duration(n)
    :answer_c: Finds the tallest height
    :answer_d: names
    :answer_e: sumDuration





.. mchoice:: post1_3
    :correct: d
    :answer_a: num <= 0
    :answer_b: print(sumNames)
    :answer_c: sumDuration -=
    :answer_d: print(sumDuration)
    :answer_e: "happybirthday.midi"













Notes - 3: Write Code
:::::::::::::::::::::::::


.. activecode:: sumallnoteActivecode

   notes = getNotes("happybirthday.midi")






   print(sumDuration)






.. Picture
Sum up the bright values of pixels.

Picture - 1: Match Logic and Code
:::::::::::::::::::::::::::::::::::::

.. code-block:: python

     pixels = getPixels("sunset.jpg")

     for p in pixels:
        if luminance(p) > 200:
           setBlue(p,255)

     show(makePic(pixels), dimensions("sunset.jpg"))



.. parsonsprob:: sumallpixelParsons

    Match the labels to the appropriate parts of the code.

   -----
   Collect input list
   =====
   Start sum with zero
   =====
   Go through all items in the list
   =====
   Add that value to the sum
   =====
   Show the sum
   =====
   Go through one element in the list #distractor
   =====
   Keep the old value #distractor
   =====
   If that element does not meet the criteria #distractor




Picture - 2: Fill in the Blank
:::::::::::::::::::::::::::::


Choose the correct choice to fill in the blank of the code:

.. code-block:: python

    (1) getPixels("beach.jpg")

    sumLuminance = 0

    (2)
      sumLuminance (3) luminance(p)

    print(sumLuminance)



.. mchoice:: post1_1
    :correct: c
    :answer_a: songs =
    :answer_b: else:
    :answer_c: pixels =
    :answer_d: integer =
    :answer_e: print(sumHeights)






.. mchoice:: post1_2
    :correct: c
    :answer_a: num <= 0
    :answer_b: num > 0
    :answer_c: for p in pixels:
    :answer_d: -=
    :answer_e: if:




.. mchoice:: post1_3
    :correct: c
    :answer_a: <
    :answer_b: >
    :answer_c: +=
    :answer_d: -=
    :answer_e: ==









Picture - 3: Write Code
:::::::::::::::::::::::::


.. activecode:: sumallpixelActivecode

   pixels = getPixels("sunset.jpg")





   print(sumLuminance)




