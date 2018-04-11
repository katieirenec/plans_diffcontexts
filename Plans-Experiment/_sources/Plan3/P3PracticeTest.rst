=====================
Guarded Replacement
=====================


Replace all the names that start with J with the name “Jimmy”.


Section 1: Parsons Problem
::::::::::::::::::::::::::::


Parsons Problem
----------------

.. parsonsprob:: replacementstringParsons

    Match the labels to the appropriate parts of the code.

   .. code-block:: python

       names = getClassNames()

       for i in range(len(names)):
         if names[i].startwith("j")
            names[i] = "Jimmy"

       print(names)

     -----
     Collect input list
     =====
     Go through all elements in the list
     =====
     If that element meets the criteria
     =====
     Replace it with a new value
     =====
     Show that changed list
     =====
     Go to the first element in the list #distractor
     =====
     Add that value to itself #distractor
     =====
     Show the changed list #distractor



Section 2: Fill in the Blank
:::::::::::::::::::::::::::::


Choose the correct choice to fill in the blank of the code:



.. mchoice:: post1_1
    :correct: a
    :answer_a: names = getClassNames()
    :answer_b: num
    :answer_c: heights = getHeights()
    :answer_d: for i in range
    :answer_e: names = getClassGrades()


        .. code-block:: python


             (1)

             (2)(len(names)):

               if names[i].startwith((3))
                  names[i] = "Jimmy"

             print(names)



.. mchoice:: post1_2
    :correct: b
    :answer_a: heights
    :answer_b: for i in range
    :answer_c: num <= 0
    :answer_d: if i in range
    :answer_e: for n in range


        .. code-block:: python

             (1)

             (2)(len(names)):

               if names[i].startwith((3))
                  names[i] = "Jimmy"

             print(names)



.. mchoice:: post1_3
    :correct: b
    :answer_a: heights
    :answer_b: J
    :answer_c: names
    :answer_d: K
    :answer_e: num


        .. code-block:: python

              (1)

             (2)(len(names)):

               if names[i].startwith((3))
                  names[i] = "Jimmy"

             print(names)











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

Replace all long notes with a shorter note


Section 1: Parsons Problem
::::::::::::::::::::::::::::


Parsons Problem
----------------

.. parsonsprob:: sumnoteParsons

    Match the labels to the appropriate parts of the code.


    notes = getNotes(“yodel.midi”)

    for i in range(len(notes)):

        if duration(notes[i] > 5000):
            setDuration(notes[i], 5000)

    plays(notes)

   -----
   Collect input list
   =====
   Go through all elements in the list
   =====
   If that element meets the criteria
   =====
   Replace it with a new value
   =====
   Show that changd list
   =====
   Go to the first element in the list #distractor
   =====
   Add that value to itself #distractor
   =====
   Show the changed list #distractor




Section 2: Fill in the Blank
:::::::::::::::::::::::::::::


Choose the correct choice to fill in the blank of the code:



.. mchoice:: post1_1
    :correct: a
    :answer_a: range(len(notes))
    :answer_b: range(pitch(notes))
    :answer_c: num >= 0
    :answer_d: notes
    :answer_e: heights


        .. code-block:: python

            notes = getNotes(“yodel.midi”)

            for i in (1):

                (2) (notes[i] > 5000):
                    setDuration(notes[i], 5000)

            (3)



.. mchoice:: post1_2
    :correct: b
    :answer_a: if num == 0
    :answer_b: if duration
    :answer_c: else
    :answer_d: if pitch
    :answer_e: error(“Can’t draw negative or zero cards!”)


        .. code-block:: python

            notes = getNotes(“yodel.midi”)

            for i in (1):

                (2) (notes[i] > 5000):
                    setDuration(notes[i], 5000)

            (3)



.. mchoice:: post1_3
    :correct: e
    :answer_a: plays(s)
    :answer_b: print(images)
    :answer_c: notes = getNotes()
    :answer_d: num
    :answer_e: plays(notes)


        .. code-block:: python

            notes = getNotes(“yodel.midi”)

            for i in (1):

                (2) (notes[i] > 5000):
                    setDuration(notes[i], 5000)

            (3)











Section 3: Write Code
:::::::::::::::::::::::::

ActiveCode
----------

.. activecode:: sumnoteActivecode

   :coach:
   :caption: This is a caption

    notes = getNotes(“yodel.midi”)





    plays(notes)



.. Picture


Make all very bright pixels blue.


Section 1: Parsons Problem
::::::::::::::::::::::::::::


Parsons Problem
----------------

Match the labels to the appropriate parts of the code.


.. parsonsprob:: replacementpixelParsons


    pixles = getPixels(“sunset.jpg”)

    for p in pixels:
        if luminance(p) > 200:
            setBlue (p, 255)

    show(makePic(pixels), dimensions(“sunset.jpg)))


   -----
   Collect input list
   =====
   Go through all elements in the list
   =====
   If that element meets the criteria
   =====
   Replace it with a new value
   =====
   Show that changd list
   =====
   Go to the first element in the list #distractor
   =====
   Add that value to itself #distractor
   =====
   Show the changed list #distractor




Section 2: Fill in the Blank
:::::::::::::::::::::::::::::


Choose the correct choice to fill in the blank of the code:



.. mchoice:: post1_1
    :correct: a
    :answer_a: pixels
    :answer_b: heights
    :answer_c: getCards()
    :answer_d: if luminance(p) > 200
    :answer_e: setBlue


        .. code-block:: python

        (1) = getPixels(“sunset.jpg”)

          for p in pixels:
             (2)
               (3) (p, 255)

          show(makePic(pixels), dimensions(“sunset.jpg)))



.. mchoice:: post1_2
    :correct: d
    :answer_a: number
    :answer_b: if luminance(p) <= 200
    :answer_c: getCards()
    :answer_d: if luminance(p) > 200
    :answer_e: setGreen


        .. code-block:: python

            num = getNumber()

            if 1) :

                  2)

            else:

                drawCards( 3) )



.. mchoice:: post1_3
    :correct: 2
    :answer_a: setGreen
    :answer_b: if luminance(p) == 200
    :answer_c: getLuminance
    :answer_d: if luminance(p) > 200
    :answer_e: setBlue


        .. code-block:: python

            num = getNumber()

            if 1) :

                  2)

            else:

                drawCards( 3) )









Section 3: Write Code
:::::::::::::::::::::::::

ActiveCode
----------

.. activecode:: replacementpixelActivecode

   :coach:
   :caption: This is a caption

  pixles = getPixels(“sunset.jpg”)





  show(makePic(pixels), dimensions(“sunset.jpg)))

