# QA Testing — JUnit 5 Homework

A **Java-based QA testing** project using **JUnit 5** for unit testing. Organized as an Eclipse project with source and binary directories.

## 🛠️ Tech Stack

- **Language:** Java (100%)
- **Testing Framework:** JUnit 5
- **IDE:** Eclipse

## 📁 Project Structure

```
QA-testing/
├── src/main/najah/     # Java source files
├── bin/main/najah/     # Compiled class files
├── .settings/          # Eclipse project settings
├── .classpath          # Eclipse classpath
├── .project            # Eclipse project descriptor
└── README.md
```

## ✨ Features

- JUnit 5 unit tests
- Organized with Maven-style source layout
- Eclipse project ready to import

## 🚀 Getting Started

### Prerequisites

- Java JDK 11+
- Eclipse IDE (or any Java IDE)
- JUnit 5 library

### Running Tests in Eclipse

1. Clone the repository:
   ```bash
   git clone https://github.com/aprar-jalal/QA-testing.git
   ```
2. Open Eclipse and go to **File → Import → Existing Projects into Workspace**.
3. Select the cloned folder and import.
4. Right-click the project → **Run As → JUnit Test**.

### Running Tests via Command Line

```bash
# Compile
javac -cp .:junit-platform-console-standalone.jar -d bin src/main/najah/*.java

# Run
java -cp .:bin:junit-platform-console-standalone.jar \
  org.junit.platform.console.ConsoleLauncher --scan-class-path
```

## 📄 License

This project is open source and available for educational use.
