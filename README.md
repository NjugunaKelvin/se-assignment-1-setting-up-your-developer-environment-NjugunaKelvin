[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15260143&assignment_repo_type=AssignmentRepo)
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
3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

5. Install Package Managers:
   If applicable, install package managers like pip (Python).

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 




Kelvin Njuguna
Njugunak349@gmail.com


I first checked about my pc to see my windows version and system type (32 bit or 64 bit)
 




Setting Up My Development Environment on Windows 10
1. Selecting My Operating System (OS)
-Windows 10: Ensure my Windows 10 installation is up to date with the latest updates from Microsoft.

2. Installing a Text Editor or Integrated Development Environment (IDE)
Visual Studio Code: 
  - I downloaded Visual Studio Code from [Visual Studio Code Website] (https://code.visualstudio.com/Download).
  - I ran the downloaded installer (`VSCodeSetup.exe`).
  - Followed the installation wizard instructions.
  - After installation, I opened Visual Studio Code to verify it's working correctly.

3. Setting up Version Control System
Git: 
  - I downloaded Git from [Git website] (https://git-scm.com/).
  - Ran the downloaded installer (`Git-2.xx.x-64-bit.exe`).
  - Followed the installation wizard instructions:
    - Selected components to install (left default unless I had specific preferences).
    - Chose the default editor used by Git (Visual Studio Code).
    - Adjusted my PATH environment (chose "Use Git from the Windows Command Prompt").
    - Configured line ending conversions (chose "Checkout as-is, commit Unix-style line endings").
    - Configured the terminal emulator to use with Git Bash (chose "Use Windows' default console window").
    - Completed the installation.
  - Configured Git:
    - Opened Command Prompt or Git Bash.
    - Set my username: `git config --global user.name "NjugunaKelvin"`
    - Set my email address: `git config --global user.email "njugunak349@gmail.com"`
  - Created a GitHub account if I hadn't already at [GitHub] (https://github.com).
  - Initialized a Git repository:
    - Navigated to my project folder using Git Bash.
    - Initialized Git: `git init`
    - Added my files: `git add .`
    - Committed my changes: `git commit -m "Initial commit"`

4. Installing Necessary Programming Languages and Runtimes
- Python:
  - I downloaded Python from [Python website] (https://www.python.org/).
  - Ran the downloaded installer (`python-3.xx.x-amd64.exe`).
  - In the installation wizard, ensured to check "Add Python to PATH".
  - Chose the installation directory (default was recommended).
  - Installed Python by clicking "Install Now".
  - Verified the installation:
    - Opened Command Prompt or PowerShell.
    - Checked Python version: `python --version`

 5. Installing Package Managers
pip (Python):
  - pip was installed automatically with Python.
  - Verified pip installation:
    - Opened Command Prompt or PowerShell.
    - Checked pip version: `pip --version`

 6. Configuring a Database (MySQL)
-MySQL:
  - I downloaded MySQL from [MySQL website] (https://dev.mysql.com/downloads/windows/installer/).
  - Ran the downloaded installer (`mysql-installer-community-8.x.x.x.msi`).
  - Followed the MySQL Installer setup wizard:
    - Chose "Developer Default" setup type (includes MySQL Server, Workbench, and other useful tools).
    - Selected and downloaded products: MySQL Server, MySQL Workbench, and MySQL Shell.
    - Configured MySQL Server:
      - Set root password.
      - Configured MySQL Server as a Windows service.
    - Completed the installation.
  - Verified MySQL installation:
    - Opened MySQL Workbench to ensure it connects to the MySQL Server.

7. Exploring Extensions and Plugins
- **Visual Studio Code Extensions**:
  - Opened Visual Studio Code.
  - Went to the Extensions view (`Ctrl+Shift+X`).
  - Explored and installed extensions based on my needs:

---
























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
