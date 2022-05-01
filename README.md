
# Hospital Management 

HMS is a multi featured web application, developed in django which contains three major modules 
1. Admin
2. Doctor
3. Patient
where a patient can book his/her appoinment with respective specialised doctors, and accordingly doctors can generate the invoice of the detailed charges related to the patient, and entire system is being managed by admin.




## Features

- COVID assistance facility
- Doctors And Patient requires  the aprroval from admin to get procced into the dashboard.
- Patient can book the appointment with the respective specialised doctor.
- Admin is responsible to discharge the patient.
- Invoice Generation with detailed charges and facility used.



## Functions
### Admin
- Signup their account. Then Login (No approval Required).
- Can register/view/approve/reject/delete doctor (approve those doctor who applied for job in their hospital).
- Can admit/view/approve/reject/discharge patient (discharge patient when treatment is done).
- Can Generate/Download Invoice pdf (Generate Invoice according to medicine cost, room charge, doctor charge and other charge).
- Can view/book/approve Appointment (approve those appointments which is requested by patient).

### Doctor
- Apply for job in hospital. Then Login (Approval required by hospital admin, Then only doctor can login).
- Can only view their patient details (symptoms, name, mobile ) assigned to that doctor by admin.
- Can view their discharged(by admin) patient list.
- Can view their Appointments, booked by admin.
- Can delete their Appointment, when doctor attended their appointment.

### Patient
- Create account for admit in hospital. Then Login (Approval required by hospital admin, Then only patient can login).
- Can view assigned doctor's details like ( specialization, mobile, address).
- Can view their booked appointment status (pending/confirmed by admin).
- Can book appointments.(approval required by admin)
- Can view/download Invoice pdf (Only when that patient is discharged by admin).


## TechStack

- Django
- HTML
- CSS
- Bootstrap
- SQlite


## WorkFlow
https://whimsical.com/getting-started-boards-6EqUSPBWmUgH6WELLzHWXs


## HOW TO RUN THIS PROJECT

- Install Python(3.7.6) (Dont Forget to Tick Add to Path while installing Python)
- Open Terminal and Execute Following Commands :

```
pip install django==3.0.5
pip install django-widget-tweaks
pip install xhtml2pdf
```

- Download This Project Zip Folder and Extract it
- Move to project folder in Terminal. Then run following Commands :
```
py manage.py makemigrations
py manage.py migrate
py manage.py runserver
```
- Now enter following URL in Your Browser Installed On Your Pc
```
http://127.0.0.1:8000/
```


## Screenshots

### Homepage
![homepage snap](https://github.com/d3adsh0t1/Capstone_HMS/blob/0ac90e1353cafaa4ea3ad5b0c73241521416ade3/static/screenshots/Homepage.png)
### Admin Login/Signup
![homepage snap](https://github.com/d3adsh0t1/Capstone_HMS/blob/0ac90e1353cafaa4ea3ad5b0c73241521416ade3/static/screenshots/Admin%20Login.png)
### Admin Dashboard
![dashboard snap](https://github.com/d3adsh0t1/Capstone_HMS/blob/0ac90e1353cafaa4ea3ad5b0c73241521416ade3/static/screenshots/Admin%20Dashboard.png)
### Admin Approval Page
![homepage snap](https://github.com/d3adsh0t1/Capstone_HMS/blob/0ac90e1353cafaa4ea3ad5b0c73241521416ade3/static/screenshots/admin%20approving%20patient.png)
### Invoice
![invoice snap](https://github.com/d3adsh0t1/Capstone_HMS/blob/0ac90e1353cafaa4ea3ad5b0c73241521416ade3/static/screenshots/Invoice%20admin.png)
### Doctor Dashboard
![d_dashboard snap](https://github.com/d3adsh0t1/Capstone_HMS/blob/0ac90e1353cafaa4ea3ad5b0c73241521416ade3/static/screenshots/Doctor%20Dashboard.png)
### Patient Dashboard
![p_dashboard snap](https://github.com/d3adsh0t1/Capstone_HMS/blob/0ac90e1353cafaa4ea3ad5b0c73241521416ade3/static/screenshots/Patient%20Dashboard.png)
### Book Appointment
![appointmentsnap](https://github.com/d3adsh0t1/Capstone_HMS/blob/0ac90e1353cafaa4ea3ad5b0c73241521416ade3/static/screenshots/Patient%20Book%20appointment.png)
