1) Adding Spring-Security to pom.xml
we need to add the spring-boot-starter-security dependency to enable Spring-Security in our project.
	<dependency>
				<groupId>org.springframework.boot</groupId>
				<artifactId>spring-boot-starter-security</artifactId>
	</dependency>

2) Start Application
3) Go to - http://localhost:8080/ on browser
4) Spring Security defaults to form-based authentication and provides a basic login page
5) Use default in-memory username as "user" and for password check your console - you can see your application generates a default password.
   ex -
     Using generated security password: 3ba23be2-3f44-4964-8997-28ccad83b870
     This generated password is for development use only. Your security configuration must be updated before running your application in production.
6) If you want to use your custom username and password - add below lines to your application.properties file
	spring.security.user.name=alok
	spring.security.user.password=pass

