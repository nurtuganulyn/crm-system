# Customer Realationshion Managment System

# Overview

This project is a small task management.
It was built using Django and DRF and contains the following:

* Allows new accounts registration, login and logout.
* token-based authentication system.
* Each user can create edit delete any of his task.
* Each user can filter through his tasks.
* Make analysis and take statistics

#### Opertions and Postman requests.

* [Authentication](#auth)
  * Signup ```127.0.0.1:8000/accounts/register/```
  * Take Token ```127.0.0.1:8000/accounts/login/```
  
* [CRUD Operations](#crud)
  * All Tasks ```127.0.0.1:8000/me/all/```
  * Create Task ```127.0.0.1:8000/tasks/```
  * Task Detail ```127.0.0.1:8000/tasks/id/``` 
  * Update Task ```127.0.0.1:8000/tasks/id/```
  * Delete Task ```127.0.0.1:8000/tasks/id/```

* [Filter Tasks](#filter)
  * All Completed Tasks ```127.0.0.1:8000/me/completed/```
  * All Incompleted Tasks ```127.0.0.1:8000/me/incompleted/```
  

* [Export Data](#crud)
  * Export as CSV ```127.0.0.1:8000/export/csv/```
  
