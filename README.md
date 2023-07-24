# Overview

This is a project for an imaginary barbershop. Customers are able to view information regarding barbershop on a landing page, they can make an appointment.
This project consists of 4 separate repositories:

## 1. Landing page
<a href="https://en.wikipedia.org/wiki/HTML5">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
</a>

<a href="https://en.wikipedia.org/wiki/CSS">
  <img src="https://img.shields.io/badge/CSS-239120?&style=for-the-badge&logo=css3&logoColor=white" />
</a>

<a href="https://de.wikipedia.org/wiki/JavaScript">
  <img src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=yellow" />
</a>

This is a landing page for customers. They are able to view brand information, see pricelist, view locations of barbershops on google maps, get contact information and barbershop's socials.

[Repo link](https://github.com/Hikyn/barbershop-project-landing)
## 2. Scheduling appointment (complicated form on React with 5 steps)
<a href="https://www.typescriptlang.org/">
  <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" />
</a>

<a href="https://reactjs.org/">
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
</a>

<a href="https://en.wikipedia.org/wiki/HTML5">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
</a>

<a href="https://en.wikipedia.org/wiki/CSS">
  <img src="https://img.shields.io/badge/CSS-239120?&style=for-the-badge&logo=css3&logoColor=white" />
</a>

Streamlined 5-step form with Typescript and React hooks for enhanced user interactions.

Users will be navigated through 5 steps of making appointment, receiving data on the fly via my REST API.

1. Choosing location
2. Selecting services
3. Selecting prefered barber
4. Choosing timeslot
5. Filling contact information to create an appointment

[Repo link](https://github.com/Hikyn/barbershop-project-form)
## 3. REST API for CRUD appointments (express.js)

<a href="https://expressjs.com/">
  <img src="https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB" />
</a>

<a href="https://de.wikipedia.org/wiki/JavaScript">
  <img src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=yellow" />
</a>

<a href="https://nodejs.org/">
  <img src="https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white" />
</a>

<a href="https://www.mongodb.com/">
  <img src="https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white" />
</a>

<a href="https://www.mongodb.com/atlas">
  <img src="https://img.shields.io/badge/Atlas-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white" />
</a>

20+ routes to cover all application needs. Mainly used by #2 - React form for appointments.

[Repo link](https://github.com/Hikyn/barbershop-project-backend/)

## 4. Managing appointments
<b>Work in Progress</b>

<a href="https://de.wikipedia.org/wiki/JavaScript">
  <img src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=yellow" />
</a>

<a href="https://reactjs.org/">
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
</a>

<a href="https://en.wikipedia.org/wiki/HTML5">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
</a>

<a href="https://en.wikipedia.org/wiki/CSS">
  <img src="https://img.shields.io/badge/CSS-239120?&style=for-the-badge&logo=css3&logoColor=white" />
</a>

Website for managers for overseeing appointments.

1. Overview of today (taken timeslots with **selected services** along with **assigned barbers** and **expected income**)
2. Overview of tommorow (any day)
3. History of previous appointments (can change status of any prev appointment ex. Completed/Pending payement/No show/)
4. Check who made an appointment (user's name, previous appointments, additional manager only comments)
