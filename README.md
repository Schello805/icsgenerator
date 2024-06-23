First Software I have ever build. This ICS Generator is a stand alone Software written in Javascript, HTML and CSS to create an *.ics file with one or more events.<br><br>

<img width="897" alt="Screenshot ICS Gernerator" src="https://github.com/Schello805/icsgenerator/assets/28543330/7f7b0831-2808-4dc3-b668-09187d6c39b9">
<br>
<br>
To install the Software, you can use a webserver you want to.<br>
<br>
I use Ubuntu 22.04 with the following commands:<br>
<br>
apt update && apt upgrade<br>
apt install apache2 git<br>
Clone this repository with at /var/www/<br>
git clone https://github.com/Schello805/icsgenerator.git<br>
edit the apache2 conf file (/etc/apache2/sites-enabled/000-default.conf) use as root path the place you clone the respositroy (in this example /var/www/icsgenerator)
<br>
open the IP-adress of the webserver at port 80

