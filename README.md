# CS304: Data Structures

Activity 01: Installing Essential Tools and Solving the Maze

## Assigned: Friday, 29 August 2025

## Due: Monday, 1 September 2025, by 9:00am (start of class) via GitHub

## Deliverables

You are to complete and push to your repository the completed File: `writing/reflection.md`. This writing contains a reflection, and your responses to some questions (contained in the document).

## Project Goals

+ To learn how to install and configure essential software for coding.
+ To practice giving and following precise instructions.
+ To develop skills in collaboration and critical analysis.

## Part 1: Installing Commonly Used Tools

In this part of the activity, you will install three commonly used tools for programming and software development: Visual Studio Code (VSCode), Git, and Python3. These tools are essential for writing, managing, and executing code.

Follow the instructions below to download and install the following tools on your computer. Choose the instructions that match your operating system (Windows, Mac, or Linux/Ubuntu).

### VSCode

+ **Windows**:  
  Download the installer from [https://code.visualstudio.com/](https://code.visualstudio.com/) and run the `.exe` file.

+ **Mac**:  
  Download the installer from [https://code.visualstudio.com/](https://code.visualstudio.com/) and open the `.zip` file. Drag the app to your Applications folder.

+ **Linux (Ubuntu)**:  
  Open a terminal and run:

  ```sh
  sudo apt update
  sudo apt install code
  ```

  Or download the `.deb` package from the website and install it.

### Git

+ **Windows**:  
  Download the installer from [https://git-scm.com/download/win](https://git-scm.com/download/win) and run the `.exe` file.

+ **Mac**:
I have found that by simply typing `git` in the terminal, it prompts to install the necessary command line tools from `XCode` which includes `Git` (and other programming tools). Follow the prompts to complete the installation.

  Install using Homebrew (*Note*: Homebrew can be downloaded from [https://brew.sh/](https://brew.sh/)):

  ```sh
  brew install git
  ```

  Or download from [https://git-scm.com/download/mac](https://git-scm.com/download/mac).

+ **Linux (Ubuntu)**:  
  Open a terminal and run:

  ```sh
  sudo apt update
  sudo apt install git
  ```

### Python3

+ **Windows**:  
  Download the installer from [https://www.python.org/downloads/windows/](https://www.python.org/downloads/windows/) and run the `.exe` file.

+ **Mac**:  
Note: Python is often pre-installed on MacOS, but it may be an older version which might need updating. I have found in some cases that by simply typing `python3` in the terminal, MacOS may automatically ask the user whether it can automatically install updates from `XCode`. Follow the prompts to complete the installation.


  Install using Homebrew:

  ```sh
  brew install python
  ```

  Or download from [https://www.python.org/downloads/mac-osx/](https://www.python.org/downloads/mac-osx/).

+ **Linux (Ubuntu)**:
Python is often pre-installed on Ubuntu, but if you need to install or upgrade it.

  Open a terminal and run:

  ```sh
  sudo apt update
  sudo apt install python3
  ```

## GatorGrade

This activity will be checked by Gatorgrade for completion when it is submitted to your GitHub repository. You can also check your work locally if you want before you submit it. To do so, you will first need to install the `GatorGrade` checking python code before it can be run. If you already have `GatorGrad` installed, then, there is need to reinstall it. 

 + You will used `pipx` to install `GatorGrade`. If you do not have `pipx` already installed, then please follow the instructions at [https://pipx.pypa.io/stable/installation/](https://pipx.pypa.io/stable/installation/) to install it on your local machine.
 + Install `Gatorgrade` by running the following command in your terminal or command prompt:

  ```bash
  pipx install gatorgrade
  ```

### Checking Your Work

 + Navigate to the root directory of this project in your terminal or command prompt to run the following command. Note, you must be inside the project directory for the below command to work to check your work.

  ```bash
  gatorgrade --config config/gatorgrade.yml
  ```
---

## Part 2: Maze Solving and Instruction Exchange

**Partner work**: Work with one partner.

**Deliverable**: A written set of instructions and a critique of the instructions you received from your partner.

**Instructions**:
Computer code is simply a listing of instructions that provide a computer with the steps needed to complete a task. Interestingly, the task of writing code is very similar to the task of writing instructions for a person to follow.

Writing clear and precise instructions is a crucial skill in programming and collaboration. In this part of the project, you will practice this skill by solving a maze and then exchanging your solution steps with your partner. Remember that when you are working with a list of instructions prepared by someone else, you must follow them exactly as given, without making assumptions or adding your own interpretations.

1. Pair up with a partner. Each person selects a maze diagram to solve.
2. Each person works independently to solve their chosen maze.
3. As you solve the maze, write down the *exact* steps and any important information needed to reach the solution.
4. Exchange your maze and instructions with your partner.
5. Each person must follow only the instructions provided by their partner to attempt solving the new maze.
6. After completing the maze, write a critique (see `writing/reflection.md`) of the instructions you received. Note what worked well and what could be improved.
7. Each member of the course is to submit their own copy of the work via their personal GitHub repository. Please be sure to include the name of your partner in your submission. Please also submit your work with a minimum of five (5) commits to your repository. (Note: These five commits are to encourage good habits when using `Git` and `GitHub`.)

## Reflection Questions

Please open the `writing/reflection.md` file and answer the questions there. Be sure to replace all instances of `TODO` with your answers. If you have any questions about the reflection, please ask!
