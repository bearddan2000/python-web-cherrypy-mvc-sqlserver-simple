# python-web-cherrypy-mvc-sqlserver-simple

## Description
Simple web app that serves an api
for a cherrypy project.

Uses sqlalchemy query a table `dog`.

## Tech stack
- python
- cherrypy
  - jinja2

## Docker stack
- python
- mcr.microsoft.com/mssql/server:2017-CU17-ubuntu

## To run
`sudo ./install.sh -u`
- [Availble at](http://localhost)

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- [Github sqlalchemy_plugin](https://github.com/ionrock/cherrypy-sqlalchemy/blob/master/example.py)
- [Tutorialpont](https://www.tutorialspoint.com/cherrypy/cherrypy_quick_guide.htm)
- [Jinja example](https://simpletutorials.com/c/cherrypy/anvjhz8q/mvc-with-cherrypy-and-jinja2)
