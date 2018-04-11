=====================
Sum All
=====================



..String
Replace all the names that start with J with the name "Jimmy".

Section 1: Parsons Problem
::::::::::::::::::::::::::::


Parsons Problem
----------------

.. parsonsprob:: replacementstringParsons

    Match the labels to the appropriate parts of the code.

    .. code-block:: python
        names = getClassNames()
        sumLetters = 0

       for i in names:
          sumLetters += len(n):


       print(sumLetters)

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



Section 2: Fill in the Blank
:::::::::::::::::::::::::::::


Choose the correct choice to fill in the blank of the code:


.. mchoice:: post1_1
    :correct: d
    :answer_a: get
    :answer_b: num > 0
    :answer_c: getClassHeights()
    :answer_d: getClassName()
    :answer_e: for n in names


        .. code-block:: python

           names = (1)
           sumLetters = 0

           (2)
              sumLetters += len(n)


          print((3))



.. mchoice:: post1_2
    :correct: b
    :answer_a: num <= 0
    :answer_b: for n in names
    :answer_c: if length(names) > 0
    :answer_d: Adds up all heights greater than 30
    :answer_e: num > 0


        .. code-block:: python

           names = (1)
           sumLetters = 0

           (2)
              sumLetters += len(n)


          print((3))



.. mchoice:: post1_3
    :correct: a
    :answer_a: sumLetters
    :answer_b: pickNotes()
    :answer_c: heights =
    :answer_d: num
    :answer_e: sumHeights


        .. code-block:: python

           names = (1)
           sumLetters = 0

           (2)
              sumLetters += len(n)


          print((3))











Section 3: Write Code
:::::::::::::::::::::::::

ActiveCode
----------

.. activecode:: replacementstringActivecode

   :coach:
   :caption: This is a caption

   names = getClassNames()




   print(names)



.. Notes


Replace all long notes with a shorter note.

Section 1: Parsons Problem
::::::::::::::::::::::::::::


Parsons Problem
----------------

.. parsonsprob:: replacementnoteParsons

    Match the labels to the appropriate parts of the code.

   notes = getNotes("happybirthday.midi")
   sumDuration = 0

   for i in notes:
      sumDuration += duration(n)

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





Section 2: Fill in the Blank
:::::::::::::::::::::::::::::


Choose the correct choice to fill in the blank of the code:

Sum up the duration of all the notes.



.. mchoice:: post1_1
    :correct: a
    :answer_a: sumDuration = 0
    :answer_b: number = getNumber()
    :answer_c: duration(n)
    :answer_d: sumDuration = notes
    :answer_e: print(notes)



        .. code-block:: python

           notes = getNotes("happybirthday.midi")

           (1)

           for i in notes:
              sumDuration += (2)

           (3)



.. mchoice:: post1_2
    :correct: b
    :answer_a: volumne(n)
    :answer_b: duration(n)
    :answer_c: Finds the tallest height
    :answer_d: names
    :answer_e: sumDuration


        .. code-block:: python

           notes = getNotes("happybirthday.midi")

           (1)

           for i in notes:
              sumDuration += (2)

           (3)



.. mchoice:: post1_3
    :correct: d
    :answer_a: num <= 0
    :answer_b: print(sumNames)
    :answer_c: sumDuration -=
    :answer_d: print(sumDuration)
    :answer_e: "happybirthday.midi"


        .. code-block:: python

           notes = getNotes("happybirthday.midi")

           (1)

           for i in notes:
              sumDuration += (2)

           (3)











Section 3: Write Code
:::::::::::::::::::::::::

ActiveCode
----------

.. activecode:: replacementnoteActivecode

   :coach:
   :caption: This is a caption

   notes = getNotes("vodel.midi")






   print(makeSong(notes))




.. Picture


Replace all very bright pixels with blue pixels.

Section 1: Parsons Problem
::::::::::::::::::::::::::::


Parsons Problem
----------------

.. parsonsprob:: replacementpixelParsons

    Match the labels to the appropriate parts of the code.

   pixels = getPixels("sunset.jpg")

   for p in pixels:
      if luminance(p) > 200:
         setBlue(p,255)

   show(makePic(pixels), dimensions("sunset.jpg"))
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




Section 2: Fill in the Blank
:::::::::::::::::::::::::::::


Choose the correct choice to fill in the blank of the code:



.. mchoice:: post1_1
    :correct: c
    :answer_a: songs =
    :answer_b: else:
    :answer_c: pixels =
    :answer_d: integer =
    :answer_e: print(sumHeights)


        .. code-block:: python

            (1) getPixels("beach.jpg")

            sumLuminance = 0

            (2)
              sumLuminance (3) luminance(p)

            print(sumLuminance)



.. mchoice:: post1_2
    :correct: c
    :answer_a: num <= 0
    :answer_b: num > 0
    :answer_c: for p in pixels:
    :answer_d: -=
    :answer_e: if:


        .. code-block:: python

            (1) getPixels("beach.jpg")

            sumLuminance = 0

            (2)
              sumLuminance (3) luminance(p)

            print(sumLuminance)



.. mchoice:: post1_3
    :correct: c
    :answer_a: <
    :answer_b: >
    :answer_c: +=
    :answer_d: -=
    :answer_e: ==


        .. code-block:: python

            (1) getPixels("beach.jpg")

            sumLuminance = 0

            (2)
              sumLuminance (3) luminance(p)

            print(sumLuminance)











Section 3: Write Code
:::::::::::::::::::::::::

ActiveCode
----------

.. activecode:: replacementpixelActivecode

   :coach:
   :caption: This is a caption

   pixels = getPixels("sunset.jpg")





   show(makePic(pixels), dimensions("sunset.jpg"))




