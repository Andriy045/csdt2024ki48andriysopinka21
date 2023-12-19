CSAD




Repository Information This repository was created for the tic-tac-toe game project. From the subject "Computer systems of automated design" NU "Lviv Polytechnic"

The task of the project is to create a game using hardware and software. The hardware must act as a server and handle requests from the software via the UART.

Student Number Student Assignment Configuration Format 21 Sopinka Andrii Tick-Toe (Unlimited Board) XML Project Details Communication Schematic Drawing Details about the technology, programming language, and hardware that will be used in the following assignments.

The front end and software of the application is written using Angular 2 with Ngrx as a single page application (SPA). The programming language is TypeScript

To connect the software and interface, I used Spring Boot, which will handle the requests from Angular, pass them to the Arduino, and send the response back. The programming language is Java

Raspberry Pi PICO hardware is used as a server. Programming language - C++, Framework - Arduino

DevOps Ansible and Jenkins will be used to simplify and automate build and deployment. Frontend and Backend will be combined with docker

Run Information about creating and running the program

IWNIL_client Don't forget to change the server address in environment.ts

Local launch. Node version 16 or higher is required

swagger: http:localhost:9000/swagger-ui
api-docs: http:localhost:9000/api-docs
IWNIL_hardware
Documentation for Raspberry Pi PICO was generated using doxygen You can view it by opening index.html file by any browser at docs/iwnil-hardware/html folder

=======

References
VS Code - Code editor with extensions for versatile development.
Node - JavaScript runtime for server-side applications.
npm - JavaScript package manager
Angular - Framework for dynamic web apps.
NgRx - State management for Angular.
Spring Boot - Simplified Java application development.
Maven - Build tool for Java projects.
Ansible - Automation for configuration and deployments.
Jenkins - CI/CD automation server.
Docker - Container platform for app development.
Arduino - Open-source electronics platform for DIY projects.
Raspberry Pi - Compact, low-cost computer board used for learning and hobby projects.
PlatformIO - Embedded development ecosystem with IoT support.
MongoDB - Popular, open-source NoSQL database management system designed for flexibility and scalability
Doxygen - Tool for generating documentation from annotated source code.
Javadoc - Documentation generator for generating API documentation in HTML format from Java source code.
Compodoc - Documentation tool for Angular applications, providing a comprehensive documentation for code.
Swagger - Framework for API specification that includes a set of tools to design, build, document, and use RESTful APIs.
