# UniSphere - Database Design 

## 1. Introduction 
The UniSphere database will store and organise academic information needed by university students, lecturers and authorised administrators.

## 2. Main Database Entities 

### Students 
Stores basic student account information. 

-Student ID

-Full name 

-Email address

-Department 

-Level 

### Departments 
Stores information about academic departments. 

-Department ID

-Department name 

### Courses 
Stores information about individual courses.

-Course ID

-Course code

-Course title 

-Department 

### Announcements 
Stores academic announcements shared with students.

-Announcement ID

-Title

-Description

-Course

-Date posted

-Posted by 

### Course Materials 
Stores information about learning resources

-Material ID

-Material Title

-Course

-Uploaded by

-Date Uploaded 

## 3. Relationships 
-A department can have many students

-A department can offer many courses

-A course can have many announcements

-A course can have many course materials

-Lecturers and authorised representatives can post announcements 

## 4. Data Security 

-User information should be protected.

-Only authorised users should be allowed to post or edit academic information.

-Passwords should be securely stored.

-Access should depend on user roles.

## 5. Future Database Improvements 

-Assignment submission

-Timetable records 

-Notification records 
