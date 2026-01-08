# Mini-Project: Maven-Jenkins-Build

##  Project Overview
This project demonstrates how to build and manage a Java application using **Apache Maven** as a build automation and dependency management tool.  
Maven is widely used in **DevOps environments** to automate builds, manage dependencies, run tests, and package applications.

This project follows standard Maven conventions and can be easily integrated with CI/CD tools like Jenkins and Docker.

---

##  Tools & Technologies Used
- Apache Maven
- Java (JDK 8 / 11 / 17)
- Git & GitHub
- Linux / Ubuntu
- Jenkins (optional)
- Docker (optional)

---

##  Implementation Steps:

**Step1: SSH Jenkins Server** 
- Create a directory mavenapp
- In mavenapp create mkdir -p src/main/com/fortune/app
- mkdir -p src/test/com/fortune/app
- touch pom.xml mkdir -p src/main/com/fortune/app/app.java mkdir -p src/test/com/fortune/apptest.java
- sudo apt install tree -y 
- tree

![](/Images/SSH%20and%20created%20file.png)

---
**Step2: Create a file**
- pom.xml
- nano src/main/com/fortune/app/app.java
- nano src/test/com/fortune/app/apptest.java

![](/Images/cmds.png)

---
**Step3: Add Maven and JDK**
- In Manage Settings
- Tools(Give Name to JDK and Maven)

---
Step4: Create new Item

![](/Images/Jenkins%20Item.png)

![](/Images/2.png)

![](/Images/3.png)

---

Step5: Create Github Repository
- Push file on Github

![](/Images/Git%20Repo.png)

---

Step6: Add Webhook

![](/Images/Screenshot%20(513).png)

Step7: 

