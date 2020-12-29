# reportal
CSE370 Database Project
How to install? Follow below instructions:

1. install python 3.8 64 bit version
2. install git and github desktop
3. install xampp
4. clone the repo from the given link
5. go to cloned repository open powershell by pressing shift+mouse right at the same time
6. install requirements.txt by entering pip install -r requirements.txt, don't close powershell
7. open xampp start apache and mysql
8. from your browser goto localhost/phpmyadmin
9. create new database 370reportal
10. after creating the database, again goto powershell enter python manage.py makemigrations
11. then enter python manage.py migrate
12. if you don't get any error then you are on the right path. Now, again goto powershell and enter python manage.py runserver
