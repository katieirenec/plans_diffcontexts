==============================================
"Check If Empty" Plan Post-Test - Order code
==============================================

Use what you've learned about the "Check if Empty" plan to solve the problem below.

I am examining a course roster for my class. A course roster is made up of students.

My goal is to **determine if the PSY-P 101 course roster is empty before showing the grade distribution of that course**.

.. reveal:: contextbox_C4
    :showtitle: Show information about code for course rosters
    :hidetitle: Hide information about code for course rosters

    There are several ways to get a course roster::

       getCourseRoster("Put course name here")
       enterCourseRoster()

    You can get the number of students in the roster::

	length(roster)

    Each student has its own:
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

       The code below is mixed up and contains extra blocks that are not needed.  Drag the needed code from the left to the right and put them in order with the correct indention so that the code would work correctly. 

       -----
       roster = getCourseRoster(“PSY-P 101”)
       =====
       if length(roster) == 0:
       =====
           error("The roster shouldn’t be empty!")
       =====
       else:
       =====
           showGradeDistribution(roster)
       =====
       for student in roster: #distractor
       =====
       if roster == 0: #distractor
       =====
       save(roster) #distractor



