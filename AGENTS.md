A backend api application microservice for managing user address directory.

It should have the following features:
1. Create user address
2. Update user address
3. Delete user address
4. Get user address
5. List user addresses
6. Search user addresses by name, phone, email, address

It should have the following tables:
1. UserAddress
# Tools
- use embedded database as h2 or sqlite.
- use java 17 springboot 3.x
- use maven for build management
- use docker for containerization
- use git for version control
- Write Azure devops pipeline yaml for CI/CD build push in azure artifact and deploy in azure container instance.
- write dockerfile and helm chart for deployment.
# setup

 When i run the container image it should start the application and expose the port 8080.
 It should create the required table in h2 database if not exists.
 It should have a health check endpoint at /actuator/health.
 It should have a swagger ui at /swagger-ui.html.

 # DOcumentation
 - Document the code and the setup process in the README.md file.

 # Testing
 - Write unit tests for the application.
 - Write integration tests for the application.
 - Write end-to-end tests for the application.
 - make sure all tests are passing before pushing the code to the repository.
 - make sure code coverage is at least 80%.
 - make sure jacoco is configured and generating reports.
 - make sure in pom.xml project version can be passed for release build otherwise default is snapshot.