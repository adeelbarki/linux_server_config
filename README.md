# Udacity Linux Server Configuration

## Description
This project provides Linux Web Server configuration of Udacity Item Catalog Web Application. This activity is a final part of Udacity Full Stack Web Development Nanodegree Program.

## Resources
Resources used in this project are :
* Application (udacity_item_catalog) developed in python flask
* Amazon lightsail
* Amazon RDS
* Apache2
* Google authentication for login

## Web URL
* IP Address : 52.221.52.10/
* SSH Address : grader@52.221.52.10 -p 2200
* SSH PORT: 2200
* Web Address(URL): http://adeelbarki.com

## Deployment Summary

Softwares installed are apache2 and mod-wsgi in order to run flask application. Configuration file can be found in 

* Apache2 configuration file:
`/etc/apache2/sites-available/udacity_item_catalog.conf`

* Project folder:
`~/udacity_item_catalog`

* WSGI file:
`~/udacity_item_catalog/udacity_item_catalog.wsgi`

* Error logs: 
`/var/log/apache2/error.log`

* To restart server enter command:
`sudo service apache2 restart`

* To check ufw firewall status:
`sudo ufw status` 

## SSH key location
SSH key is provided in "Notes to Reviewer" for logging into account "grader"

## License

Project Item Catalog is a part of Full Stack Web Development Nanodegree Program at [Udactiy](https://www.udacity.com/course/full-stack-web-developer-nanodegree--nd004).

## Author

* Adeel Ahmed Khan (Adeel Barki)
* _Full Stack Web Developer_