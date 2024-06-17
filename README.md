
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

I chose to continue using Windows 10 for my development environment setup as it meets the assignment requirement and is compatible with my current device.


2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download

   I  installed  Visual Studio Code (VS Code) as my IDE. Here's how I did it:
Downloaded the VS Code installer for Windows 10 from the official website: https://code.visualstudio.com/Download
![VS Download](c/Snippets/VS Code.png)

Double-clicked the downloaded installer and followed the on-screen instructions to complete the VS Code installation.


3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

I set up Git for version control as follows:
Downloaded and installed Git for Windows from the following website: https://www.git-scm.com/download/win
![GIT Installation](c/Snippets/GIT .png)

During installation, I chose the option to integrate Git with my command line and VS Code.

I then created a free account on GitHub: https://github.com/login

Then opened a terminal window Command Prompt  and navigated to my project directory, cd Project_git
Initialized a Git repository in my project directory by running the command git init.
Created a sample file  and added it to the staging area using git add.
Committed the changes with a descriptive message using git commit -m "First commit".
Pushed it to my remote repo using git push.

Understanding the concept of staging and committing changes initially posed a challenge but with practice I got a hang of it.

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

Since the assignment mentions Python, I installed the latest version from the official website:https://www.python.org/downloads/windows/
![Python Download](c/Snippets/Python .png)

During installation, I ensured Python was added to my system path(through Environmental Variable) for easy access from the terminal.


5. Install Package Managers:
   If applicable, install package managers like pip (Python).

Python uses the pip package manager, which comes bundled with the Python installation. I verified its installation by opening a terminal and typing pip --version.


6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

Downloaded the Installer: Downloaded the appropriate MySQL Community Server installer from the official website. 
![SQL Download](c/Snippets/My SQL.png)
However,I had difficulty choosing the installer type and therefore had to refer to the SQL documentation to ensure compatibility(factors such 32-bit or 64-bit system)

Ran the Installer: Double-clicked the downloaded installer and followed the on-screen instructions for the installation process. 
Tested the Connection: Connected to the MySQL server using the root user and password from the command line to verify successful installation.There was some difficulty connecting to the server but after double checking the root and password,everything was fine.


7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

I am currently comfortable with my development environment setup and will explore tools like Docker or virtual machines in the future if my projects require them.


8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

 I explored extensions in VS Code to enhance my development experience. Here are some;
Python extension for syntax highlighting and linting.
GitLens for Git integration within VS Code.

