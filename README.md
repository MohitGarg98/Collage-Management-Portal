## Collage Managemt Portal
  
### Login Page:
User should be able to login as student or teacher

### Signup Page:
User should be able to signup as student or teacher

### Profile page:
Users should able to edit their information from here. Like passwords, name.

### Student Dashboard:
&nbsp;&nbsp;&nbsp;- Students should be able to see 2 tabs (Submitted assignments, Upcoming assignments) in the Dashboard.  
&nbsp;&nbsp;&nbsp;- Upcoming Assignments tab is a list of assignments whose deadline has not passed.  
&nbsp;&nbsp;&nbsp;- Students can submit any assignment in “Upcoming Assignments” tab. They’ll have to upload a pdf file  
&nbsp;&nbsp;&nbsp;- Students can view their submissions in “Submitted Assignments” tab(along with the grades if assigned by the teacher).  

### Teacher’s dashboard:
&nbsp;&nbsp;&nbsp;- A teacher should be able to add assignments with deadlines, title, description etc (you can add whatever you can think of).  
&nbsp;&nbsp;&nbsp;- A teacher can view the submissions (and also those who have not submitted) of all the assignments.  
&nbsp;&nbsp;&nbsp;- A teacher can view all the submissions and give a grade for each submission for a particular assignment.  
&nbsp;&nbsp;&nbsp;- Once evaluated, students should be able to see their grades in their Submitted Assignments section.  

### All API's  
    http://localhost:9000/student-login (For student login)  
    http://localhost:9000/teacher-login (For teacher login)  
    http://localhost:9000/create-student (For register a student)  
    http://localhost:9000/create-teacher (for register a teacher)  
    http://localhost:9000/get-assignment (For get assignments added by the teacher)  
    http://localhost:9000/get-submit-assignment (For get the assignment submitted by student)  
    http://localhost:9000/add-assignments (For add the assignment by the teacher)  
    http://localhost:9000/get-assignments (For get all the assignmnets given by the teacher)  
    http://localhost:9000/submit-assignments (For submit the assignment by student given by the teacher)  
    http://localhost:9000/submit-grade (For submit grade by teacher for a assignment)  
    http://localhost:9000/edit-student (For edit the student's detail like name, password)  
    http://localhost:9000/edit-teacher (For edit the teacher's detail like name, password)    

### Folder Structure of Front-End:
    public
       index.html
    src
        action
            index.js
        components
            images
            all_the_components...
        reducer
            index.js
        index.js

### Folder Structure of Back-End:
    models
        add_assignment.js
        student.js
        submitted_assignment.js
        teacher.js
    public
        files
    routes
        index.js
    app.js
