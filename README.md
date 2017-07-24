# Udacity Server Config Project
- IP address: 54.153.239.65
- SSH port: 2200
- URL: http://54.153.239.65/
## Installed Software
- Python3
- Python Virtualenv
- Apache2
- Apache mod WSGI
- Postgresql
## Configuration Changes
1. Add SSH key for 'ubuntu' user
1. Disallow password login
1. Disallow root login
1. Create user 'grader'
1. Give 'grader' sudo privelages
1. Add SSH key for grader
1. Remove remote login from Postgres
1. Create user 'catalog'
1. Create db role 'catalog' with low privileges
1. Create database 'catalog'
1. Clone app into /home/catalog
1. Change app config to use postgres
1. Run app scripts to generate key and populate db
1. Create app WSGI script
1. Pip install app requirements in virtualenv
1. Edit Apache config to use wsgi script
## Resources Used
- http://modwsgi.readthedocs.io/en/develop/
- http://flask.pocoo.org/docs/0.12/deploying/mod_wsgi/
- https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps
- https://wiki.apache.org/httpd/ClientDeniedByServerConfiguration
