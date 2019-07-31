# Framework for running a webserver with httpd docker image

## Run the commands to build and run the Docker image:
```bash
$ docker build -t my-apache2 .
$ docker run -dit --name my-running-app -p 8080:80 my-apache2
```
Visit http://localhost:8080 and you will see It works!

## Read more 
https://hub.docker.com/\_/httpd

