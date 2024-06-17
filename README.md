[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15280645&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

Go to the official Microsoft Windows 11 download page.
Use the Installation Assistant:

Click on the “Download now” button under the "Windows 11 Installation Assistant" section. This tool is designed to upgrade your current PC to Windows 11.
Create Installation Media:

Alternatively, if you want to perform a clean install or install Windows 11 on a different PC, you can create a bootable USB drive or DVD.
In the "Create Windows 11 Installation Media" section, click “Download now”.
Run the Media Creation Tool, and follow the instructions to create installation media on a USB drive or DVD.
Download the ISO File:

You can also download the Windows 11 disk image (ISO) directly. Under the "Download Windows 11 Disk Image (ISO)" section, select Windows 11 and click “Download”.
Step 4: Install Windows 11
Upgrade Using Installation Assistant:

Run the Installation Assistant you downloaded in Step 3. Follow the on-screen instructions to upgrade your PC to Windows 11.
Using Installation Media:

Insert the USB drive or DVD you created into the PC where you want to install Windows 11.
Restart the PC and boot from the USB drive or DVD.
Follow the on-screen instructions to perform a clean installation.
Using the ISO File:

Mount the ISO file (right-click and select "Mount") and run the setup.exe file to start the installation process.
Follow the on-screen instructions to upgrade or perform a clean installation.
After installation, ensure Windows 11 is activated. If you upgraded from a genuine copy of Windows 10, Windows 11 should activate automatically. If not, you may need to enter your product key
Once Windows 11 is installed, go to Settings > Windows Update to check for and install any updates. Also, ensure all necessary drivers are installed and updated.


2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download

•	Visit the official Visual Studio Code website (https://code.visualstudio.com/) using your
                web browser, I used Chrome.
- Download the installer for your operating system I chose Windows, because I use Windows.
•	On the left side of the File Explorer window, locate and click on Downloads. Double-click on
        the downloaded 'VSCodeUserSetup-x64-1.x.x.exe file.
•	Once the installer launches, step through the installation process. First, accept the License
        Agreement, then click Next >.
•	Accept the default location for installation by clicking Next >.
•	Optionally check the boxes for 'Creating a desktop icon', and adding VS Code to the Right-
        Click menu functionality of Windows File Explorer, then click Next >.
•	Confirm the installation options, then click Install.
•	The installation will proceed.
•	Click Finish to exit the installation and (by default) launch Visual Studio Code.
•	The Visual Studio Code installer will create an icon in the ⊞ Start Menu. To locate it, click on
the Start Menu and search for 'Code'.
•	Visual Studio Code will launch.


3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

•	Visit your web browser, I used Chrome. Type “Git for windows” if you use windows like me, and press enter.
•	Click on “Git for Windows”
•	Click download.
•	On the left side of the File Explorer window, locate and click on Downloads. Double-click on Git-2.45.2-64-bit.
•	Once the installer launches, step through the installation process.
•	Click next
•	Accept the default location for installation by clicking Next >.
•	Select the components you want to install; clear the components you do not want to install. Click Next when you are ready to continue.
•	Click next.
•	Where it says “Which editor would you like Git to use” I had to choose “Use Notepad as Git’s default editor” and click Next.
•	Click next until install.
•	Wait while setup installs Git on your computer.
•	Then launch Git Bash and Click Finish.
•	You have now set up Git, create a GitHub account, initialize a Git repository, and make your first commit.
•	You go to your web browser and write github and click enter.
•	On github, you signup or login create your repository.
on Git bash:
git --version
git config --global user.name "Thandi Zikhokhile Sithole"
git config --global user.email "cokejobe@gmail.com"
mkdir demo
cd demo
git init
git status
git commit -m "this is my first commit"
git branch
git remote add origin http://github.com/Thandi06/demo.git
git push -u origin master
vi README.md
git status 
git fetch
git add .
git commit -m "my second commit"
git fetch
git pull
git push



4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

Visit the official Python website http://wwww.python.org .
Click on "Downloads" and select your operating system Windows.
Run the Installer:

Open the downloaded installer file.
Check the option to "Add Python to PATH".
Click "Install Now" and follow the prompts.
Verify Installation:

Open a terminal or command prompt. i opened git bash
Type python --version to check the installation, it came up as Python 3.12.4


5. Install Package Managers:
   If applicable, install package managers like pip (Python).

Open a terminal or command prompt. i opened git bash
Run pip --version to check if pip is installed. it was not installed 
Install pip (if not already installed): i had to install pip manual

Download get-pip.py from the official site.
i had to right click on the get-pip.py page and click copy, went to my file explorer window to create a folder and paste.
Run the script: on git bash
python get-pip.py
Upgrade pip:

Run the following command to upgrade pip to the latest version:
git bash
python -m pip install --upgrade pip
Verify Installation
Run pip --version to ensure it is installed correctly. it came as pip-24.0


6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

Go to https://dev.mysql.com/downloads/windows/installer/5.7.html
Click "Download" for the MySQL Installer.
Run the Installer:

Open the downloaded .msi file on file explorer window
Choose "Developer Default" setup.
Install MySQL:

Follow the on-screen instructions and click "Next" and "Execute" to install.
Configure MySQL:

Set the root password.
Configure server settings.
Finish the installation.
Verify Installation:

Open MySQL Command Line Client.
Log in with root credentials.
Run SHOW DATABASES; to confirm setup.



7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

Virtual Environment Setup:
git bash:
pip install virtualenv
mkdir my-python-project
cd my-python-project
virtualenv venv
Activate Virtual Environment:
venv\Scripts\activate

 Use an official Node.js runtime as a parent image
FROM node:14

# Set the working directory
WORKDIR /usr/src/app

# Copy package.json and package-lock.json
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy the rest of the application code
COPY . .

# Expose the port the app runs on
EXPOSE 8080

# Command to run the application
CMD ["node", "app.js"]
 Build and Run the Docker Image

docker build -t my-node-app .
docker run -p 8080:8080 my-node-app


8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

To install any of these extensions, follow these steps:

Open VS Code.
Go to the Extensions view by clicking on the Extensions icon in the Activity Bar on the side of the window or by pressing Ctrl+Shift+X.
Search for the extension by typing the name in the search bar.
Click on the Install button next to the extension you want to install.
syntax highlighting:
JavaScript (ES6) code snippets
Installation Command: ext install xabikos.JavaScriptSnippets

Python
Installation Command: ext install ms-python.python

HTML CSS Support
Installation Command: ext install ecmel.vscode-html-css

Markdown All in One
Installation Command: ext install yzhang.markdown-all-in-one

TypeScript and JavaScript Grammar
Installation Command: ext install ms-vscode.vscode-typescript-next

C/C++
Installation Command: ext install ms-vscode.cpptools

PHP Intelephense
Installation Command: ext install bmewburn.vscode-intelephense-client

Ruby
Installation Command: ext install rebornix.ruby

Language Support for Java(TM) by Red Hat
Installation Command: ext install redhat.java

Go
Installation Command: ext install golang.go

YAML
Installation Command: ext install redhat.vscode-yaml

JSON Tools
Installation Command: ext install eriklynd.json-tools

Bash IDE
Installation Command: ext install mads-hartmann.bash-ide-vscode

2. Linting
ESLint
Installation Command: 'ext install dbaeumer.vscode-eslint'
Configuration: 'npm install eslint --save-dev and npx eslint --init'

Pylint
Installation Command: 'ext install ms-python.python'
Configuration: 'pip install pylint'

Flake8
Installation Command: 'ext install ms-python.python'
Configuration: 'pip install flake8'

TSLint
Installation Command: 'ext install ms-vscode.vscode-typescript-tslint-plugin'
Configuration: 'npm install tslint --save-dev and npx tslint --init'


HTMLHint
Installation Command: 'ext install HTMLHint.vscode-htmlhint'
Configuration: 'npm install htmlhint --save-dev'

Stylelint
Installation Command: 'ext install stylelint.vscode-stylelint'
Configuration: 'npm install stylelint stylelint-config-standard --save-dev'

Ruby RuboCop
Installation Command: 'ext install rebornix.ruby'
Configuration: 'gem install rubocop'

Go
Installation Command: 'ext install golang.go'
Configuration: 'go get -u golang.org/x/lint/golint'

Code Formatting:
Prettier - Code formatter
Installation Command: 'ext install esbenp.prettier-vscode'

Beautify
Installation Command: 'ext install HookyQR.beautify'

Black Formatter
Installation Command: 'ext install ms-python.black-formatter'

Autopep8
Installation Command: 'ext install ms-python.python'

C/C++
Installation Command: 'ext install ms-vscode.cpptools'

PHP Intelephense
Installation Command: 'ext install bmewburn.vscode-intelephense-client'

Go
Installation Command: 'ext install golang.go'

Version Control Integration:
GitLens — Git supercharged
Installation Command: 'ext install eamodio.gitlens'

Git Graph
Installation Command: 'ext install mhutchie.git-graph'

GitHub Pull Requests and Issues
Installation Command: 'ext install GitHub.vscode-pull-request-github'

Git History
Installation Command: 'ext install donjayamanne.githistory'

GitHub Actions
Installation Command: 'ext install GitHub.vscode-github-actions'

Azure Repos
Installation Command: 'ext install ms-vsts.team'

SVN
Installation Command: 'ext install johnstoncode.svn-scm'




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
