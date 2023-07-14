# Overview

This is a project for an imaginary barbershop. Customers are able to view information regarding barbershop on a landing page, they can make or cancel an appointment. Managers of a barbershop are able to view appointments for a day/week, create, read, update or delete them. 
This project consists of 4 separate repositories:

## 1. Landing page
HTML/CSS/JS

This is a landing page for customers. They are able to view brand information, see pricelist, view locations of barbershops on google maps, get contact information and barbershop's socials.

[Repo link](https://github.com/Hikyn/barbershop-project-landing)
## 2. Scheduling appointment (complicated form on React with 5 steps)
HTML/CSS/TS/React
This is a page for making appointments. Users will be navigated through 5 steps of making appointment, receiving data on the fly via my REST API.
1. Choosing location
2. Selecting services
3. Selecting prefered barber
4. Choosing timeslot
5. Sign up to create appointment

[Repo link](https://github.com/Hikyn/barbershop-project-form)
## 3. REST API for CRUD appointments (express.js backend only server with json responses)
Node.js/Express.js/Mongodb/Atlas

1. GET /services
---
2. GET /barbers
3. GET /barbers/:barberId
4. GET /barbers/:barberId/working_hours
5. GET /barbers/:barberId/working_hours/:day
6. GET /barbers/:barberId/appointments
7. GET /barbers/:barberId/timeslots/:day/:month/:year
---
8. GET /barbershops
9. GET /barbershops/:barbershopId
10. GET /barbershops/:barbershopId/barbers
---
11. GET /appointments
12. POST /appointments
13. GET /appointments/:appointmentId
14. PUT /appointments/:appointmentId
15. DELETE /appointments/:appointmentId
---
16. GET /customers/
17. GET /customers/:userid
18. POST /customers/:userid
19. PUT /customers/:userid
20. DELETE /customers/:userid

[Repo link](https://github.com/Hikyn/barbershop-project-backend/)
## 4. Managing appointments (auth user can check/delete/update appointments)
HTML/CSS/JS/React
Website for managers for overseeing appointments.

1. Overview of today (taken timeslots with **selected services** along with **assigned barbers** and **expected income**)
2. Overview of tommorow (any day)
3. History of previous appointments (can change status of any prev appointment ex. Completed/Pending payement/No show/)
4. Check who made an appointment (user's name, previous appointments, additional manager only comments)
