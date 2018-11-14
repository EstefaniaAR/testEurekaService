# testEurekaService
Part of a spring cloud sample. Eureka server has the register of all related service 

## Eureka Server 
Eureka server displays all services related to the microservices Architecture.

## Requirements 
- Spring boot
- Java 8
- Config server from :https://github.com/EstefaniaAR/testConfigServer.git
- Reservation service from: https://github.com/EstefaniaAR/testReservationService.git

## Dependencies
	<dependencies>
		<dependency>
			<groupId>org.springframework.cloud</groupId>
			<artifactId>spring-cloud-starter-config</artifactId>
		</dependency>
		<dependency>
			<groupId>org.springframework.cloud</groupId>
			<artifactId>spring-cloud-starter-netflix-eureka-server</artifactId>
		</dependency>

		<dependency>
			<groupId>org.springframework.boot</groupId>
			<artifactId>spring-boot-starter-test</artifactId>
			<scope>test</scope>
		</dependency>
	</dependencies>

## Run
Run the main class as Spring Boot Application

## Query
http://localhost:8761/
