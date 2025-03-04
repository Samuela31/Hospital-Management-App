# Hospital Management App

This is a team project done in my 1st year of college as part of our Industrial Revolution 4.0 course. Please view full report [HERE](https://drive.google.com/file/d/1MXGhYqyxQwlb0uEpH0d_UEk1HMxM5CmR/view?usp=sharing). App code and Android Studio project files can be found in the hissss final.zip file. Output screenshots of our Android app can be found in the Progress folder. Media and pictures required for the app are stored in Drawable pics folder. 

## Technology Used/ Required
Android Studio (used Java), Firebase database, Android phone/ emulator

Note: To run the app in your phone, you should enable developer mode in phone settings and then install app from Android Studio by connecting your phone with Android Studio.

## What App is this?
We have created an android application for a hospital to store patient details and patient history, which consists of login page for patients, doctors, admin, registration page for patients, doctors, appointment booking, etc using Android studio. All data is stored in Firebase database.

## Why this App?
- <b>Problem statement:</b> It is a hassle for patients to keep track of their previous doctor visits, previous symptoms and
medications taken. So it difficult for the doctor to diagnosis the patient accurately, hence patient treatment is less efficient. 

- <b>Objective:</b> To easily identify what the patient is suffering from and make accurate diagnosis quickly based on patient history. The doctor does not have to spend time asking how frequent the patient has been experiencing these symptoms, when it happened, what medications were taken, etc. Patient can also book and cancel appointments with ease, and doctors can get a clear view of their schedule. When more patients use this app, the hospital also generates more revenue.

## How Does it Work?
There are 3 types of logins- patient, doctor, and admin. Choose one to get user priviledges and access accordingly. 

- <b>Patients:</b> Patients can book appointments by selecting doctor and the date. They can also see patient history, status of booked appointments, and can cancel appointments. If they cancel appointment, then the doctor will be notified within app. No external email or SMS notifications will be sent.


  <img src="https://github.com/Samuela31/Hospital-Management-App/blob/main/Progress/1661152507194.jpg" alt="Patient sign-in" width="250" height="400"> 
  <img src="https://github.com/Samuela31/Hospital-Management-App/blob/main/Progress/1661152507207.jpg" alt="Patient homepage" width="250" height="400">
  
- <b>Doctors:</b> Doctors can see pending appointments in notification section where they can either reject or accept patient appointments. For this they have to enter email of patient from the displayed list along with date of appointment, and if they accept appointment then they have to enter time of appointment. Then they can press either accept or reject button and the patient will be notified. Doctors can update patient history only for the appointments which he has accepted, and after updating patient history the appointment is considered as finished and will be deleted from the database.

<img src="https://github.com/Samuela31/Hospital-Management-App/blob/main/Progress/1661153514653.jpg" alt="Patient history" width="250" height="400"> <img src="https://github.com/Samuela31/Hospital-Management-App/blob/main/Progress/1661154385132.jpg" alt="Appointments" width="250" height="400">

- <b>Admin:</b> Admin can register new doctors and delete account of users (both patient and doctors). For deleting user, they have to mention if they are patient or doctor, and then enter email of user to be deleted. The list of all users will be displayed and their status- “Patient” or “Doctor” will be mentioned.

## Future Work/ Improvements 
A website can be created for the same, dashboards with useful insights can be included, and payment gateways can be integrated.
