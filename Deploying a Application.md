## Install jenkins 

- login to the Virtual Machine
- Install java
- Verify if Java is installed
- Installing Jenkins

**Pre-Requisites:**
- Java(JDK)

## Run the below commands to install Java and Jenkins

**Install java:**

```sudo apt update```

```sudo apt install openjdk-17-jre```

**Verify Java is Installed:**

```java -version```

## 🔧 Install Jenkins on Ubuntu

```bash
curl -fsSL https://pkg.jenkins.io/debian/jenkins.io-2023.key | sudo tee \
  /usr/share/keyrings/jenkins-keyring.asc > /dev/null

echo deb [signed-by=/usr/share/keyrings/jenkins-keyring.asc] \
  https://pkg.jenkins.io/debian binary/ | sudo tee \
  /etc/apt/sources.list.d/jenkins.list > /dev/null

sudo apt-get update
sudo apt-get install jenkins
```
---
**Note:**
By default, Jenkins will not be accessible to the external world due to inbound traffic restrictions on AWS & Azure.

**Login to Jenkins using the below URL:**

(http://<your-public-ip>:8080) give ur public ip address provided in your azure resources console.
