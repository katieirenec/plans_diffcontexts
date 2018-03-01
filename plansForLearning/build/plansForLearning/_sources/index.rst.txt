=========================
Multiple Choice Pre-Test
=========================

.. Here is were you specify the content and order of your new book.

.. Each section heading (e.g. "SECTION 1: A Random Section") will be
   a heading in the table of contents. Source files that should be
   generated and included in that section should be placed on individual
   lines, with one line separating the first source filename and the
   :maxdepth: line.

.. Sources can also be included from subfolders of this directory.
   (e.g. "DataStructures/queues.rst").

Introduction
:::::::::::::::::::::::
//insert introduction text blurb here//



Multiple Choice
---------------

.. mchoice:: question1_1
    :multiple_answers:
    :correct: c
    :answer_a: A
    :answer_b: B
    :answer_c: C
    :answer_d: D
    :answer_e: Nothing is printed.

    Consider the following code:

	if a > 0 and b > 0:
	    if a > b:
		print("A")
   	    else:
		print("B")
	elif b < 0 or a < 0:
   		print("C")
	else:
    		print("D")

    **What is printed when a is 3, and b is -2?**

.. mchoice:: question1_1
    :multiple_answers:
    :correct: d
    :answer_a: [12, 9, 8, 4, 3, 6, 11, 1, 7]
    :answer_b: [12, 9, 7, 8, 4, 6, 11, 1, 3]
    :answer_c: [12, 9, 7, 4, 3, 6, 11, 1, 8]
    :answer_d: [8, 4, 3, 6, 11, 1, 12, 9, 7]
    :answer_e: [1, 11, 6, 12, 9, 7, 8, 4, 3]

Consider the following code:

	list = getInputList()
	n = getNValue()

	for k in range(0, n):
		item = list[0]
		del list[0]
		list.append[item]

	print(list)

	Assume that the input collected by **getInputList()** is [12, 9, 7, 8, 4, 3, 6, 11, 1]. **What is printed if the n value is 3?**


.. mchoice:: question1_1
    :multiple_answers:
    :correct: a,b,d
    :answer_a: 
	arr = getInputList()
	isEven = false
	for x in arr:
	    if x % 2 == 0:
	        isEven = true
	print(isEven)

    :answer_b: 
	arr = getInputList()
        isEven = false
	for x in arr:
	    if x % 2 != 0
	        isEven = false
	    else:
	        isEven = true
        print(isEven)

    :answer_c: 
	arr = getInputList()
	isEven = false
	for x in arr:
	    if x % 2!= 0:
	        isEven = false
	    print(isEven)

    :answer_d: 
	arr = getInputList()
	isEven = true;
	if x % 2 != 0:
	    isEven = false
	else:
	    isEven = true
	print(isEven)

    :answer_e: 
	arr = getInputList()
	isEven = true
	for x in arr:
	    if x % 2 == 0:
	        isEven = false
	    else:
		isEven = true
	print(isEven)

	Consider the following segments of code. Which piece of code prints true if all items in the list are even numbers?

.. mchoice:: question1_1
    :multiple_answers:
    :correct: a,b,d
    :answer_a: I only
    :answer_b: II only
    :answer_c: III only
    :answer_d: I and III
    :answer_e: II and III

    Consider the following code:
	if value < 0 or value > 100:
	    print("Not in range")
	else:
	    print("In range")

    Consider the following code segments that could be used to replace the code above.
	**I.**	if value < 0:
		    if value > 100:
			print("Not in range")
		    else:
			print("In range")
		else:
		    print("In range")

	**II.**	if value < 0:
		    print("Not in range")
		elif value > 100:
		    print("Not in range")
		else:
		    print("In range")

	**III.**if value >= 0:
		    print("In range")
		elif value <= 100:
		    print("in range")
		else:
		    print("Not in range")

	**Which of the replacements will have the same behavior as the original version above?**

.. mchoice:: question1_1
    :multiple_answers:
    :correct: a,b,d
    :answer_a: red
    :answer_b: yellow
    :answer_c: black
    :answer_d: green
    :feedback_a: Red is a definitely on of the colors.
    :feedback_b: Yes, yellow is correct.
    :feedback_c: Remember the acronym...ROY G BIV.  B stands for blue.
    :feedback_d: Yes, green is one of the colors.

    Which colors might be found in a rainbow? (choose all that are correct)


