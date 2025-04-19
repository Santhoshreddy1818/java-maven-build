## 📦 Project Structure

```
java-maven-build/
├── src/
│   └── main/
│       └── java/
│           └── com/
│               └── example/
│                   └── App.java
├── pom.xml
└── README.md
```

## 🚀 Getting Started

### Prerequisites

Ensure you have the following installed:

- Java 11+ (JDK)
- Maven 3.6+

### Clone the Repository

```bash
git clone https://github.com/Santhoshreddy1818/java-maven-build.git
cd java-maven-build
```

### Build the Project

```bash
mvn clean install
```

### Run the Application

```bash
mvn exec:java -Dexec.mainClass="com.example.App"
```

> ⚠️ Make sure the `exec-maven-plugin` is configured in your `pom.xml`.

## 🧪 Running Tests

```bash
mvn test
```

## 📁 Packaging the Application

```bash
mvn package
```

The JAR file will be generated in the `target/` directory.

## 📌 Features

- Standard Maven build lifecycle
- Easy integration with CI/CD pipelines (Jenkins, GitHub Actions)
- Simple Java main class structure
- Unit testing with JUnit

## 🤖 CI/CD Integration

This project is designed to work well with tools like:

- Jenkins
- GitHub Actions
- Docker

## 👨‍💻 Author

**Santhosh Reddy**  
GitHub: [@Santhoshreddy1818](https://github.com/Santhoshreddy1818)  
