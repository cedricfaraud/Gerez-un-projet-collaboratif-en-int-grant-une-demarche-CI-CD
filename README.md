# BobApp

Clone project:

> git clone https://github.com/cedricfaraud/Gerez-un-projet-collaboratif-en-int-grant-une-demarche-CI-CD.git

## Front-end 

Go inside folder the front folder:

> cd front

Install dependencies:

> npm install

Launch Front-end:

> npm run start;

### Docker

Build the container:

> docker build -t cfaraud/frontend .  

Start the container:

> docker run -p 80:80 --name frontend -d cfaraud/frontend

## Back-end

Go inside folder the back folder:

> cd back

Install dependencies:

> mvn clean install

Launch Back-end:

>  mvn spring-boot:run

Launch the tests:

> mvn clean install

### Docker

Build the container:

> docker build -t cfaraud/backend .  

Start the container:

> docker run -p 8080:8080 --name backend -d cfaraud/backend 
