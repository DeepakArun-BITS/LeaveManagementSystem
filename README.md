# Leave Management System
## Simple Application For Managing Employee Leaves.

### Description
Leave Management System is a web application for managing employee leaves. This application provides all the things that a project/team needs. Through this application one can easily manage leaves. Application maintenance is easy.

### Requirements
* Java 7 or higher.
* Maven
* Postgres Database
* Run on Tomcat 7 (you can run on later versions)

### How To Run
* As it's a Maven Project, you can call `mvn install` in terminal(in project directory) to get a war file.(You can find it in **target** folder)
* You need to have Postgres database to import tables from app-DB-Script.sql (`psql -U postgres lms < app-DB-Script.sql`).
* Default username is `manager@email.com` and password is `123456`.
* You can find the file **app-DB-Script.sql**  in **resources** folder.
* Deploy the war file to the tomcat server and visit localhost:8080/leave-management-system

## Application Overview
### Login Page (Initial Opening Page)
![Login Page](https://github.com/DeepakArun-BITS/LeaveManagementSystem/blob/master/resources/screenshots/HomePage_CheckPassword.PNG)

### Home Page (Options provided for data variation)
![Home Page](https://github.com/DeepakArun-BITS/LeaveManagementSystem/blob/master/resources/screenshots/HomePage_CheckPassword.PNG)

![Home Page](https://github.com/DeepakArun-BITS/LeaveManagementSystem/blob/master/resources/screenshots/ChangePassword.PNG)

![Home Page](https://github.com/DeepakArun-BITS/LeaveManagementSystem/blob/master/resources/screenshots/HomePage_CheckPassword.PNG)

![Home Page](https://github.com/DeepakArun-BITS/LeaveManagementSystem/blob/master/resources/screenshots/HomePage_TeamLead.PNG)

### Manage Users
![Manage Users](https://github.com/DeepakArun-BITS/LeaveManagementSystem/blob/master/resources/screenshots/ManageUsers.PNG)

### Edit User
![Edit User](https://github.com/DeepakArun-BITS/LeaveManagementSystem/blob/master/resources/screenshots/EditUser_Manager.PNG)

### Manage Leaves
![Manage Leaves](https://github.com/DeepakArun-BITS/LeaveManagementSystem/blob/master/resources/screenshots/ManageLeaves_Manager.PNG)

### Apply Leave
![Apply Leave](https://github.com/DeepakArun-BITS/LeaveManagementSystem/blob/master/resources/screenshots/ApplyLeave_Fields.PNG)

### My Leaves
![My Leaves](https://github.com/DeepakArun-BITS/LeaveManagementSystem/blob/master/resources/screenshots/MyLeaves_Manager.PNG)
![My Leaves](https://github.com/DeepakArun-BITS/LeaveManagementSystem/blob/master/resources/screenshots/MyLeaves_TL.PNG)

### Change Password
![Change Password](https://github.com/DeepakArun-BITS/LeaveManagementSystem/blob/master/resources/screenshots/ChangePassword.PNG)

