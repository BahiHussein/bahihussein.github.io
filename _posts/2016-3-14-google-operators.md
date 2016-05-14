---
layout: post
title: Google Operators
---

##Basic Operators (+,-,~,.,"",OR)

Google ignore common words like (where, how, digits and single letters).
for example: how to make money == make money
1. (+) force inclusion of something common
    apple != apple + red (more specific)
2. (-) force exclusion of something 
    apple - red, exclude red apples from apples
3. "" search  for exact phrase
    example: "angry orange"
4. OR
5. (.) concatenate 

index.of.dcim
index.of.dcim private
index.of.private
index.of.password
index.of.backup
index.of.mp3

##Advanced Operators 

//searching for exact site
site:yoururl.com

//sites contains admin in their url 
inurl:admin
inurl:login
inurl:admin login
inurl:admin.php
inurl:exam site:yourclgsite.com

//contains word in their title
intitle:hacking

//search for specific file type
filetype:txt or xls or .doc

define: "hacking"
phonebook:
link: kratikal.in
related: kratikal.in
info: kratikal.in

filetype:txt username password @gmail.com
filetype:xls username password @gmail.com
filetype:xls username password @facebook.com
filetype:xls username password paypal
filetype:xls username password facebook

//hacking printer
inurl:webarch/mainframe.cgi

//hacking power
intitle:mutlimon ups status page

//hacking routers
intitle: speedstream router management interface
intitle: vnc viewer from java
intitle: "sipura.spa.configration" -.pdf 


//Webcams 
inurl:main.cgi linksys
inurl:viewerframe?mode=motion
inurl:view/index.shtml
intitle:"Toshiba Network Camera" User Login
intitle:"EvoCam" inurl:"Webcam.Html"
inurl:/view.shtml
inurl:indexFrame.shtml Axis

//directory listing vulnerabilities 
site:kratikal.in intitle:index.of

//sql injection vulnerabilitiy
inurl:.php?id=

//search for configuration files
site:mnnit.ac.in ext:xml | ext:conf |
ext:cnf | ext:reg | ext:inf | ext:rdp | 
ext:cfg | ext:txt | ext:ora | ext:ini


//hacking agencies 
intext: classified top secret site:nsa.gov


