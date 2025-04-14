# Simple Web Platform

This is a simple web platform project built using Maven. The application sets up a basic HTTP server that responds to requests made to the root URL.

## Project Structure

```
simple-web-platform
├── src
│   ├── main
│   │   ├── java
│   │   │   └── com
│   │   │       └── example
│   │   │           └── web
│   │   │               └── App.java
│   │   ├── resources
│   │   │   └── application.properties
│   │   └── webapp
│   │       ├── WEB-INF
│   │       │   └── web.xml
│   │       └── index.html
│   └── test
│       └── java
│           └── com
│               └── example
│                   └── web
│                       └── AppTest.java
├── pom.xml
└── README.md
```

## Getting Started

To build and run the application, follow these steps:

1. **Clone the repository**:
   ```
   git clone <repository-url>
   cd simple-web-platform
   ```

2. **Build the project**:
   ```
   mvn clean install
   ```

3. **Run the application**:
   ```
   mvn jetty:run
   ```

4. **Access the application**:
   Open your web browser and navigate to `http://localhost:8080`. Click the link on the main page to trigger a request.

## Features

- Simple HTTP server setup
- Console logging when the link is clicked
- Basic HTML interface

## Dependencies

This project uses Maven for dependency management. The required dependencies are specified in the `pom.xml` file.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.