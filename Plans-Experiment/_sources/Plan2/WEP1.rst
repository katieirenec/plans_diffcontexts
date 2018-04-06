=====================
Guarded Replacement
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


Replace all the names that start with J with the name "Jimmy".

Section 1: Parsons Problem
::::::::::::::::::::::::::::


Parsons Problem
----------------

.. parsonsprob:: replacementstringParsons

    Match the labels to the appropriate parts of the code.

    names = getClassNames()

   for i in range(len(names)):
      if names[i].startwith("J"):
         names[i]="Jimmy"

   print(names)
   -----
   Collect input list
   Go through all elements in the list
   If that element meets the criteria
   Replace it with a new value
   Show the changed list
   =====
   Go through one element in the list #distractor
   Keep the old value #distractor
   If that element does not meet the criteria #distractor


Section 2: Fill in the Blank
:::::::::::::::::::::::::::::

Fill in blank parts of code to complete the method.

..fillintheblank:: replacementstringFillblank

   |blank|

   |blank|(len(names)):
      if names[i].startwith(|blank|):
         names[i]="Jimmy"

   print(names)

    - :answer: Feedback for blank 1
      :x: The last item
    - :answer: Feedback for blank 2







Section 3: Write Code
:::::::::::::::::::::::::

ActiveCode
----------

.. activecode:: replacementstringActivecode

   :coach:
   :caption: This is a caption

   names = getClassNames()




   print(names)
