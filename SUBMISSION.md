# Deliverables [50 pts]
Chadwick Rivera-Crum 1978229

# DOCKER
- Your dockerfile. Please provide a link to this file rather than a screen capture.
- [My Dockerfile](Dockerfile) 
- [Original docker file without MySQL](Dockerfile_original)


- Your running docker instance as shown by a ps command.
![Running Docker Instance](images/Docker_ps.png)

- Your browser accessing the main page of the website from your local container.
![Running Docker Instance](images/Spring_running_docker.png)

# DOCKER COMPOSE - MYSQL ONLY
- The output from the docker-compose up command
![Output from docker-compose up](images/docker-compose-up1.png)
![Output from docker-compose up](images/docker-compose-up-2.png)
- Your browser accessing the “Veterinarians” page of the website from your local container when you run the application from the host system.
![Vet page](images/vet-page.png)
- A section of the stack trace generated when you attempt to run the application container that has been updated to use MySQL.
![Failed Run](images/stacktrace.png)

# DOCKER COMPOSE - APP SERVER AND MYSQL
- Your updated docker-compose.yml file containing the application server, built from your local Dockerfile, and the existing MySQL configuration. Please provide a link to this file rather than a screen capture.

[docker-compose.yml](docker-compose.yml)
- Including this screen cap just to show build
![Capture of build from dockerfile](images/docker-build-both.png)
- Your updated application-mysql.properties file containing the URL change for the database server. Please provide a link to this file rather than a screen capture.
[application-mysql.properties file](src/main/resources/application-mysql.properties)

- The output from the docker-compose up command.
![Docker-compose up for both](images/docker-compose-both.png)

- Your browser accessing the “Veterinarians” page of the website from your local con- tainer.
![Vet page from App/Server in Container](images/spring-vet-both.png)