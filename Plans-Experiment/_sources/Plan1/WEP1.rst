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

.. parsonsprob:: emptystringParsons

    Match the labels to the appropriate parts of the code.

    name = inputString()
    if name == "":
        error("Name string is empty!")
    else:
        print("Hello ", name)
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


Section 2: Fill in the Blank
:::::::::::::::::::::::::::::

Fill in blank parts of code to complete the method.

..fillintheblank:: emptystringFillblank

    |blank|

    if |blank| :

        error(|blank|)

    else:

         print("Hello ", name)

    - :answer: Feedback for blank 1
      :x: The last item
    - :answer: Feedback for blank 2







Section 3: Write Code
:::::::::::::::::::::::::

ActiveCode
----------

.. activecode:: emptystringActivecode

   :coach:
   :caption: This is a caption

   name = inputString()




   print("Hello ", name)
