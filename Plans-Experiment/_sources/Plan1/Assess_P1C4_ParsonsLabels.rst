===============================================
"Check If Empty" Plan Post-Test - Order labels
===============================================

Use what you've learned about the "Check if Empty" plan to solve the problem below.

I am working with a course roster for my class. A course roster is made up of students.

My goal is to **determine if the PSY-P 101 course roster is empty before showing the grade distribution of that course**.

Click on the button below to learn more about code you can use to work with course rosters.

.. reveal:: contextbox_C4
    :showtitle: Show information about code for course rosters
    :hidetitle: Hide information about code for course rosters

    A course roster contains students.

    There are several ways to get a course roster as input::

       getCourseRoster("Put course name here")
       enterCourseRoster()

    You can get the number of students in the roster::

	length(roster)

    Each student has some values:
	*Final Score* – from 0-100::
		
		getFinalScore(student)
		setFinalScore(student, newFinalScore)

	*Attendance Points* – points for participating in class::

		getAttendancePoints(student)
		setAttendancePoints(student, newAttendancePoints)

	*Extra Credit* – number of extra credit points::

		getExtraCredit(student)
		setExtraCredit(student, newExtraCredit)

    There are several things you can do with a course roster::

        save(roster)
	showGradeDistribution(roster)
	getHighestGrade(roster)
	dropAbsentStudents(roster)


.. parsonsprob:: emptynumberParsons

       Choose the labels that describe the pieces of code you would need to solve this problem, and place them in the correct order. There are more labels available than you need.

       -----
       Collect input
       =====
       If the input is empty
       =====
       Show error
       =====
       Otherwise, do something with the input
       =====
       If the input is not empty #distractor
       =====
       Otherwise, show error #distractor
       =====
       Go through all items #distractor


