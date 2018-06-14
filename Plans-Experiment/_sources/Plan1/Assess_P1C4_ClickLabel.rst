======================================================
"Check If Empty" Plan Post-Test - Match labels to code
======================================================

Use what you've learned about the "Check if Empty" plan to solve the problem below.

I am creating a course roster for my class. A course roster is made up of students.

My goal is to **determine if the course roster entered by the user is empty before saving the roster**.

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


.. clickablearea:: P1L2
    :question: Click on the code best decribed by "If the input is empty".
    :iscode:
    
    :click-incorrect:new_roster = enterCourseRoster():endclick:

    :click-correct:if length(new_roster) == 0::endclick:
        :click-incorrect:error(“Roster has no students!”):endclick:
    :click-incorrect:else:
        save(new_roster):endclick:


.. clickablearea:: P1L1
    :question: Click on the code best decribed by "Collect input".
    :iscode:
    
    :click-correct:new_roster = enterCourseRoster():endclick:

    :click-incorrect:if length(new_roster) == 0::endclick:
        :click-incorrect:error(“Roster has no students!”):endclick:
    :click-incorrect:else:
        save(new_roster):endclick:



.. clickablearea:: P1L4
    :question: Click on the code best decribed by "Otherwise, do something with the input".
    :iscode:
    
    :click-incorrect:new_roster = enterCourseRoster():endclick:

    :click-incorrect:if length(new_roster) == 0::endclick:
        :click-incorrect:error(“Roster has no students!”):endclick:
    :click-correct:else:
        save(new_roster):endclick:


.. clickablearea:: P1L3
    :question: Click on the code best decribed by "Show error".
    :iscode:
    
    :click-incorrect:new_roster = enterCourseRoster():endclick:

    :click-incorrect:if length(new_roster) == 0::endclick:
        :click-correct:error(“Roster has no students!”):endclick:
    :click-incorrect:else:
        save(new_roster):endclick:



