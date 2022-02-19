# Spring Boot Camp

Working plan to get started with Spring Boot

1. Tools

   - Java 11 - JDK - You need a Java Development Kit installed. Amazon's implementation Corretto is a good choice -
     - [AWS Correto download](https://docs.aws.amazon.com/de_de/corretto/latest/corretto-11-ug/downloads-list.html)
   - Package manager - Homebrew - Homebrew is a package manager for Mac. We will use this to install some tools easily
     - [https://brew.sh](https://brew.sh)
   - IDE/Code editor - VSCode/Codium - I like to use Codium, the open-source telemetric free VSCode version. It has a bunch of plugins and helps development quite a bit. Intelij IDEA is also a very good choice. I use the paid version at work and really like it.
     - [VSCodium](https://github.com/VSCodium/vscodium)
     - VSCode spring Boot Plugins
       - [VSCode java-spring-boot docs](https://code.visualstudio.com/docs/java/java-spring-boot)
       - [VSCode spring boot dev pack plugin](https://marketplace.visualstudio.com/items?itemName=Pivotal.vscode-boot-dev-pack)
       - [VSCode Java plugin](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-pack)
   - Postman/insomnia - You will need a tool for making REST requests. I like Insomnia because it's nice and clean. But Postman also works
     - [Insomnia](https://insomnia.rest/download)
            - [Postman](https://www.postman.com/downloads/)
   - MongoDB - We will use a NoSQL database that save objects. - Install mongodb as a service in homebrew locally
     - [MongoDB installation guide](https://docs.mongodb.com/manual/tutorial/install-mongodb-on-os-x/)
     - Install a tool to look at the database data e.g. [Compass](https://www.mongodb.com/products/compass)

2. Java Basics
   [Online syntax resource](https://www.tutorialspoint.com/java/java_basic_syntax.htm)
   1. Objects
   2. [Interfaces](https://www.tutorialspoint.com/java/java_interfaces.htm)
   3. Conforming to an interface
   4. Spring boot [Dependency Injection](https://www.baeldung.com/spring-dependency-injection)
3. Initialization
   1. Spring boot initializer [Boilerplate generator](https://start.spring.io)
   2. Dependency Management with Maven [Spring boot maven docs](https://docs.spring.io/spring-boot/docs/2.6.3/maven-plugin/reference/htmlsingle/#?.?)
4. Separation of concern
    1. API/Web
    2. Models [(JSON)](https://www.json.org/json-en.html)
    3. Service
    4. Persistence
5. Build API
    1. Annotations [Cheat-sheet](https://www.jrebel.com/blog/spring-annotations-cheat-sheet)
    2. [GET](https://developer.mozilla.org/de/docs/Web/HTTP/Methods/GET)
    3. [POST](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods/POST)
    4. [DELETE](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods/DELETE)
6. Testing
    1. Basics [Docs](https://docs.spring.io/spring-boot/docs/1.5.2.RELEASE/reference/html/boot-features-testing.html)
    2. [Test driven development (TDD)](https://en.wikipedia.org/wiki/Test-driven_development)
7. JSON Requests
    1. GET
    2. POST
    3. DELETE
8. Service layer and logic
    1. [Annotations](https://docs.spring.io/spring-framework/docs/current/javadoc-api/org/springframework/stereotype/Service.html)
9. Persistence
    1. [Object storage](https://www.mongodb.com/en-us/nosql-explained)
    2. MongoDB
    3. [Repositories](https://docs.spring.io/spring-data/jpa/docs/current/reference/html/#repositories)
￼
