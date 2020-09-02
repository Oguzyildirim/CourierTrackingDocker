#  Docker config for Courier producer Application and Geolocation Application

## Genarating images

To generate application images run this command at the root files of two project

    ./gradlew bootJar -Pprod jibDockerBuild

then docker-compose up

If you would like to create http requests from postman i've added postman collections.

