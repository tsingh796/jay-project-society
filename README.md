# Project DjangoSociety

## What is it
	DjangoSociety contains details of the members, groups and events in the society. You can
	add new members, groups and events and manage/modify the existing ones.

## Society App Details
	Society app has three models: People, Event and Group
#### People
	People model saves info about each individual person in the society like
	his/her name, username, date of birth etc.
#### Event
	Event model saves info about any event being conducted in the society
#### Group
	Groups are created for people with common interests to keep together.

## How to run this project
* Open CommandPrompt, cd to folder which contains virtualenv
* Open virtualenv using command $<env_name>\Scripts\activate
* cd to folder which contains the Project Folder
* run the project using command $python manage.py runserver
* log onto any webserver and go to site http://localhost:8000/society 
* On this homepage you can see/add new Event, Group or People by clicking respective buttons

## What versions were used to create it
|Package|Version|
|-------|-------|
|appdirs|1.4.4|
|asgiref|3.4.1|
|distlib|0.3.2|
|Django|3.2.5|
|filelock|3.0.12|
|pip|21.1.3|
|pytz|2021.1|
|setuptools|56.0.0|
|six|1.16.0|
|sqlparse|0.4.1|
|virtualenv|20.4.7|
|python|3.9.6|


## What was learned while working on this project
* How to route the urls to proper page according to need. Also it was made clear how this routing can 
 be used to link the back buttons to homepage.
* Learned to code html to improve view of the page using style and tables. Using buttons and links.
* How to use the same html format to create multiple pages to keep the styling uniform.
* To find out an error looking at the error types in cmd and checking in the file which gave the error. 
* How to check version of different packages of the virtualenv 