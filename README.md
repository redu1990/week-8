# week-8
Project 8 - Pentesting Live Targets

Time spent: **9** hours spent in total

> Objective: Identify vulnerabilities in three different versions of the Globitek website: blue, green, and red.

The six possible exploits are:
* Username Enumeration
* Insecure Direct Object Reference (IDOR)
* SQL Injection (SQLi)
* Cross-Site Scripting (XSS)
* Cross-Site Request Forgery (CSRF)
* Session Hijacking/Fixation

Each version of the site has been given two of the six vulnerabilities. (In other words, all six of the exploits should be assignable to one of the sites.)

## Blue

Vulnerability #1: Session Hijacking / Fixation. The session does not expire, which makes it easier for an attacker to steal the session id from an admin and use it to gain access to the admin section of the page.
<img src="https://media.giphy.com/media/9xg7jPmqJ6wsOosNv2/giphy.gif">

Vulnerability #2: Username Enumeration


## Green

Vulnerability #1: Cross-Site Scripting --> If you leave feedback as a user and enter some javascript, the javascript will run when an admin views the feedback.
<img src="https://media.giphy.com/media/nbjegOtbia4sax14Ka/giphy.gif" width="800">

Vulnerability #2: Cross-Site Request Forgery


## Red

Vulnerability #1: Insecure Direct Object Reference --> If you change the id get variable in the URL to 10 or 11 while whithin a salesperson page, the page allows you access salesperson information that is meant to not be public.
<img src="https://media.giphy.com/media/1dLONni9K46KDI6kT1/giphy.gif" width="800">

Vulnerability #2: Sequal Injection


