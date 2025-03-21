# Java Spring Boot Study Project

This repository is a study project for learning Java with Spring Boot. It contains basic setup and examples of building a Spring Boot application. The project is run within a **Dev Container** using Docker and is used for exploring how to develop, build, and deploy Spring Boot applications in a containerized environment.

## Prerequisites

Before running the project, make sure you have the following installed on your machine:

- **Docker**: To build and run the Dev Container.
- **VS Code**: With **Remote - Containers** extension to work with Dev Containers.
- **Java JDK 21 or higher**: Ensure you have the correct version installed (JDK 21 is recommended for Spring Boot 3.x).
- **Maven** or **Gradle**: To manage dependencies and build the project. The project uses Maven.

## Setting up the Dev Container

1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   cd <repository-name>
   ```
2. Open the project in VS Code:
3. Open VS Code and open the project folder.
4. Rebuild the Dev Container:
5. Press Cmd + Shift + P (or Ctrl + Shift + P on Windows) in VS Code.
6. Type Rebuild Container and hit Enter to rebuild the Dev Container. This will set up the environment with all required dependencies such as Java, Maven, and other tools.
7. Check that the container is running:
Once the Dev Container is rebuilt, ensure that the container is running by opening the terminal in VS Code and checking if the environment is ready.

Running the Project

1. Start the Spring Boot application:

In the VS Code terminal (inside the Dev Container), use one of the following commands based on your project setup:
	•	For Maven:
 ```bash
 ./mvnw spring-boot:run
 ```
2. Access the Application:
  After the application starts successfully, you can access it through your browser:
 ```bash
 http://localhost:8080
 ```
You should see the Spring Boot application running. If you’re running this in a Dev Container, ensure that the port is correctly forwarded (refer to the devcontainer.json configuration).
