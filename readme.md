<# Compte rendu : Activités 2 / 3 / 4

This project is a web application for managing patient records. It allows users to view, add, update, and delete patient information.

## Interfaces

### Interface 1: Login Page

The login page allows users to log in to the application using their username and password.

![Login Page](/images/Screenshot 2023-04-26 at 22.51.18.png)

### Interface 2: Show All Patients

The "Show All Patients" page displays a list of all patients in the database. Users can view patient details and edit or delete individual records.

![Show All Patients](/images/Screenshot 2023-04-26 at 22.53.28.png)

### Interface 3: Search

The index page also has a search functionnality.

![Show All Patients](/images/Screenshot 2023-04-27 at 00.28.34.png)

### Interface 4: Add a New Patient

The "Add a New Patient" page allows users to add a new patient record to the database.

![Add a New Patient](/images/Screenshot 2023-04-26 at 22.54.30.png)

### Interface 5: Update an Existing Patient

The "Update Patient" page allows users to edit an existing patient record in the database.

![Update an Existing Patient](/images/Screenshot 2023-04-26 at 22.54.10.png)

### Interface 6: Login as normal user

A normal user is not allowed to add , delete or update a patient record.

![Normal user](/images/Screenshot 2023-04-26 at 22.52.18.png)

## Spring Security

### In-memory authentication
<script src="https://gist.github.com/MohamedAmineALLAF/d85497dd7d90282317c5d1955c9db040.js"></script>

### Authentication using JDBC
<script src="https://gist.github.com/MohamedAmineALLAF/468eb9c209a6d033303d9378d195aa18.js"></script>

### Authentication using UserDetailsService 
#### Add users and roles
<script src="https://gist.github.com/MohamedAmineALLAF/8bb272e863b18dd3a06e63fb86e7b237.js"></script>