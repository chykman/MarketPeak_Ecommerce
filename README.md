# Market Peak E-commerce Website



## **Market Peak E-commerce**

**Project Title:** Market Peak E-Commerce Website\
**Student Name:** [Okoro Chikere Johnson]\
**Institution:** [DAREY.IO]\
**Course Name:** [Devops Engineering]



## Capstone Project: E-Commerce Platform Deployment with Git, Linux, and AWS

## **Abstract**

This capstone project focuses on deploying a static e-commerce website using Git, Linux, and AWS. It demonstrates proficiency in version control, cloud computing, and web server configuration. The project follows a structured approach, including repository setup, website deployment, and continuous integration for updates. The final implementation ensures a scalable and accessible web presence hosted on AWS.

### **Description**

This project demonstrates the skills and knowledge I have acquired in setting up and deploying a static website using Git, Linux, and AWS. It showcases my ability to implement version control through Git, manage a structured development workflow, and deploy applications in a cloud environment. The project involves creating and managing branches, staging, committing, and pushing changes to a remote repository, as well as configuring and hosting the website on an AWS EC2 instance. Detailed snapshots of the commands executed and tasks performed are included for documentation and transparency. This capstone project reinforces my expertise in Git operations, Linux server management, and cloud deployment, key skills essential for modern DevOps practices.

---
## **Objectives**

- Implement version control using Git.
- Host a static e-commerce website on AWS EC2.
- Automate deployments using Git workflows.
- Secure and optimize the server configuration for better performance.

---
## **Tools and Technologies Used**

- **Version Control:** Git, GitHub
- **Cloud Services:** AWS EC2
- **Operating System:** Linux (Ubuntu/CentOS)
- **Web Server:** Apache
- **Development Tools:** CLI, SSH
- **Programming Languages:** HTML, CSS, JavaScript (if applicable)

---

## **Methodology**

This project follows a structured step-by-step approach.

---



## Steps for Operations Performed

### 1. Version Control with Git

#### Create the Local Repository
![image](https://github.com/user-attachments/assets/bb79cf03-4bc6-4fc0-a585-a13fb5b0f1f9)

#### Download a Website Template
![image](https://github.com/user-attachments/assets/ff9356bd-2ca3-4469-a34c-ef42cf7deaaf)
![image](https://github.com/user-attachments/assets/e8f8fb53-c27a-4564-ba98-4d71e490ecc6)
![image](https://github.com/user-attachments/assets/516f31fe-5225-493a-a2b8-78d820538fcb)

#### Stage and Commit the Website Template to Git

**Set global username**  
![image](https://github.com/user-attachments/assets/dda0afe8-0d5d-44a8-93c4-6f232b7aafe7)

**Set global user email**  
![image](https://github.com/user-attachments/assets/9b238822-9f58-44ed-8e0f-8d64d6cdc72c)

**Git add the files**  
![image](https://github.com/user-attachments/assets/3ecaaa20-dfe6-466f-a222-31a469c5abfd)

**Git commit the files**  
![image](https://github.com/user-attachments/assets/d275b889-a474-4b88-95de-392df2e145e3)
![image](https://github.com/user-attachments/assets/211c52a8-c3fe-4863-88c3-8cf770bd687a)

#### Pushing Code to Git Repository

**Create a Git repository**  
![image](https://github.com/user-attachments/assets/66d10243-a56e-4069-9b7d-ba5d5c0c3ddc)
![image](https://github.com/user-attachments/assets/d530914f-7c66-46f0-af82-3b2a6ac7b44d)

**Link local repo to Git repository**  
![image](https://github.com/user-attachments/assets/33784ae3-a524-4887-a65b-411797646f3d)

**Push the code to Git repository**  
![image](https://github.com/user-attachments/assets/538f60ee-2a39-42ba-bd37-64b8bfe0d6eb)
![image](https://github.com/user-attachments/assets/70017113-f0ce-4b2d-a58c-f70bab74db41)

---

### 2. AWS Deployment

#### Setting Up AWS Instance

**Login as Admin User**  
![image](https://github.com/user-attachments/assets/1797c603-7336-4545-87fe-1c4b0b9997fe)

**Launch a New AWS Instance**  
![image](https://github.com/user-attachments/assets/cd49d4e0-f030-4505-823a-719b1c8646fd)
![image](https://github.com/user-attachments/assets/9496e12f-2742-4981-8f29-d223b6b8ee3e)
![image](https://github.com/user-attachments/assets/85274cfd-50ea-4be7-8dd1-6b3007b848a8)

**Connect to Your Instance via SSH**  
![image](https://github.com/user-attachments/assets/e92ca97a-1059-4769-a70f-c954cf7ea778)

---

#### 2.1 Clone Git Repository on AWS Server

**Clone Git Repository using SSH**  
![image](https://github.com/user-attachments/assets/e37cae2d-53dd-49e9-b8e6-e6b70702bdf8)

---

#### 2.2 Install Web Server on EC2 Instance

**Update All Packages**  
![image](https://github.com/user-attachments/assets/7bd56fc4-c361-442f-9d11-8273d46b6f59)

**Install and Start Apache Server**  
![image](https://github.com/user-attachments/assets/3d635f96-131e-4488-9f94-5763e3a0c589)
![image](https://github.com/user-attachments/assets/53e0c27a-6bc2-40ea-8bfa-ca5c3cbf0935)

**Enable Apache Server**  
![image](https://github.com/user-attachments/assets/b2cab939-121c-4852-806c-3a252353a553)

---

#### 2.3 Configure Apache Server

**Prepare Server by Clearing Default HTTPD Web Directory**  
![image](https://github.com/user-attachments/assets/a8beeafb-9ad7-4e69-acff-fd5f2ce17108)

**Replace with Market Peak E-Commerce Files**  
![image](https://github.com/user-attachments/assets/03d6af68-ec74-45a2-b83f-9e5a002539c0)

**Reload Apache Server**  
![image](https://github.com/user-attachments/assets/dab4a39e-4cdc-42d1-acfa-4eca7ada21fa)

---

#### 2.4 Access the Website through Web Browser

**Copy Public IP and Open in a Browser**  
![image](https://github.com/user-attachments/assets/fb472cb9-e46e-4add-8d90-88ddecd2fecd)

---

### 3. Continuous Integration and Deployment

#### Creating a Development Branch
![image](https://github.com/user-attachments/assets/05dcaeb7-f940-443f-bd62-22cc9491aa8f)

#### Making and Deploying Changes
![image](https://github.com/user-attachments/assets/f4dd5ab1-f105-49a0-9418-268704c5a999)

#### Testing Changes
**Website Before Changes**  
![image](https://github.com/user-attachments/assets/1e843139-cdca-4475-9ff0-0ff87ce40844)

**Website After Changes**  
![image](https://github.com/user-attachments/assets/6733313e-8638-4d5e-9586-daa1efcd6885)

---

## **Results & Testing**

- The website is successfully hosted on AWS.
- The Git repository enables version control and easy updates.
- Continuous integration ensures smooth deployment.
- The website is accessible via the EC2 instance’s public IP.

---

## **Challenges & Solutions**

### **Challenges Faced:**

- Trying too effect changes from the Production server side.
- Knowing the policies for my server to be able to access via web browser.
- Git merge conflicts during updates.

### **Solutions Implemented:**

- I used the changes that were git pulled from my remote repository to update apache url location(\var\www\html).
- Made sure my server allowed web traffic on port 80
- Resolved conflicts by managing Git branches efficiently.

---
---
## **Conclusion**

The **Market Peak E-Commerce Website** project successfully demonstrates cloud deployment, Git-based version control, and continuous integration. Future improvements include:



---


