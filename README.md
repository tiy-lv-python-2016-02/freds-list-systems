# Fred's List Final

## Description
This is the last time we will be using Fred's List for class.  This assignment will be to push Fred's List live manually and create a server
with the appropraite systems running to serve the site competely and scalably.

## Learning Objectives
* Basic systems administration
* SSH administration
* Ubuntu package manager
* Deamons and background processes
* Permissions

## Details

### Deliverables
* URL to AWS EC2 server running the Fred's List Service through nginx.

### Normal Mode
* Setup an AWS account
* Setup a micro ec2 instance and be able to ssh into it
* Clone your Fred's List repository to a directory in your home directory
* Make sure it can run in a virtual environment
* Set up the system to run the django server with gunicorn
* Install and configure nginx to run in front of the django server
* You may turn off caching (or set it to dummy caching)

### Hard Mode
* Make the system run on postgresql
* Setup the system to be able to memcached
