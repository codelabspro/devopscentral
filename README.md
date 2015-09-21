DevOpsCentral
=============


DevOpsCentral is built in Grails 2.4.4


Steps

- grails create-app devopscentral

- cd devopscentral

- grails integrate-with --git


- Follow instructions here to setup the database :

https://devcenter.heroku.com/articles/getting-started-with-grails

- Follow instructions here to configure dependencies :

https://devcenter.heroku.com/articles/getting-started-with-grails

- Follow instructions to create heroku app using
heroku create devopscentral

- Configure to use grails wrapper as follows

grails wrapper

- Deploy as follows :

git push heroku master 

This will deploy at

 https://devopscentral.herokuapp.com/



