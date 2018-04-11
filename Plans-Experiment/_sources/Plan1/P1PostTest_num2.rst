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


Determine if the number of cards entered by the user is valid before drawing that number of cards.


.. timed:: posttest1-fillinblank_timed
    :timelimit: 5
    :nofeedback:


    Section 2: Fill in the Blank
    :::::::::::::::::::::::::::::

    Fill in blank parts of code to complete the method.


    .. mchoice:: post1_1
        :correct: a
        :answer_a: num <= 0
        :answer_b: num > 0
        :answer_c: getNumber()
        :answer_d: cards
        :answer_e: print ("Cards")

        Choose the correct choice to fill in the blank of the code:

            .. code-block:: python

                num = getNumber()

                if 1) :

                      2)

                else:

                    drawCards( 3) )



    .. mchoice:: post1_2
        :correct: b
        :answer_a: num <= 0
        :answer_b: error(“Can’t draw negative or zero cards!”)
        :answer_c: num > 1
        :answer_d: getNumber()
        :answer_e: num >= 0

        Choose the correct choice to fill in the blank of the code:

            .. code-block:: python

                num = getNumber()

                if 1) :

                      2)

                else:

                    drawCards( 3) )



    .. mchoice:: post1_3
        :correct: d
        :answer_a: num <= 0
        :answer_b: getNumbder()
        :answer_c: print ("Cards")
        :answer_d: num
        :answer_e: cards

        Choose the correct choice to fill in the blank of the code:

            .. code-block:: python

                num = getNumber()

                if 1) :

                      2)

                else:

                    drawCards( 3) )





