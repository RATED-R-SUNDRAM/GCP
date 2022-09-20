# GCP
COLLABORATIVE CODING IDE , SECURED AS EXECUTING CODES IS DONE ON A DEAMON-LESS CONTAINER PODMAN , WITH CHAT AND VIDEO CALL FEATURES.
# Group Coding Project

## ABOUT
This project was intented to bring ease and productivity among multiple users working on the same coding project, We have created a sychronous platform removing redundancy by incorporating OPERATIONAL TRANSROMATION Algorithm allowing multiple users to simulatenously edit and yet maintaing a version which is same across user.
<br/>
<br/>
To further esclate the cohesity among users and to provide scope for real time discussions and communications we have faciliated the users with features such as chats and Video Calls.
<br/>
<br/>
NOTE : This project is yet to be deployed at the moment so please follow the steps in the "HOW TO RUN LOCALLY " section to run it locally on your system.
## Getting Started

### PREREQUISITES TO RUN LOCALLY 
* Python (vesion >=3.5)
* Podman Installed 
* JavaScript libraries such as ( Socket Io , Nodemon, NodeJs)

## HOW TO RUN LOCALLY 
* Clone the repo locally and open in VSCOde or any other IDE.
* run the command npm start ( ENSURE THAT THE PORT WE HAVE ALLOCATED IS FREE ELSE USE A CUSTOM PORT USING npm start <#port> .
* The landing page looks something like this ![img](https://ibb.co/n81W8rF)


## WHERE WE SEE IT'S USE CASES 
* The best use cases for it can be people from an organization or from different backgrounds contributing and collaboarating remotely without the actual need for physical interactions.
* We have tried to provide the real time interaction features like chat and Video Call so that the scope of productive discussion and interaction is always there.
* The safety of clients system is taken care of by running the code snippets on containers and not their actual systems preventing the system from malicious codes.
* Not limited just to a synchronous text editor each user can run the code at any moment he wihses and gets the output on his system.
#### MongoDB

## FURTHER IMPROVEMENTS
The project uses MongoDB as a database. Install [MongoDB](https://docs.mongodb.com/manual/administration/install-community/)

* Foremost deploying this project, which is a big challenge considering the diverse tech stack used.
* Implementing some sort of social media connect features so user can discuss the project beforehand starting it.
* More attractive coding are and code features such as autocomplete snippets, boilerplates etc.
#### Docker

## TECH STACK USED
The project uses Podman containers to run the user provided source files.

* FRONTEND ( HTMl, CSS, JAVASCRIPT) 
* SOCKET IO for synchronous chats and code
* PYTHON 
* PODMAN CONTAINERS
* BASH
* Libraries for OT ( OPERATIONAL TRANSFORMATION)
Make sure that you have docker installed. Run the `createimage.sh` script and it will create a podman image according to the commands given in the `Dockerfile` which will be used to create the podman containers.

## TO KNOW MORE REFER TO THIS [PPT](https://docs.google.com/presentation/d/1swEnctdIqO-o6HL93Xx1libZsJMHsC9bXHB4LE6mqoM/edit?usp=sharing)
### Run the Application

The project is preconfigured with a simple development web server.

The simplest way to start this server is:
`npm start`

- Open [http://localhost:9909](http://localhost:9909/) and take a look around.
