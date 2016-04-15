*****************************************
FSND P5: Linux-based Server Configuration
*****************************************

Description:
Ubuntu Linux install on an AWS virtual machine to host a previously developed Catalog Flask web app. 


Access to server:
• ssh grader@52.37.166.237 -p 2200 -i ~/.ssh/linuxGrader

URL of hosted app:
http://ec2-52-37-166-237.us-west-2.compute.amazonaws.com/

Private Key for SSH:
See "notes to reviewer" in submission


-------------------------
STEPS TO COMPLETE PROJECT
-------------------------

1. created and launched Virtual Machine on AWS
2. created  new user 'grader' and granted this user sudo permissions
3. updated all currently installed packages
4. configured the local timezone to UTC
5. secured server with SSH port change to 2200 and configured UFW
6. installed and configured Apache to serve a Python mod_wsgi application
7. installed and configured PostgreSQL and confirmed to not allow remote connections
8. created a new user named catalog that has limited permissions catalog application database
9. installed git, cloned and set up Catalog App project


Software installed:
• apache2
• mod_wsgi
• python-setuptools
• git
• python-pip
• virtualenv
• Flask
• httplib2
• requests
• flask-seasurf
• oauth2client
• sqlalchemy
• python-psycopg2
• postgresql 
• postgresql-contrib


Helpful resources used:
• https://discussions.udacity.com/t/markedly-underwhelming-and-potentially-wrong-resource-list-for-p5/8587
• https://discussions.udacity.com/t/project-5-resources/28343
• https://discussions.udacity.com/t/p5-how-i-got-through-it/15342/15
• http://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-tutorials.html
• http://killtheyak.com/use-postgresql-with-django-flask/
• https://github.com/stueken/FSND-P5_Linux-Server-Configuration
• http://stackoverflow.com/questions/27211158/no-passwd-entry-for-user-postgres-error
