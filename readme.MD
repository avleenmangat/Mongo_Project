#Course Management 

## Courses
###id: Unique identifier for the course.
###name: Name of the course.
###description: Description of the course.
###instructor: Name or ID of the instructor teaching the course.
###schedule: Array of scheduled class times/dates.
###enrollment_limit: Maximum number of students allowed to enroll in the course.

## Students
###id: Unique identifier for the student.
###name: Full name of the student.
###email: Email address of the student.
###courses: Array of course IDs the student is enrolled in.
###registration_date: Date when the student registered.

## Instructors
###id: Unique identifier for the instructor.
###name: Full name of the instructor.
###email: Email address of the instructor.
###courses_taught: Array of course IDs taught by the instructor.
###department: Department the instructor belongs to.

## Schedules
###id: Unique identifier for the classroom.
###name: Name of the classroom.
###capacity: Maximum seating capacity of the classroom.
###course_name: Name of the course.
###date: Details of the lecture.

##Enrollments
###id: Unique identifier for the enrollment.
###student_id: ID of the student enrolling.
###course_id: ID of the course being enrolled in.
###enrollment_date: Date when the enrollment was made.
###status: Status of the enrollment (e.g., enrolled, waitlisted, withdrawn).
