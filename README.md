# Spring Boot Exercise – Gradle Version

This exercise is nearly identical to the previous Level 1 task, but uses **Gradle** as the dependency manager.

## 🛠 Project Setup

Go to [https://start.spring.io/](https://start.spring.io/) and generate a Spring Boot project with the following settings:

- **Project**: Gradle
- **Language**: Java
- **Spring Boot**: Latest stable version

### Project Metadata

- **Group**: `cat.itacademy.s04.t01.n02`
- **Artifact**: `S04T01N02`
- **Name**: `S04T01N02`
- **Description**: `S04T01N02`
- **Package Name**: `cat.itacademy.s04.t01.n02`
- **Packaging**: Jar
- **Java Version**: 11 or higher

### Dependencies

- Spring Web
- Spring Boot DevTools

## ⚙️ Configuration

Open the file `src/main/resources/application.properties` and add:

```properties
server.port=9001

