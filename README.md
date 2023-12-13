# Vzeeta API:
.NET Core Web API project simulating vzeeta.com. It's designed with onion architecture, ensuring adherence to clean code principles and SOLID design.
The API supports three roles: admin, doctor, and patient, each of them with specific Features.
API secured using JWT Authentication
API Provides Sending Emails Using Gmail
# Features:
## Admin Role Features:
### Admin Dashboard:-
- Dashboard with statistics (number of Doctors, Patients, Requests(Completed, Pending, Cancelled)).
- Top 5 Specializations based on number of completed requests.
- Top 10 Doctors based on the number of their Requests.
### Registered Doctors Accounts:-
- CRUD opertions of doctors.
- Sending email to doctor's email with it's email/userName & password so he can login and use Application.
### Discount Codes Coupons Management:-
- Add Discount codes and specify number of completed requests that user must make them to use code.
- CRUD opertions of discount code.
- Can Deactivate code.
## Doctor Role Features:
- Login and view it's all bookings.
### Add it's Appointments:-
- CRUD opertions of Appointments.
### Confirm Checkups
## Patient Role Feature:
- Register and login
- Search for doctors and booking appointments
- Cancel booking request
- View personal booking history
#Project ERD
![Screenshot (217)](https://github.com/wejdangamal/Vzeeta_API/assets/73383355/1556932b-20d7-4cf0-aa05-8d7dc7d39738)

