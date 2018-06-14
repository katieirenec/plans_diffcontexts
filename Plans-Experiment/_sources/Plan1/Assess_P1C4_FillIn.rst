==============================================
"Check If Empty" Plan Post-Test - Fill in code
==============================================

Use what you've learned about the "Check if Empty" plan to solve the problem below.

I am working with a course roster for my class. A course roster is made up of students.

My goal is to **determine if the BIOL-L 311 course roster is empty before dropping absent students from that course**.

Some of the code to achieve this goal is below. 

.. code-block:: python

        bio_course = getCourseRoster("BIOL-L 311")

        if ____1____ :

            ____2____

        else:

            dropAbsentStudents( ____3____ )


.. reveal:: contextbox_C4
    :showtitle: Show information about code for course rosters
    :hidetitle: Hide information about code for course rosters

    A course roster contains students.

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



In the questions below, choose the pieces of code that should complete the blanks.


.. mchoice:: posttest_P1_C4_FillIn_1
        :correct: a
        :answer_a: roster == 0
        :answer_b: length(bio_course) == 0
        :answer_c: error("The roster must have students!")
        :answer_d: length(roster) > 0
        :answer_e: bio_course > 0

        Which code should go in ____1____?



.. mchoice:: posttest_P1_C4_FillIn_2
        :correct: b
        :answer_a: roster > 0
        :answer_b: error("The roster must have students!")
        :answer_c: error("The roster has too many students!")
        :answer_d: enterCourseRoster()
        :answer_e: length(bio_course) == 0

        Which code should go in ____2____?


.. mchoice:: posttest_P1_C4_FillIn_3
        :correct: e
        :answer_a: error("The roster must have students!")
        :answer_b: length(roster) > 0
        :answer_c: length(bio_course)
        :answer_d: roster
        :answer_e: bio_course

        Which code should go in ____3____?



