[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15283815&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download

   I had already installed VS Code while working on my Week 1 assignment and the installation was straightforward. I did not have any challenges intsallling it. However, when submitting my assignment, I had problems with "git commit" command, the changes I made were not reflected. I had an error and I tried solving the issue through Google but I ended up having creating more commands so I just used the save tab on VS Code. Kindly point out what mistake I might have done.


3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

   I had also installed github in Week 1 and I have not had a problem using it.


4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

5. Install Package Managers:
   If applicable, install package managers like pip (Python).

   
    Python was laready installed in my machine as well before I started this course as I was using it to practice for my school work.


    Download the SQL server from https://dev.mysql.com/downloads/windows/installer/ . (Pick Windows 8.0.37 and choose the 296MB file).

**SQL Installation**
Download the SQL server from https://dev.mysql.com/downloads/windows/installer/ . (Pick Windows 8.0.37 and choose the 296MB file).

Open the download and allow it to make changes to the computer.

Select “Server” option as the setup type.

Pick the most recent version and execute.

On the Type & Networking section, let the Name Pipe and Shared Memory remain as ‘MYSQL’. On the Config type, choose ‘Development Computer’. 

Check ‘Show Advanced and Logging Options’.

At the Authentication Method step, pick ‘Minimum Access to all Users’ and create a strong password.

Pick default options in the Windows Service.

Allow full access to the user running the server and the administrator groups only.

Uncheck ‘Slow Query Log’ and ‘Binary Log’ to get rid of the errors.

Leave the default settings on the Advanced Options and click ‘Next’.

Apply the Configuration by executing- Leave settings on default.

Copy "C:\Program Files\MySQL\MySQL Server 8.0\bin\mysqld" –console and run command on Command Line.

Shut down by running the command "C:\Program Files\MySQL\MySQL Server 8.0\bin\mysqladmin" -u root shutdown. 

**Problems encountered in MYSQL installation**
The shutdown command did not work for me so I used the following instead "C:\Program Files\MySQL\MySQL Server 8.0\bin\mysqladmin" -u root -p shutdown

I was prompted to put my password and the program was shut down.

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 



#Deliverables:
- Document detailing the setup process with step-by-step instructions and screenshots where necessary.
- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).
- A reflection on the challenges faced during setup and strategies employed to overcome them.

#Submission:
Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.

#Evaluation Criteria:**
- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.
