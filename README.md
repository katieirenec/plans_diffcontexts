# plans_diffcontexts
Experimental ebook for the contexts / plans experiment

## Installation Instructions

#### Prerequisites

If you choose to use an AWS EC2 instance as the server it is recommended to use the free tier eligible Ubuntu Server.
Accept defaults and launch. 

Run `sudo apt-get update` before continuing

`sudo apt-get install python-pip`

`sudo apt-get install libfreetype6-dev`

`sudo apt-get install postgresql-common postgresql postgresql-contrib`

`sudo apt-get install libpq-dev`

`sudo apt-get install libxml2-dev libxslt1-dev`

#### Install web2py

1. Download web2py source code
`wget https://mdipierro.pythonanywhere.com/examples/static/web2py_src.zip`
2. Unzip web2py
`sudo apt-get install unzip`

`unzip web2py_src.zip`

#### Install Runestone Software

1. Install Runestone using

  `pip install runestone`
2. Instal Runestone server by navigating to 'web2py/applications' and running

  `git clone https://github.com/RunestoneInteractive/RunestoneServer.git runestone`
3. Install remaining Runestone requirements by navigating to 'web2py/applications/runestone' and running

  `pip install -r requirements.txt`
4. Install a book by navigating to `web2py/applications/runestone/books` and using git to clone the book code into the directory

#### Setup Postgres Server

1. Give your account permission. <USERNAME> should be equal to the username currently logged in as
  `sudo -i -u postgres`
`postgres@ubuntu:~$ createuser --interactive -P`
  
`$ Enter name of role to add: <USERNAME>`

`$ Enter password for new role: <a password for this user>`

`$ Enter it again: <again>`

`$ Shall the new role be a superuser? (y/n) y`

`$ Password: <password for the default, postgres user>`

2. Create the database 
`createdb runestone --owner=<USERNAME>`
  
  `exit`

3. The connection string for your database will be 'postgresql://username:passwd@localhost/dbname' Remember this

4. Export environment variables

`export WEB2PY_CONFIG=production`

`export WEB2PY_MIGRATE=Yes`

`export DBURL=postgresql://username:passwd@localhost/dbname`

5. Create auth.key file
`mkdir private`

`touch private/auth.key`

6. Initialize Database
`rsmanage initdb`

#### Build Book
Navigate to the `web2py/applications/runestone/books/bookName` and run

`runestone build`

`runestone deploy`






