# Overview

This is a project for an imaginary barbershop. Customers are able to view information regarding barbershop on a landing page, they can make or cancel an appointment. Managers of a barbershop are able to view appointments for a day/week, create, read, update or delete them. 
This project consists of 4 separate repositories:

## 1. Landing page
HTML/CSS/JS

[Repo link](https://github.com/Hikyn/barbershop-project-landing)

This is a landing page for customers. They are able to view brand information, see pricelist, view locations of barbershops on google maps, get contact information and barbershop's socials.
## 2. Scheduling appointment (complicated form on React with 5 steps)
HTML/CSS/JS/React
This is a page for making appointments. Users will be navigated through 5 steps of making appointment.
1. Choosing location
2. Selecting services
3. Selecting prefered barber
4. Choosing timeslot
5. Sign up to create appointment
## 3. REST API for CRUD appointments (express.js backend only server with json responses)
Node.js/Express.js/Mongodb/Atlas
1. GET /locations
2. GET /services
3. GET /barbers
---
4. GET /timeslots
5. GET /timeslots/available
---
6. GET /appointments
7. POST /appointments
8. PUT /appointments
9. DELETE /appointments
10. GET /appointments/history
---
11. GET /customers/
12. GET /customers/:userid
13. POST /customers/:userid
14. PUT /customers/:userid
15. DELETE /customers/:userid
## 4. Managing appointments (auth user can check/delete/update appointments)
HTML/CSS/JS/React
Website for managers for overseeing appointments.

1. Overview of today (taken timeslots with **selected services** along with **assigned barbers** and **expected income**)
2. Overview of tommorow (any day)
3. History of previous appointments (can change status of any prev appointment ex. Completed/Pending payement/No show/)
4. Check who made an appointment (user's name, previous appointments, additional manager only comments)
