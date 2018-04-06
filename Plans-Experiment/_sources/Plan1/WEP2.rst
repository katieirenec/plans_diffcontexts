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
   If the input is not valid
   Show error
   Otherwise, do something with the input
   =====
   If the input is valid #distractor


Section 2: Fill in the Blank
:::::::::::::::::::::::::::::

Fill in blank parts of code to complete the method.

..fillintheblank:: emptynoteFillblank

    song = |blank|

    if |blank| :

        error("No notes in sound!")

    |blank|



    - :answer: Feedback for blank 1
      :x: The last item
    - :answer: Feedback for blank 2







Section 3: Write Code
:::::::::::::::::::::::::

ActiveCode
----------

.. activecode:: emptynoteActivecode

   :coach:
   :caption: This is a caption

   song = chooseSong()




   play(song)
