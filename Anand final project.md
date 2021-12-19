
# Topic: Host a simple website on a Raspberry Pi or Virtualbox using Apache/NGINX 

## Table of Content
* setup an apache server
  * Hardware Requirement
  * Power and connection 
  * setting up  SSH 
  * Updating  Raspberry Pi
  * Installing Apache and PHP 
  * check the apache server 
  * setting up Html page


## Hardware Requirement
* Raspberry Pi
* USB Type-C Cable with power adapter
* PC monitor 
* Micro-SD card with card reader
* Keyboard

## Step1:  Power and connection  
THe first step is to be connect raspberry pi with your monitor. so first step is power your raspberry pi then connect your local wifi with your raspberry pi wifi name and password. 


## Step2: setting up  SSH 
  * once you connected, you need to install putty and enable SSH.  In new raspberry pi they already installed in it. so  you first click the raspberry logo.
  
  *  This logo at the top-left corner. then you click on  Select Preferences  and then click on  Raspberry Pi Configuration.Now, you navigating this window , you find  SSH in the second line. now, you enable the SSH.


   * This SSH client use for the communicate with the raspberry pi .

![Enable SSH](../cis106-fall21/Images/final%20projectssh%20enable%20system.png)

* Now, you need to setup the putty. you need a IP address in the field. so, first you know your raspberry  IP address  by this way:  you can move your mouse  over the  right side   at the top side  network icon. you can look your IP address there.   so, you open putty configuration and enter your IP address in it and select port at "22".   Then click it open the putty will ask a username and password.   
* The default login details for pi  username are "Pi" and password is "raspberry".

![Setup Putty](../cis106-fall21/Images/final%20project%20ssh%20setup.png)

## step 3: Updating  Raspberry Pi


* Before install any software in raspberry pi, we need to update our PI . because    pi will not  disturb when we instal the  apache and php server.  To do that , you updated PI as using terminal by this command:

----
#### sudo apt-get update
----


----
#### sudo apt-get upgrade
----

## step4: Installing Apache and PHP   

To install apache ,you use this command in terminal:

---
#### sudo apt-get install apache2 -y
---



* To check the apache is running: 



---
#### sudo service apache2 status
---

* Now, you install the php server by this command:

---
#### sudo apt-get install apache2 php5 libapache2-mod-php5
---



* For activate the apache server use this command



---
#### sudo service apache2 restart
---


## step 4:  check the apache server 

Open any  Web browser  and search this URL in the address bar:

http:// local host or your ip address 

![Apache Server](../cis106-fall21/Images/apache%20webserver.png)



## step 5: setting up Html  page

find html file by this command:

---
### cd    var/www/html
---

Now, if you want to change or edit the file

---
### sudo chown pi: index.html
---

---
### sudo nano index.html
---


Cited:- 
1. Orsini, Lauren, and Hack. “How to Host a Website with Raspberry Pi.” ReadWrite, 27 Aug. 2018, https://readwrite.com/2014/06/27/raspberry-pi-web-server-website-hosting/. 

2. ago, Lakshan 1 year, et al. “Set up a Raspberry Pi Web Server and Easily Build an HTML Webpage.” Latest Open Tech From Seeed, 23 June 2020, https://www.seeedstudio.com/blog/2020/06/23/setup-a-raspberry-pi-web-server-and-easily-build-an-html-webpage-m/. 











































