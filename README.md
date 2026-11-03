# 🤖 BugPredict AI – Software Defect Prediction & Code Analysis

## 📌 Project Overview

BugPredict AI is an intelligent software defect prediction and code analysis platform developed using Java and Spring Boot. It analyzes source code, identifies potential programming errors, evaluates code complexity, and predicts defect risk levels.

The platform helps developers detect potential issues early, understand code quality, identify high-risk files, and improve software reliability through automated analysis and suggested code corrections.

## 🎯 Objectives

- Identify potential software defects.
- Analyze source code automatically.
- Predict defect risk levels.
- Evaluate code complexity and quality.
- Suggest possible code corrections.
- Generate downloadable analysis reports.

## ✨ Key Features

- **Multi-language Code Scanning:** Supports Java, Python, JavaScript, TypeScript, C, C++, C#, Go, PHP, Ruby, Rust, and SQL.
- **Defect Detection:** Identifies selected common coding issues.
- **Risk Prediction:** Categorizes code files into Low, Medium, High, and Critical risk levels.
- **Code Complexity Analysis:** Evaluates cyclomatic complexity, nesting depth, and method length.
- **Automated Code Correction:** Provides suggested fixes for selected defect patterns.
- **Project Management:** Organizes projects and source files.
- **Scan Management:** Performs code analysis and maintains scan results.
- **Report Generation:** Exports analysis results in CSV format.
- **User Authentication:** Supports secured application access.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Java 21 | Backend programming |
| Spring Boot 3.5.5 | Backend framework |
| Spring Security | Authentication and security |
| Spring Data JPA | Database operations |
| JavaParser | Java AST parsing |
| MySQL | Database support |
| H2 Database | Local database |
| Maven | Dependency management |
| HTML, CSS, JavaScript | Frontend |

## 🏗️ Project Architecture

```text
BugPredict-AI/
│
├── src/
│   ├── main/
│   │   ├── java/com/bugpredict/
│   │   │   ├── config/
│   │   │   ├── controller/
│   │   │   ├── model/
│   │   │   ├── repository/
│   │   │   ├── service/
│   │   │   └── BugPredictApplication.java
│   │   │
│   │   └── resources/
│   │       ├── static/
│   │       │   ├── css/
│   │       │   ├── js/
│   │       │   └── index.html
│   │       └── application.yml
│   │
│   └── test/
│
├── pom.xml
├── Dockerfile
├── mvnw
├── mvnw.cmd
└── README.md
```

## ⚙️ Installation and Setup

### Prerequisites

- Java JDK 21
- Maven
- Visual Studio Code / IntelliJ IDEA
- MySQL (optional, if using MySQL instead of the default H2 database)

### Step 1: Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### Step 2: Navigate to the Project

```bash
cd bugpredict-ai
```

### Step 3: Build the Project

For Windows:

```bash
mvnw.cmd clean compile
```

For Linux/Mac:

```bash
./mvnw clean compile
```

### Step 4: Run the Application

```bash
mvnw.cmd spring-boot:run
```

For Linux/Mac:

```bash
./mvnw spring-boot:run
```

### Step 5: Open in Browser

```text
http://localhost:8080
```

## 🧪 Run Tests

```bash
mvnw.cmd test
```

## 📊 Expected Outcomes

- Automated source code analysis.
- Identification of potential programming defects.
- Risk classification of source files.
- Code quality evaluation.
- Suggested code improvements.
- Downloadable defect analysis reports.

## 🔮 Future Enhancements

- Integration of advanced machine learning models.
- Support for additional programming languages.
- Improved AI-based bug detection.
- GitHub repository integration.
- Real-time code analysis.
- Advanced visualization dashboards.
- Automated testing recommendations.

## 🎓 Learning Outcomes

- Java and Spring Boot development.
- REST API development.
- Database integration using JPA.
- Static code analysis.
- Abstract Syntax Tree (AST) concepts.
- Software defect prediction.
- Secure application development.

## 📝 Conclusion

BugPredict AI provides an automated approach to software defect analysis and risk prediction. By identifying potential coding issues and evaluating software quality, the platform helps developers improve code reliability, reduce debugging effort, and build better software applications.

## 👩‍💻 Project Details

**Project Name:** BugPredict AI

**Domain:** Artificial Intelligence & Software Engineering

**Project Type:** Full-Stack Web Application

**Backend:** Java Spring Boot

**Database:** MySQL / H2

---

⭐ If you find this project interesting, consider giving it a star!
