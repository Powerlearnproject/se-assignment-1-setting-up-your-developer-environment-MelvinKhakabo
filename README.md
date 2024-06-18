[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15294620&assignment_repo_type=AssignmentRepo)
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

Setting up my developer environment on Windows 11 involved several detailed steps and configurations. Firstly, I installed Visual Studio Code as my preferred IDE. During the installation process, I made sure to include additional components and extensions for Python development, such as the Python extension and the GitLens extension for version control integration. After installation, I customized the settings in Visual Studio Code to suit my preferences, including themes, keybindings, and workspace settings. I also configured the Python extension to use the correct interpreter and set up linting and formatting tools for code consistency.
Next, I set up pip as my package manager for managing Python dependencies. I ensured that pip was installed correctly and added to the system PATH to allow for easy access from the command line. I also installed virtualenv to create isolated Python environments for my projects, ensuring that each project had its own set of dependencies to avoid conflicts. I regularly updated pip and virtualenv to the latest versions to take advantage of new features and bug fixes.
For database management, I installed MySQL on my Windows 11 machine. During the installation process, I configured MySQL to run as a service and set up a root password for security. I used the MySQL Command Line Client to create databases, tables, and users, and I configured the MySQL Workbench IDE for a graphical interface to interact with the database. I also installed the MySQL Python connector to allow Python scripts to communicate with the MySQL database.
To manage development environments and ensure consistent setups across different projects, I used Docker for virtualization. I created Docker containers for each project, containing all the necessary dependencies and configurations. This allowed me to easily share and replicate development environments with team members and deploy applications to production environments with confidence. I configured Docker to use Windows containers, ensuring compatibility with my Windows 11 operating system.
Finally, I enhanced my Visual Studio Code IDE with various extensions and plugins to improve productivity and streamline development processes. Some of the extensions I used included Bracket Pair Colorizer for visually matching brackets in my code, Live Server for quickly launching a local development server, and Markdown All in One for editing and previewing Markdown files. I regularly updated these extensions to the latest versions to ensure compatibility with new features and improvements.
Throughout the setup and configuration process, I encountered some challenges, such as compatibility issues with certain extensions and configuration conflicts between different tools. However, I was able to overcome these challenges through troubleshooting and seeking help from online resources and developer communities. Overall, the setup of my developer environment on Windows 11 was comprehensive and tailored to meet the specific requirements of my projects, allowing me to work efficiently and effectively.




#Deliverables:
- Document detailing the setup process with step-by-step instructions and screenshots where necessary.

Setting Up a Python Project in Visual Studio Code
Step 1: Install Visual Studio Code
Download Visual Studio Code from the official website: Visual Studio Code Download.
Run the installer and follow the on-screen instructions to complete the installation.
Step 2: Open Visual Studio Code and Create a New Project
Open Visual Studio Code.
Click on the "File" menu and select "Open Folder".
Create a new folder for your project and select it.
Click on the "New File" button in the Explorer pane and name it app.py.
Step 3: Write Some Python Code
Open the app.py file.
Write a simple Python program, such as:
python
Copy code
print("Hello, World!")
Step 4: Install Python and Set Up Environment
Install Python from the official website: Python Downloads.
During installation, make sure to check the box that says "Add Python to PATH".
Open a new terminal in Visual Studio Code by clicking on the "Terminal" menu and selecting "New Terminal".
Verify that Python is installed correctly by typing python --version in the terminal and pressing Enter.
Step 5: Install Required Dependencies
Create a requirements.txt file in your project folder.
Open the requirements.txt file and add the following line:
makefile
Copy code
requests==2.26.0
Install the dependencies using pip by running the following command in the terminal:
Copy code
pip install -r requirements.txt
Step 6: Run Your Python Program
In the terminal, type python app.py and press Enter.
You should see the output Hello, World! printed in the terminal, indicating that your program is running successfully.




- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).

My git repository: https://github.com/MelvinKhakabo/sample_app



- A reflection on the challenges faced during setup and strategies employed to overcome them.

During the setup of my Python project in Visual Studio Code, I encountered several challenges that required careful attention and problem-solving. One of the main challenges was ensuring that all dependencies were correctly installed and configured. I initially faced issues with installing the requests library using pip, as the version specified in my requirements.txt file was not compatible with the current version of pip. To overcome this challenge, I had to update pip to the latest version using the pip install --upgrade pip command before installing the dependencies.
Another challenge was setting up the Python environment in Visual Studio Code. Although I had installed Python and added it to the PATH during installation, I still faced issues with Visual Studio Code recognizing the Python interpreter. To resolve this, I had to manually specify the Python interpreter path in the Visual Studio Code settings.
Additionally, I encountered difficulties with configuring the Git repository for version control. When attempting to add my project files to the Git staging area using the git add . command, I received an error stating that the repository was not found. This was because I had forgotten to initialize a Git repository in my project folder. After initializing the Git repository using the git init command, I was able to successfully add and commit my files.
In overcoming these challenges, I learned the importance of thorough preparation and attention to detail when setting up a new project. It is essential to carefully review the project requirements and ensure that all dependencies are correctly specified and compatible with the current environment. Additionally, maintaining clear and detailed documentation can help streamline the setup process and provide a reference for troubleshooting common issues.
Moving forward, I plan to further improve my setup process by automating repetitive tasks, such as dependency installation and environment configuration, using tools like virtual environments and package managers. I also aim to enhance my troubleshooting skills by actively seeking solutions to common setup issues and incorporating them into my workflow.



#Submission:
Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.

#Evaluation Criteria:**
- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.
