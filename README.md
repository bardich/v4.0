<h1>GOautodial Open source Multi-channel Contact Center Application</h1>

The GOautodial CE Application (also called "GOautodial app") is the next generation open source omni-channel web based contact center application.

Rewritten from ground up using the following standards and technologies:

Bootstrap 3<br>
WebRTC<br>
HTML5<br>
PHP7<br>
JQuery<br>
REST API<br>

Major Features:

Multi-channel contact center application (voice and non-voice)
Predictive dialer + Inbound IVR and ACD
Ticketing system (under development)
Live chat
SMS (under development)
Fax (under development)
Email
Social media (under development)
CRM type application
Responsive design supporting major web browsers
Modular API and plugin based system
Reports and analytics
Multi-language

To install (assumming your document root directory is /var/www/html):

cd /var/www<br>
git clone https://github.com/goautodial/v4.0 html

Edit the 3 configuration files (inside /var/www/html/):

1. astguiclient.conf 
2. php/Config.php
3. php/goCRMAPISettings.php

Replace the default database name, users and passwords according to your preference.


