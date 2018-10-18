# CodePathWeek8
# Project 8 - Pentesting Live Targets

Time spent: **X** hours spent in total

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

Vulnerability #1: Session Hijacking/Fixation
<img src="BlueVulnerabilty1.gif" width=800>

Vulnerability #2: __________________


## Green

Vulnerability #1: Username Enumeration <br>
When a valid username is entered the error that is displayed is in bold. When a username that is not valid is entered the error that is displayed is not in bold.
<img src="GreenVulnerability1.gif" width=800>

Vulnerability #2: XSS 
Feedback form doesn't sanitize HTML elements
<img src="GreenVulnerability2.gif" width=800>


## Red

Vulnerability #1: IDOR
You are able to see hidden salespeople (Ones who might have been let go for one reason or another...)
The other two sites prevented this from occuring by redirecting the user to another page when they were not logged in as an admin and attempted to view the hidden users.
<img src='RedVulnerability1.gif' width=800>

Vulnerability #2: CSRF
Using the CSRF token taken from the form element you can update the values on the site without being logged in
<img src="RedVulnerability2.gif" width=800>


## Notes

Describe any challenges encountered while doing the work

