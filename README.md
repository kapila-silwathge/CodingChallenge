CodingChallenge
===============

This create a one page web application displaying a short list of school results in tabular form filtered by either:

● Numeracy, Spelling or Reading

Filter is applied by selecting from a combobox list, resulting in a change of table content

##Technologies used

● Java - Yes

● Javascript- Yes

● Javascript MV* Framework e.g. Backbone - Yes

● JSON- Yes

● Bootstrap- Yes

● RESTful- Yes

● MongoDB- Yes

● Maven- Yes

● GIT- Yes

● JBoss AS 7- Yes


##To build
you need to have maven installed

run "mvn package" from the folder where pom.xml exsits.

It creates folder "target" and it will have "codingchallenge.war" in it among others.

##To Run
###Dependancy

####1.MongoDB

Download and install MongoDB

Import  school.json included with this to mongodb

database= codec

collection =school


Command

mongoimport --db codec --collection school --file school.json  --jsonArray

####2.Internet Connection

Internet connection is required while running the applicaton as application uses CDN to download some .js and .css files.

###Deploy and run

This was developed and tested  on JBoss AS 7.0.1 running standalone mode.you can coply the created .war file to <JbossHOME>/standalone/deployments folder and start the server.

After .war is deployed open a browser and type

http://localhost:8080/codingchallenge

note: all simple ”codingchallenge”

##Eclipse IDE Support

To convert the Maven web project to support Eclipse IDE, in terminal, navigate to “CodingChallenge” folder, issue this command :

mvn eclipse:eclipse -Dwtpversion=2.0




~Kapila Silwathge
