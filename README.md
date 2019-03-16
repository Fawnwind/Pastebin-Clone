# Pastebin-Clone  
Liam Crozier  
For Secure Software Development  

Project Framework is Django  
Dependencies:  
Pip  
Python  
Django (2.1 or higher)  
Django-crispy-forms  
Django-dbbackup  
Pillow  

Site Database is backed up using Django-dbaackup in /backup.  
Site profile images are stored in /media  
User app is stored in /users  
Paste app is stored in /paste  
/django_project contains main settings and url files  
Screenshots of site can be found in Images Document.docx   
Passwords are salted and hashed in database using django database  
CSRF tokens are implamented to increase security  
Data is sanatized and validated before input into database using django .is_valid() function  
Bootstrap is used for appealing visual design  
Posts have titles and author names displayed  
Admin interface is only accessable with an admin account (found at localhost:8000/admin)  
