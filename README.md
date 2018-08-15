RESOURCES
=========

The web search has been done using: https://www.google.com.eg/ (this URL was copied from Google Chrome browser(https://www.google.com/chrome/)).

I used Google Chrome browser (https://www.google.com/chrome/) to work on this project.

I used git(https://git-scm.com/) to work on this project.

https://www.digitalocean.com/docs/droplets/how-to/add-ssh-keys/

https://www.digitalocean.com/docs/droplets/how-to/add-ssh-keys/create-with-openssh/

https://www.digitalocean.com/docs/droplets/how-to/add-ssh-keys/to-account/

https://www.debian.org/devel/passwordlessssh

https://www.digitalocean.com/community/questions/how-to-find-the-login-info-for-my-droplet

https://www.youtube.com/watch?v=BUasdmczmMw

https://www.digitalocean.com/community/tutorials/how-to-install-and-use-postgresql-on-ubuntu-16-04

https://serverfault.com/a/254706 by: HUB.

https://askubuntu.com/a/424039 by: Maythux.

https://www.digitalocean.com/community/questions/how-to-log-in-as-non-root-user-via-ssh

https://www.digitalocean.com/community/questions/secure-ubuntu-server-for-non-root-user-using-only-ssh-keys?answer=22286

https://askubuntu.com/a/695704 by: Neil.

https://mediatemple.net/community/products/dv/204643810/how-do-i-disable-ssh-login-for-the-root-user

https://www.cyberciti.biz/faq/howto-start-stop-ssh-server/

https://www.digitalocean.com/community/questions/ssh-port

https://www.digitalocean.com/community/tutorials/initial-server-setup-with-ubuntu-18-04

https://www.digitalocean.com/community/tutorials/initial-server-setup-with-ubuntu-16-04

https://www.digitalocean.com/community/tutorials/initial-server-setup-with-ubuntu-12-04

https://www.digitalocean.com/community/tutorials/how-to-install-linux-apache-mysql-php-lamp-stack-on-ubuntu

https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps

https://github.com/ahmedsameha1/item_catalog

https://stackoverflow.com/a/11919677 by: Erwin Brandstetter

https://www.postgresql.org/docs/8.1/static/sql-alterrole.html

https://www.postgresql.org/docs/8.1/static/sql-createrole.html

https://www.digitalocean.com/community/tutorials/how-to-install-and-use-postgresql-on-ubuntu-16-04

https://askubuntu.com/questions/14763/where-are-the-apache-and-php-log-files

https://www.youtube.com/watch?v=bMEAtCuFoiw

https://askubuntu.com/a/14767 by: misterben

https://www.postgresql.org/docs/8.1/static/tutorial-accessdb.html

https://github.com/aviaryan/flask-postgres-apache-server

https://stackoverflow.com/a/42587012 by: andrew

https://github.com/ahmedsameha1/item_catalog

https://stackoverflow.com/a/7858570 by: kubal5003

https://github.com/aviaryan/ud-catalog/blob/master/catalog/__init__.py

https://github.com/singingwolfboy/flask-dance/issues/35

https://stackoverflow.com/questions/26400776/circumstances-of-the-invalid-grant-error-when-refreshing-an-access-token

https://stackoverflow.com/q/41793588 by: Nick Slavsky

http://flask-dance.readthedocs.io/en/latest/quickstarts/google.html

The contents of the file item_catalog.conf was copied from: https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps. Then I made some changes to make the contents fit my needs.

The contents of the file item_catalog.wsgi was copied from: https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps. Then I made some changes to make the contents fit my needs.

The virtual Linux server is provided by: https://www.digitalocean.com/

INSTALLED SOFTWARE
==================

postgresql

postgresql-contrib

apache2

libapache2-mod-wsgi

python-dev

python-pip

virtualenv

Flask

flask-sqlalchemy

flask-login

flask-marshmallow

marshmallow-sqlalchemy

flask-dance

blinker

flask-dance[sqla]

psycopg2 (got this from an error that was produced by python)

IP ADDRESS
==========

142.93.80.234 ( was copied from: https://cloud.digitalocean.com/projects/30473446-650b-4a9b-abae-c2b9cf8d6870/resources?i=a11aef)

The URL is: www.142.93.80.234.xip.io

CONFIGURATIONS
==============

Update the software of the virtual server.

Install apache2 web server.

Delete /var/www/html directory.

Install postgresql database.

Add the grader user.

Add the grader user to the sudo group.

Allow the grader user to connect with the ssh key.

Disable login using passwords.

Disable login using root.

Install the software to run the project.

Enable the site on apache2 web server

Add the file item_catalog.conf

Add the file item_catalog.wsgi

Restart the apache2 web server
