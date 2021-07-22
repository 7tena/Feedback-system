# Feedback System
The Feedback System is an automatic feedback generation system
that provides the proper feedback to the lecturers. Feedback is undoubtedly crucial
when it comes to educating students. Without proper feedback, we fail to acknowledge
the issues students might face while attending a particular lecturer’s class and this
leads to ineffectiveness of the lectures which will be carried on to successive batches.
Feedback and evaluation of a lecturer and his/her sessions, ensures high efficiency
and continuous improvement from the teacher’s side. This in turn improves the quality
of the institution and the students studying there.

This online feedback system will make it easier for the students to provide insightful
evaluation of a teacher’s skills and classes, and for the head of each department to
analyse the performance of all the teachers.


## Motivation
The root intent behind initiating and developing this system is to contribute as much as
we could in improving our current educational structure. Assessments of a student’s
performance is an integral and regular part of the curriculum. But the same cannot
be said when it comes to our educators. We are lacking in fairly assessing them and
hence this can bring about an unequal impartment of quality education. With our
faculty evaluation system, we attempt to eliminate that gap.


## Objective 
To develop an Online Student Feedback System that provides the proper feedback to
the lecturers.


## Design
- [ ] Use Case Diagram
- [ ] ER Diagram
- [ ] Data Flow Diagram


## Users and functionalities
- [ ] Admin 
    - Add Departments 
    - Add HODs

- [ ] HOD 
    - Add classes and corresponding subjects in the system  
    - Add students to the registered classes
    - View feedbacks from students
    - Generate Reports

- [ ] Student
    - Select available subjects with corresponding teachers
    - Give feedback for the courses and faculty


## Implementation Details
> The tech stacks used for the feedback sysytem involves :

    1. Node.js for developing the backend of the application
    2. MySql engine is used as the database
    3. Sequelize for ORM (Object Relational Mapping)
    4. Express web framework
    5. EJS view engine to design HTML page
    6. Nodemon package to run the node server


## UI Snippets


## Conclusion and Future Scope
The project was hosted with minimal functionalities using basic technologies. The
future scope of the project includes the following modifications :
1. Improving the UI to increase the user experience
2. Allowing students to submit feedback whenever they wish to do it, instead of the
current model which only takes feedback at the end of the semester
3. To include a notification system that alerts the faculty when a student has submitted
a feedback for him/her.
