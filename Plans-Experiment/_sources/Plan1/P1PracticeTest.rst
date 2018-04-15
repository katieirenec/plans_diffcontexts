=====================
Practice Test
=====================

.. Here is were you specify the content and order of your new book.


Determine if the name entered by the user is not empty before saying hello to that person.


String - 1: Match Logic and Code
::::::::::::::::::::::::::::::::::::


.. code-block:: python

      name = inputString()

      if name == "":
          error("Name string is empty!")

      else:
          print("Hello ", name)



.. parsonsprob:: emptystringParsons

    Match the labels to the appropriate parts of the code.



   -----
   Collect input
   =====
   If the input is not valid
   =====
   Show error
   =====
   Otherwise, do something with the input
   =====
   If the input is valid #distractor
   =====
   Show the sum #distractor
   =====
   Go through one element in the list #distractor



String - 2: Fill in the Blank
:::::::::::::::::::::::::::::

Choose the correct choice to fill in the blank of the code:


.. code-block:: python

    (1)

    if (2) :

          error((3))

    else:
        print ("Hello ", name)


.. mchoice:: post1_1
  :correct: a
  :answer_a: name = inputString()
  :answer_b: s == 0
  :answer_c: cards
  :answer_d: "Name string is not empty!"
  :answer_e: address = inputString()




.. mchoice:: post1_2
  :correct: b
  :answer_a: num <= 0
  :answer_b: s == ""
  :answer_c: error(“Can’t draw negative or zero cards!”)
  :answer_d: "Name string is not empty!"
  :answer_e: getString()




.. mchoice:: post1_3
  :correct: d
  :answer_a: getCards()
  :answer_b: "Name string is not empty!"
  :answer_c: num <= 0
  :answer_d: "Name string is empty!"
  :answer_e: s == ""










String - 3: Write Code
:::::::::::::::::::::::::


.. activecode:: emptystringActivecode


   name = inputString()




   print("Hello ", name)









Notes - 1: Match Logic and Code
::::::::::::::::::::::::::::::::::::


Determine if the song chosen by the user is not empty before playing that song.


.. code-block:: python

      song = chooseSong()

      if length(s) == 0:
          error("No notes in sound!")

      else:
          play(song)


.. parsonsprob:: emptynoteParsons

    Match the labels to the appropriate parts of the code.

   -----
   Collect input
   =====
   If the input is not valid
   =====
   Show error
   =====
   Otherwise, do something with the input
   =====
   If the input is valid #distractor
   =====
   Show the sum #distractor
   =====
   Go through one element in the list #distractor








Notes - 2: Fill in the Blank
:::::::::::::::::::::::::::::

Choose the correct choice to fill in the blank of the code:



.. code-block:: python

    song = (1)

    if (2)
        error("No notes in sound!")

    (3)


.. mchoice:: post1_1
    :correct: a
    :answer_a: chooseSong()
    :answer_b: length(s) == 0
    :answer_c: else: play(song)
    :answer_d: num <= 0
    :answer_e: chooseBook()



.. mchoice:: post1_2
    :correct: b
    :answer_a: num <= 0
    :answer_b: length(s) == 0
    :answer_c: song
    :answer_d: length(s) == 1
    :answer_e: error(“Can’t draw negative or zero cards!”)




.. mchoice:: post1_3
    :correct: d
    :answer_a: num <= 0
    :answer_b: choosePicture()
    :answer_c: num > 0
    :answer_d: else: play(song)
    :answer_e: length(s) == 2








Notes - 3: Write Code
:::::::::::::::::::::::::


.. activecode:: emptynoteActivecode

   song = chooseSong()




   play(song)





.. Picture



Picture - 1: Match Code and Logic
:::::::::::::::::::::::::::::::::::::


Determine if the picture chosen by the user is not empty before viewing the picture.


.. code-block :: python

    picture = pickPicture()

    if length(getPixels(p)) == 0:
      error("Picture has no pixels!")

    else:
      view(picture)



.. parsonsprob:: emptypictureParsons

  Match the labels to the appropriate parts of the code.


  -----
  Collect input
  =====
  If the input is not valid
  =====
  Show error
  =====
  Otherwise, do something with the input
  =====
  Show successful message #distractor
  =====
  Otherwise, don't do something with the input #distractor
  =====
  Don't collect input #distractor








Picture - 2: Fill in the Blank
:::::::::::::::::::::::::::::::::


Choose the correct choice to fill in the blank of the code:


.. code-block:: python

    (1) pickPicture()

    (2)
      error("Picture has no pixels!")

    (3)
      view(picture)


.. mchoice:: post1_1
    :correct: a
    :answer_a: picture =
    :answer_b: notes =
    :answer_c: pickNotes()
    :answer_d: if length(getPixels(picture)) > 0
    :answer_e: result =



.. mchoice:: post1_2
    :correct: b
    :answer_a: num <= 0
    :answer_b: if length(getPixels(picture)) == 0
    :answer_c: pickPixels()
    :answer_d: if length(getPixels(picture)) > 0
    :answer_e: picture =



.. mchoice:: post1_3
    :correct: d
    :answer_a: if
    :answer_b: if length(getPixels(picture)) > 0
    :answer_c: pickNotes()
    :answer_d: else
    :answer_e: result =








Picture - 3: Write Code
:::::::::::::::::::::::::


.. activecode:: emptypictureActivecode

   picture = pickPicture()




   view(picture)

