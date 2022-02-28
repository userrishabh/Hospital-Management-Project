# java-EE-LPU-2022
# hospital-management-system
## Project Discussion
  ~~~~~~~~~~~~~~~~~~

    1. Doctors Patients Queue
       ~~~~~~~~~~~~~~~~~~~~~~
        For a Doctor, patients will walk in and doctor serves them in a Queue 
        i.e. 1st come 1st serve basis -> Problem (As patients they may not agree to this)
        
        Create a Patients Queue i.e. add the patient appointment with date and time in DB
        Doctor will have below options in the web app:
        1. Patients     | CRUD Operations
        2. Appointments | CRUD Operations
        3. List Appointments for the Day i.e. Today and serve them in QUEUE bases
           Doctor will update the status of the appointment as : Seen, Cancelled, Update (to another date/time)
        4. Insights i.e. whenever doctor enters a date, number of seen, cancelled and updated appointments should come as graph (charts.js)   
        5. Tech Stack: Spring Boot, HTML, CSS, JS, Bootstrap/AnyOtherCSSFW, MySQL/MongoDB
