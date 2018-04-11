=====================
Check If Valid
=====================

.. Here is were you specify the content and order of your new book.

.. Each section heading (e.g. "SECTION 1: A Random Section") will be
   a heading in the table of contents. Source files that should be
   generated and included in that section should be placed on individual
   lines, with one line separating the first source filename and the
   :maxdepth: line.

   Congratulations!   If you can see this file you have probably successfully run the ``runestone init`` command.  If you are looking at this as a source file you should now run ``runestone build``  to generate html files.   Once you have run the build command you can run ``runestone serve`` and then view this in your browser at ``http://localhost:8000``

.. Sources can also be included from subfolders of this directory.
   (e.g. "DataStructures/queues.rst").


Determine if the name entered by the user is not empty before saying hello to that person.


Section 1: Parsons Problem
::::::::::::::::::::::::::::


Parsons Problem
----------------

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


    Choose the correct choice to fill in the blank of the code:


    Section 2: Fill in the Blank
    :::::::::::::::::::::::::::::


    .. mchoice:: post1_1
        :correct: a
        :answer_a: name = inputString()
        :answer_b: s == 0
        :answer_c: cards
        :answer_d: "Name string is not empty!"
        :answer_e: address = inputString()


            .. code-block:: python

                (1)

                if (2) :

                      error((3))

                else:
                    print ("Hello ", name)






    .. mchoice:: post1_2
        :correct: b
        :answer_a: num <= 0
        :answer_b: s == ""
        :answer_c: error(“Can’t draw negative or zero cards!”)
        :answer_d: "Name string is not empty!"
        :answer_e: getString()


            .. code-block:: python

                (1)

                if (2) :

                      error((3))

                else:
                    print ("Hello ", name)



    .. mchoice:: post1_3
        :correct: d
        :answer_a: getCards()
        :answer_b: "Name string is not empty!"
        :answer_c: num <= 0
        :answer_d: "Name string is empty!"
        :answer_e: s == ""


            .. code-block:: python

                (1)

                if (2) :

                      error((3))

                else:
                    print ("Hello ", name)







Section 3: Write Code
:::::::::::::::::::::::::

ActiveCode
----------

.. activecode:: emptystringActivecode

   :coach:
   :caption: This is a caption

   name = inputString()




   print("Hello ", name)




..Notes
=====================
Check If Valid
=====================

.. Here is were you specify the content and order of your new book.

.. Each section heading (e.g. "SECTION 1: A Random Section") will be
   a heading in the table of contents. Source files that should be
   generated and included in that section should be placed on individual
   lines, with one line separating the first source filename and the
   :maxdepth: line.

   Congratulations!   If you can see this file you have probably successfully run the ``runestone init`` command.  If you are looking at this as a source file you should now run ``runestone build``  to generate html files.   Once you have run the build command you can run ``runestone serve`` and then view this in your browser at ``http://localhost:8000``

.. Sources can also be included from subfolders of this directory.
   (e.g. "DataStructures/queues.rst").


Determine if the song chosen by the user is not empty before playing that song.


Section 1: Parsons Problem
::::::::::::::::::::::::::::


Parsons Problem
----------------

.. parsonsprob:: emptynoteParsons

    Match the labels to the appropriate parts of the code.

    song = chooseSong()

    if length(s) == 0:
        error("No notes in sound!")

    else:
        play(song)

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
   If the input is valid #distractor
   =====
   If the input is valid #distractor








    Section 2: Fill in the Blank
    :::::::::::::::::::::::::::::

    Choose the correct choice to fill in the blank of the code:


    .. mchoice:: post1_1
        :correct: a
        :answer_a: chooseSong()
        :answer_b: length(s) == 0
        :answer_c: else: play(song)
        :answer_d: num <= 0
        :answer_e: chooseBook()


            .. code-block:: python

                song = (1)

                if (2)
                    error("No notes in sound!")

                (3)



    .. mchoice:: post1_2
        :correct: b
        :answer_a: num <= 0
        :answer_b: length(s) == 0
        :answer_c: song
        :answer_d: length(s) == 1
        :answer_e: error(“Can’t draw negative or zero cards!”)


            .. code-block:: python

                song = (1))

                if (2)
                    error("No notes in sound!")

                (3)



    .. mchoice:: post1_3
        :correct: d
        :answer_a: num <= 0
        :answer_b: choosePicture()
        :answer_c: num > 0
        :answer_d: else: play(song)
        :answer_e: length(s) == 2


            .. code-block:: python

                song = (1))

                if (2)
                    error("No notes in sound!")

                (3)







Section 3: Write Code
:::::::::::::::::::::::::

ActiveCode
----------

.. activecode:: emptynoteActivecode

   :coach:
   :caption: This is a caption

   song = chooseSong()




   play(song)





.. Picture
=====================
Check If Valid
=====================

.. Here is were you specify the content and order of your new book.

.. Each section heading (e.g. "SECTION 1: A Random Section") will be
   a heading in the table of contents. Source files that should be
   generated and included in that section should be placed on individual
   lines, with one line separating the first source filename and the
   :maxdepth: line.

   Congratulations!   If you can see this file you have probably successfully run the ``runestone init`` command.  If you are looking at this as a source file you should now run ``runestone build``  to generate html files.   Once you have run the build command you can run ``runestone serve`` and then view this in your browser at ``http://localhost:8000``

.. Sources can also be included from subfolders of this directory.
   (e.g. "DataStructures/queues.rst").


Determine if the picture chosen by the user is not empty before viewing the picture.


Section 1: Parsons Problem
::::::::::::::::::::::::::::


Parsons Problem
----------------

.. parsonsprob:: emptypictureParsons

  Match the labels to the appropriate parts of the code.

  picture = pickPicture()

  if length(getPixels(p)) == 0:
    error("Picture has no pixels!")

  else:
    view(picture)

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
   If the input is valid #distractor
   =====
   If the input is valid #distractor






Section 2: Fill in the Blank
:::::::::::::::::::::::::::::


Choose the correct choice to fill in the blank of the code:



.. mchoice:: post1_1
    :correct: a
    :answer_a: picture =
    :answer_b: notes =
    :answer_c: pickNotes()
    :answer_d: if length(getPixels(picture)) > 0
    :answer_e: result =


        .. code-block:: python

            (1) pickPicture()

            (2)
              error("Picture has no pixels!")

            (3)
              view(picture)



.. mchoice:: post1_2
    :correct: b
    :answer_a: num <= 0
    :answer_b: if length(getPixels(picture)) == 0
    :answer_c: pickPixels()
    :answer_d: if length(getPixels(picture)) > 0
    :answer_e: picture =


        .. code-block:: python

            (1) pickPicture()

            (2)
              error("Picture has no pixels!")

            (3)
              view(picture)



.. mchoice:: post1_3
    :correct: d
    :answer_a: if
    :answer_b: if length(getPixels(picture)) > 0
    :answer_c: pickNotes()
    :answer_d: else
    :answer_e: result =

        .. code-block:: python

            (1) pickPicture()

            (2)
              error("Picture has no pixels!")

            (3)
              view(picture)







Section 3: Write Code
:::::::::::::::::::::::::

ActiveCode
----------

.. activecode:: emptypictureActivecode

   :coach:
   :caption: This is a caption

   picture = pickPicture()




   view(picture)

