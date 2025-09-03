# IDS706_week1


## Project Description
This repository is the starter template and first project for IDS 706: Data Engineering Systems at Duke University. It was created by cloning a repository locally from the course instructor and setting up a virtual Python environment. 

In this respository, you will see:
- A Makefile that includes directions for installing, testing, formatting, linting, and cleaning code
- A requirements.txt file that list all the dependencies (packages) your project needs
- A hello.py file that returns a greeting message to students in the IDS class
- A test_hello.py file that tests the code from hello.py with one example for each function 
- A Github Actions workflow for continuous integration which automates certain workflows such as ensuring dependencies are installed correctly, code style is checked (flake8), tests are run (pytest), and everything passes before code is merged


## Setup/Usage instructions 

### Run the Python functions
If you want to run the functions in hello.py, run the script directly using 'python hello.py' and run the tests using 'make test'

### 1) Clone the repository
To use this template further, first clone the repository using git clone. If you are working working outside the dev container, create the virtual Python environment using the code below:

```bash
python3 -m venv ~/.IDS706_python_template
source ~/.IDS706_python_template/bin/activate
```

Then, install the dependencies using `make install`

### 2) Add Your New Project Code
- Replace hello.py with your own Python scripts
- Write matching test files
- Update the Makefile if you need new commands

### 3) Commit the new changes using example code below

```bash
git add .
git commit -m "Initial commit for Project"
git push origin main
```

### 4) Github Actions

The CI/CD is already set up so your new project will automatically install dependencies, run lint checks, and run tests on every push/pull request. However, if needed, you can update .github/workflows/main.yml if you need different Python versions or extra steps.


