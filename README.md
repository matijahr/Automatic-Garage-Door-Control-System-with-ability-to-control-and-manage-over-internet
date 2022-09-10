# Garage door
<b>Automatic Garage Door Control System with ability to control and manage over internet</b>

This paper is based on making an automatic garage door system with a human-machine interface. Automatic control system was made using a PLC S7-1513-1 PN and TIA Portal and the code was written in LAD and SCL programming languages.
Also, a human-machine interface was made using Visual Studio Code that enables controlling of the system and is uploaded to the PLC’s web server. Human-machine interface was programmed using HTML, CSS and JS programming languages.
Automatic control system was manually tested with an HMI panel that was made using TIA Portal and the human-machine interface was tested by watching variable response inside data block within TIA Portal.
After testing, some cybersecurity aspects of the system were dealt with using Siemens Security Advisories and a brute force attack was done using Hydra tool.

There are 3 types of users:
Accounts:</br>
_Admin:_
- Username: admin
- Password: Admin1234

_User:_
- Username: user
- Password: 31000

_Everybody:_
- No username or password

The goal of my thesis was to make this system and to test the cybersecurity aspect of the web server that is running on the PLC. 

(documentation available in Croatian)
