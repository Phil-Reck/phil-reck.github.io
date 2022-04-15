---
layout: project
type: project
image: images/kabu-timetabling.png
title: Kabarak University Timetabling
permalink: projects/timetabling
# All dates must be YYYY-MM-DD format!
date: 2022-01-01
labels:
  - Laravel
  - SQL
  - Websockets
  - jQuery
summary: The system is built for a University based setup for the generation of a semeter
---

<div class="ui small rounded images">
  <img class="ui image" src="../images/schools.png">
  <img class="ui image" src="../images/timetable.png">
</div>

The project is built with Laravel with AdminLTE for the frontside templating.

The system is built for Kabarak University and/or for any University based setup for the generation of a semeter long timetable based on parameters such as the Venue classes will be taking place, the School and Department under which Diploma and Degree Programs belong to, the Units each Program has, the time allocation for each Unit and the Room and Laboratory each unit will be taking place at for a given period of the week.
The system then generates a timetable, which factors in the number of days classes are carried out within the institution, the cohort that are doing that semester and leaves the ones on break.

For this project, I took part in the implementation of the CRUD functionality, development of new features, refactoring for speed & memory efficiency, setup of a linux based server environment on Digital Ocean, debugging  and performing tests for current and newly developed features.

The system implements some awesome laravel features; websockets, authentication of users based on roles, events, jobs and listeners, queues and jobs of the generation of the timetable.





