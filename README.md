# Jenkins EC2 Automation

This repository, **jenkins-ec2-automation**, demonstrates the setup and basic usage of Jenkins on an AWS EC2 instance. The following tasks were performed and documented to provide a simple overview for beginners:

## Tasks Completed

1. **Jenkins Setup on EC2**  
   - Launched an AWS EC2 instance.  
   - Installed and initialized Jenkins.  

2. **Project Demonstrations**  
   - Created and executed:  
     - **Freestyle Project**  
     - **Pipeline Project**  
     - **Multi-Configuration Project**  
   - Verified successful execution with console outputs.  

3. **User and Role Management**  
   - Added Jenkins users with specific roles:  
     - **Global Roles**: Read-only access for employees.  
     - **Item Roles**: Full access for developers, testers, and production support.  
   - Assigned roles to corresponding users.  

## Screenshots

- `ec2-server.png`: Jenkins server running on EC2.  
- `simple-freestyle-project.png`: Freestyle Project execution output.  
- `simple-pipeline-project.png`: Pipeline Project execution output.  
- `simple-multiconfig-project.png`: Multi-Configuration Project execution output.  
- `users-created.png`: List of created users.  
- `user-manage-roles.png`: Role configuration details.  
- `users-role-assign.png`: Role assignments to users.  

## How to Reproduce

1. Launch an EC2 instance and set up Jenkins.  
2. Create the described projects and verify their outputs.  
3. Manage users and roles via **Manage Jenkins > Configure Global Security**.  

## Purpose

This repository is intended for beginners to understand:  
- Basic Jenkins setup and project execution.  
- Role-based access control configuration.  

Feel free to fork, explore, and enhance the tasks as part of your Jenkins learning journey!
