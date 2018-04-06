=====================
Sum All
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


Sum up the brightness values of the pixels

Section 1: Parsons Problem
::::::::::::::::::::::::::::


Parsons Problem
----------------

.. parsonsprob:: sumpixelParsons

    Match the labels to the appropriate parts of the code.

   pixels = getPixels("beach.jpg")

   sumLuminance= 0

   for p in pixels:
     sumLuminance += luminance(p)

   print(sumLuminance)
   -----
   Collect input
   Start sum with zero
   Go through all items in the list
   Add that value to the sum
   Show the sum
   =====
   Go to the first element in the list #distractor
   Add that value to itself #distractor
   Show the changed list #distractor


Section 2: Fill in the Blank
:::::::::::::::::::::::::::::

Fill in blank parts of code to complete the method.

..fillintheblank:: sumpixelFillblank

   |blank| getPixels("beach.jpg")

   sumLuminance= 0

   |blank|
     sumLuminance |blank|

   print(sumLuminance)



    - :answer: Feedback for blank 1
      :x: The last item
    - :answer: Feedback for blank 2







Section 3: Write Code
:::::::::::::::::::::::::

ActiveCode
----------

.. activecode:: sumpixelActivecode

   :coach:
   :caption: This is a caption

   pixels = getPixels("beach.jpg")





   print(sumLuminance)
