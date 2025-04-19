# Jenkins + Maven Project

## 🌟 Objective

This project demonstrates how to build, test, and deploy a simple Java application using **Jenkins** and **Maven**. The application is built with Maven, and Jenkins is used to automate the continuous integration (CI) process.

## 🛠 Tools & Technologies Used
- **Java**: The core programming language for the application.
- **Maven**: A build automation tool for Java projects.
- **Jenkins**: A continuous integration server to automate the build process.
- **GitHub**: For version control and repository management.
- **Git**: To handle version control and repository management.

## 📂 Project Structure
hello-java-maven/ ├── src/ │ ├── main/ │ │ └── java/ │ │ └── HelloWorld.java # Main Java application ├── pom.xml # Maven configuration file ├── Jenkinsfile # Jenkins pipeline configuration └── README.md

# Project documentation

## 🚀 Steps Followed

1. **Project Setup**:
   - Created a simple Java application (`HelloWorld.java`) that prints "Hello, Jenkins + Maven!".
   - Configured **Maven** in the `pom.xml` to define dependencies and build settings.
   - Set up a Jenkins job to automate the build and testing process.

2. **Version Control**:
   - Initialized a Git repository for the project.
   - Pushed the code to a GitHub repository to enable Jenkins integration.

3. **Jenkins Setup**:
   - Created a Jenkins job that pulls the latest code from GitHub.
   - Configured the **Jenkinsfile** to define the pipeline and build steps (including Git repository clone and Maven build).
   - Triggered automatic builds on code pushes to the repository.

4. **Jenkins Pipeline**:
   - Set up a simple **Jenkinsfile** for automated builds with stages: `Checkout`, `Build`, and `Post-Build`.
   - Defined tools like Maven and JDK in Jenkins for the build process.

5. **Verifying Build**:
   - After each push, Jenkins automatically triggers a build and displays the build logs.
   - You can view build success/failure in the Jenkins dashboard.

## 🌐 Live Website Link

If you want to see the build results and project output, you can view them through the Jenkins interface at:

**Note**: You will need to set up your own Jenkins server to view the build results live.

---

## 📌 Features
- Automated Maven build triggered by Jenkins CI.
- Simple Java application with Maven dependencies.
- Jenkins pipeline for continuous integration.
- Clear build logs and status monitoring through Jenkins.

## 🚀 Continuous Integration Build

The Jenkins build for this project can be found at the following link:

[Jenkins Build Status](http://localhost:9090/job/hello-java-maven/4/)

Every time a commit is made, Jenkins will automatically trigger a build to compile and test the application.


---

## 🖼 Screenshot
![Website Screenshot](https://github.com/Maharshi08/hello-java-maven/raw/main/Screenshot2.png)
