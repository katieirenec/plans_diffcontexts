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



Section 1: Parsons Problem
::::::::::::::::::::::::::::


Parsons Problem
----------------

.. parsonsprob:: emptynumberParsons

    Match the labels to the appropriate parts of the code.

    num = getNumber()
    if num <= 0:
        error("Can't draw negative or zero card!")
    else:
        drawCard(num)
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



