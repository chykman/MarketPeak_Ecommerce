# Market Peak E-commerce Website

## Description - 

 # Capstone Project: E-Commerce Platform Deployment with Git, Linux and AWS

This project demonstrates the skills and knowledge I have acquired in setting up and deploying a static website using Git, Linux, and AWS. It showcases my ability to implement version control through Git, manage a structured development workflow, and deploy applications in a cloud environment. The project involves creating and managing branches, staging, committing, and pushing changes to a remote repository, as well as configuring and hosting the website on an AWS EC2 instance. Detailed snapshots of the commands executed and tasks performed are included for documentation and transparency. This capstone project reinforces my expertise in Git operations, Linux server management, and cloud deployment, key skills essential for modern DevOps practices.

### Steps for Operations Performed

#### 1. Version Control with Git

- Create the Local Repository
  
  ![image](https://github.com/user-attachments/assets/bb79cf03-4bc6-4fc0-a585-a13fb5b0f1f9)

- Download a Website template
  
  ![image](https://github.com/user-attachments/assets/ff9356bd-2ca3-4469-a34c-ef42cf7deaaf)

  ![image](https://github.com/user-attachments/assets/e8f8fb53-c27a-4564-ba98-4d71e490ecc6)

  ![image](https://github.com/user-attachments/assets/516f31fe-5225-493a-a2b8-78d820538fcb)
  
- Stage and Commit the Website Template to Git

  **To set global username**
  ![image](https://github.com/user-attachments/assets/dda0afe8-0d5d-44a8-93c4-6f232b7aafe7)

  **To set global user email**
  ![image](https://github.com/user-attachments/assets/9b238822-9f58-44ed-8e0f-8d64d6cdc72c)

  **To git add the files**
  ![image](https://github.com/user-attachments/assets/3ecaaa20-dfe6-466f-a222-31a469c5abfd)

  **To git commit the files**
  ![image](https://github.com/user-attachments/assets/d275b889-a474-4b88-95de-392df2e145e3)
  ![image](https://github.com/user-attachments/assets/211c52a8-c3fe-4863-88c3-8cf770bd687a)

- Pushing Code to Git repository
  **To Create your Git repository**
  ![image](https://github.com/user-attachments/assets/66d10243-a56e-4069-9b7d-ba5d5c0c3ddc)
  ![image](https://github.com/user-attachments/assets/d530914f-7c66-46f0-af82-3b2a6ac7b44d)

   **To Link Local repo your Git repository**
  ![image](https://github.com/user-attachments/assets/33784ae3-a524-4887-a65b-411797646f3d)

  **To push the code to the Git repository**
  ![image](https://github.com/user-attachments/assets/538f60ee-2a39-42ba-bd37-64b8bfe0d6eb)
  ![image](https://github.com/user-attachments/assets/70017113-f0ce-4b2d-a58c-f70bab74db41)



  #### 2. AWS Deployment

  - Setting Up AWS Instance
    
  -  Login as admin user
     ![image](https://github.com/user-attachments/assets/1797c603-7336-4545-87fe-1c4b0b9997fe)

    - Launch new AWS instance
     ![image](https://github.com/user-attachments/assets/cd49d4e0-f030-4505-823a-719b1c8646fd)
     ![image](https://github.com/user-attachments/assets/9496e12f-2742-4981-8f29-d223b6b8ee3e)
     ![image](https://github.com/user-attachments/assets/85274cfd-50ea-4be7-8dd1-6b3007b848a8)

- Connect to your instance via SSH
  Copy the command
   ![image](https://github.com/user-attachments/assets/e92ca97a-1059-4769-a70f-c954cf7ea778)

  Open on your CLI Platform paste and enter
  ![image](https://github.com/user-attachments/assets/97301ac1-9def-4315-a9d1-11ddffb38cd6)

  

  
 #### 2.1 Clone Git repository on AWS Server

 - Clone your Git Repository on the AWS Server using SSH Clone url
    ![image](https://github.com/user-attachments/assets/e37cae2d-53dd-49e9-b8e6-e6b70702bdf8)

   #### 2.2 Install Web Server on your EC2 Instance
    - Update all packages on the server
      ![image](https://github.com/user-attachments/assets/7bd56fc4-c361-442f-9d11-8273d46b6f59)
      
      - Install Apache server
        ![image](https://github.com/user-attachments/assets/3d635f96-131e-4488-9f94-5763e3a0c589)
        ![image](https://github.com/user-attachments/assets/1cae6146-e0fb-4f20-8a68-144a97eebfb5)

      - Start Apache server
        ![image](https://github.com/user-attachments/assets/53e0c27a-6bc2-40ea-8bfa-ca5c3cbf0935)

      - Enable Apache server
        ![image](https://github.com/user-attachments/assets/b2cab939-121c-4852-806c-3a252353a553)

      #### 2.3 Configure Apache server (HTTPD)

       - Prepare server by clearing the default HTTPD web directory
         ![image](https://github.com/user-attachments/assets/a8beeafb-9ad7-4e69-acff-fd5f2ce17108)

      - Replace with the Market Peak E-Commerce files
        ![image](https://github.com/user-attachments/assets/03d6af68-ec74-45a2-b83f-9e5a002539c0)

        - Reload Apache server
           ![image](https://github.com/user-attachments/assets/dab4a39e-4cdc-42d1-acfa-4eca7ada21fa)

     #### 2.4 Access the website through web browser

    - Copy the public ip from your Ec2 instance and open on a browser
      ![image](https://github.com/user-attachments/assets/fb472cb9-e46e-4add-8d90-88ddecd2fecd)

      #### 3 Continuous Integration and Deployment

      - Create  a Development Branch and switch to it
        ![image](https://github.com/user-attachments/assets/05dcaeb7-f940-443f-bd62-22cc9491aa8f)

      - Make minor changes to the code and stage
         ![image](https://github.com/user-attachments/assets/f4dd5ab1-f105-49a0-9418-268704c5a999)

      - Commit your changes
         ![image](https://github.com/user-attachments/assets/e1ab0d44-7f60-4da2-a7c3-2745a701fbf2)
         ![image](https://github.com/user-attachments/assets/a3df3599-0442-4c16-8fc9-005b885c456d)

        - Push your changes
          ![image](https://github.com/user-attachments/assets/5b33d5e4-95ad-43a9-b6a7-8c385c810c84)
        - Create a Pull request in Github
           ![image](https://github.com/user-attachments/assets/c9e5d6b6-9caf-4aee-89e1-31aca3b0af97)
           ![image](https://github.com/user-attachments/assets/675fc498-a21f-439e-9924-b1c2d5a04a49)

          - Merge PR
            ![image](https://github.com/user-attachments/assets/fa1aef0c-cd25-482b-9996-e370aeaa690e)
            ![image](https://github.com/user-attachments/assets/c8cc115b-ceb0-43a2-bade-acc72ce9f6ee)
            ![image](https://github.com/user-attachments/assets/95a5d79c-7a86-467f-874a-04abe878201a)

          - Switch local branch from development to main
             ![image](https://github.com/user-attachments/assets/8c24898a-d6df-4e11-bb5b-1c5a0e7a8572)
          - Merge to development
             ![image](https://github.com/user-attachments/assets/06c022b5-80fd-4c13-84aa-985694b2d939)
           - Push changes
              ![image](https://github.com/user-attachments/assets/e2559c5b-6ce9-4e35-9ff8-d867c2d57013)

            - Login to your Cloud server and pull the changes from your Website location
              ![image](https://github.com/user-attachments/assets/96e34fcb-0d68-43b9-bd98-c8a53b4b1d6e)
              ![image](https://github.com/user-attachments/assets/764821d5-420b-45f4-bb65-7df36ff4fc52)


              - Reload Apache server
                ![image](https://github.com/user-attachments/assets/4462d4f5-9c4e-47bd-9fd5-cb25790bd7e7)

                - Test to see the new changes by getting the public ip adress and opening it with a web browser
                  
                   
                

                

           
            



            




          




        
        

      
        



        


   

   

  



     



    

  
  


  

  



