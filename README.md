[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/swKMSSMl)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=16850804&assignment_repo_type=AssignmentRepo)
# Computer Graphics Booting Up

## Let's start with ModernGL

This lab stands to prepare the moderngl development environment. Below the steps and requirements for initial coding tasks. Please make sure to edit the python provided files; for dependencies, you can add the files you need.

1. Install moderngl and its dependencies
2. Make sure that the following programs run
    - [`01_hello_world.py`](./01_hello_world.py)
    - [`06_multiple_objects.py`](./06_multiple_objects.py)
    - [`09_models_and_images.py`](./09_models_and_images.py)
        - _Modify this program to change the box's texture to a correctly aligned TEC logo_
3. Document how to execute the 3 programs in the section below.

* For documentation and missing dependencies, follow these links:
    - https://github.com/moderngl/moderngl
    - https://moderngl.readthedocs.io/

## How to run your program

```
# Install Python if not already installed
sudo apt update
sudo apt install python3 python3-pip python3-venv -y

# Check Python version
python3 --version

# Create and activate a virtual environment
python3 -m venv env
source env/bin/activate

# Install dependencies from requirements.txt or manually
pip install -r requirements.txt || pip install moderngl pygame pillow objloader

# Run the script s
python 01_hello_world.py
python 06_multiple_objects.py
python 09_models_and_images.py


# Deactivate the virtual environment when done
deactivate

# Reference for Python virtual environments:
# https://docs.python.org/3/library/venv.html

```

## Grading Policy

- 25% - `01_hello_world.py` is running with no errors
- 25% - `06_multiple_objects.py` is running with no errors
- 25% - `09_models_and_images.py` is running with the requested change (TEC logo texture)
- 25% - Documentation on how to run your programs
