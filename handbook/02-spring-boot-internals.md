# Spring Boot Internals

Spring Boot simplifies application configuration by providing:

- auto configuration
- embedded servers
- production ready features

Application Startup Flow

SpringApplication.run()
     ↓
Create ApplicationContext
     ↓
Scan Components
     ↓
Initialize Beans
     ↓
Start Embedded Server
