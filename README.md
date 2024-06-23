# Spring Booth Starter
 Spring Booth Project is a Spring Boot application that integrates with MySQL for data persistence, uses Thymeleaf for server-side rendering, and leverages Tailwind CSS and Flowbite for UI components.

## Prerequisites

- Java 17 or higher
- Maven
- Node.js and npm
- MySQL
- See HTML in the right
- ✨Magic ✨

## Configuration

- Edit src/main/resources/application.properties with the following configuration:

```sh
pring.application.name=scm
server.port=3000
spring.datasource.url=jdbc:mysql://localhost:3306/ `MysqlDataBaseName`
spring.datasource.username=root
spring.datasource.password=`Your Mysql Password`
spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
```

Markdown is a lightweight markup language based on the formatting conventions
that people naturally use in email.
As [John Gruber] writes on the [Markdown site][df1]

## Project Structure

```sh
Spring-Booth-Starter/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/
│   │   │       └── scm/
│   │   │           ├── SCMApplication.java
│   │   │           ├── controller/
│   │   │           ├── model/
│   │   │           ├── repository/
│   │   │           └── service/
│   │   ├── resources/
│   │   │   ├── static/
│   │   │   │   └── css/
│   │   │   │       ├── input.css
│   │   │   │       └── output.css
│   │   │   ├── templates/
│   │   │   └── application.properties
├── .gitignore
├── mvnw
├── mvnw.cmd
├── pom.xml
└── tailwind.config.js

```



## Documentation

- [Node.js](https://nodejs.org/en/learn/getting-started/introduction-to-nodejs) -  evented I/O for the backend
- [Thymeleaf](https://www.thymeleaf.org/documentation.html) -  Tailwind CSS Documentation
- [Flowbite](https://www.thymeleaf.org/documentation.html) - Flowbite Documentation
- [Tailwind CSS](https://www.thymeleaf.org/documentation.html) - Thymeleaf Documentation


## Installation

Already Install the all dependencies just Use.
```sh
git clone https://github.com/Khaire7031/Spring-Booth-Starter.git
```
Start The main Java File. src\main\java\com\scm\ScmApplication.java 

> Note: Run as  `Java Application`.

## Build Tailwind CSS
```sh
npx tailwindcss -i src/main/resources/static/css/input.css -o src/main/resources/static/css/output.css --watch
```
Verify the deployment by navigating to your server address in
your preferred browser.

```sh
http://localhost:3000/services
http://localhost:3000/about
http://localhost:3000/home
```

## Contact

| Source | Link |
| ------ | ------ |
| Linkdin | [https://www.linkedin.com/in/pranav-khaire-java-developer/] |
| GitHub | [https://github.com/Khaire7031] |
| Instagram | [https://www.instagram.com/pranav_khaire_70/] |


> Note: Change `Package Name` As Per Your Need.


## License

MIT

**Free Software, Hell Yeah!**

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)

  
 

   [PlGa]: <https://github.com/RahulHP/dillinger/blob/master/plugins/googleanalytics/README.md>
