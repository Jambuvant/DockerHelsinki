# get java 8 installed
from openjdk:8

workdir /springapp
copy . .

# build the project
run ./mvnw package

# run project
cmd ["java", "-jar","./target/docker-example-1.1.3.jar"]

