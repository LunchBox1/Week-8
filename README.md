# Project 8 - Pentesting Live Targets

Time spent: **10** hours spent in total

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

Vulnerability #1: SQL Injection 

<img src="https://github.com/LunchBox1/Week-8/blob/master/SQLi.gif" width="800">

Vulnerability #2: Session Hijacking 

<img src="https://github.com/LunchBox1/Week-8/blob/master/Session%20Hijacking.gif" width="800">


## Green

Vulnerability #1: Username Enumeration 

<img src="https://github.com/LunchBox1/Week-8/blob/master/User%20Enumeration.gif" width="800">

Vulnerability #2: Cross-Site Scripting 

<img src="https://github.com/LunchBox1/Week-8/blob/master/XSS.gif" width="800">


## Red

Vulnerability #1: Insecure Direct Object Reference 

<img src="https://github.com/LunchBox1/Week-8/blob/master/IDOR.gif" width="800">

Vulnerability #2: Cross-Site Request Forgery


## Notes

The first challenge was encountered during username enumeration challege. The thing that gave away an existing username was easy to miss. It took me a while before I noticed the enumeration. 
The second challenge was encountered during SQLi. It was hard to figure out where to perform the injection. What eventually gave away that the SQL had to be injected into the URL was SQLmap. 
The final challenge, and the challenge that I was not able to overcome, was in the cross-site request forgery challenge. Although many times I believed to have figured the challenge, at the very end it proved to be false. My biggest issue with that challenge is that I did not completely understand the challenge. I determined that the red version of the site contained the CSRF by using process of elimination.
