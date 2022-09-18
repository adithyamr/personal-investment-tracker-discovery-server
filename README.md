# personal-investment-tracker-discovery-server
personal-investment-tracker-discovery-server

spring-boot:build-image
docker network create personal-investment-tracker
docker run -d --network personal-investment-tracker --name discovery-server -p 8761:8761 -it personal-investment-tracker-discovery-server:0.0.1-SNAPSHOT