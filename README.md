# LinuxConfigProject
Amazon LightSail Linux Server Configuration Project


I. IP Address and Port of Server:
Static IP:  35.176.175.194
Port:       2200

II. Hosted Item Catalog Application URI:
http://35.176.175.194.xip.io

III. Server Configurations
The Amazon hosted server referenced in this readme file accepts:
SSH connections via port 2200 
HTTP connections via port 80
the OS is Ubuntu 16.04
Server timezone setting is configured to Coordinated Universal Time (UTC)
Server language is english
SSH logon is only permitted via public-private keypair, password logon is not enabled
2 users setup ubuntu(default/sudoer)
              grader(sudoer)
Root logon is disabled
Configured to serve webpages from /var/html/apache2 folder 
virtual environment venv is set up and configured to serve 
Flask applications from /var/www/PythonPredix/PythonPredix folder 


IV. Software Stack:
Operating System:   Ubuntu@16.04
Web server:         Apache@2.4.18 
Apache Module:      libapache2-mod-wsgi@4.3.0-1.1build1
Python compiler:    python@2.7.12
package installer:  pip@9.0.3 - latest supported version for cloudfoundry python buildpack
Database Management Systems:
                    postgresql@9.5
                    sqlite@3.11
Version Control:    git@2.7.4


V. Resources 
Amazon LightSail Server
Cloudfoundry Python Buildpack
Google OAuth2 service  

VI. Version 
1.1 - 12/04/2018
