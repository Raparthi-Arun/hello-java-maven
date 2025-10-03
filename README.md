# Task 8 – Run a Simple Java Maven Build Job in Jenkins

## 📌 Objective
The objective of this task was to set up and run a simple *Java Maven build job* using *Jenkins*.  
This demonstrates Jenkins–Maven integration and provides basic hands-on experience with CI/CD.

---

## 🛠 Tools Used
- Jenkins
- Java JDK
- Apache Maven
- Git (optional)

---

## ⚙️ Steps Performed
1. Created a simple Java HelloWorld application and a pom.xml file for Maven.  
2. Installed and configured *Jenkins*.  
3. Configured *Maven* inside Jenkins using *Manage Jenkins → Global Tool Configuration → Maven*.  
4. Created a *Freestyle Job* in Jenkins named *hello-java-maven*.  
5. Added a build step using mvn clean install.  
6. Triggered a manual build in Jenkins.  
7. Verified the build by checking the *Console Output* for the message BUILD SUCCESS.

---

## ✅ Results
- Jenkins job *hello-java-maven* was successfully created and executed.  
- Builds (#1 and #2) completed successfully (green check).  
- Console output confirmed BUILD SUCCESS.  

---

## 🎯 Key Learnings
- How to create and configure a Java Maven project.  
- How to set up Maven in Jenkins.  
- How Jenkins executes builds and provides detailed logs.  
- Basics of CI/CD workflow with Jenkins.  

---

## 📸 Screenshots
- Jenkins job page showing successful builds.  
- Console Output displaying BUILD SUCCESS.
