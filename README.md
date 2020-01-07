# Python Study

This project consists of several examples for python language study.

## Setup

### Python 3

This project requires python3. You can find a installation guide and integration with VS code on this [link](https://code.visualstudio.com/docs/python/python-tutorial)

### Virtual Enviroment

It is important to create a virtual environment, that isolates the project's dependencies. To do this, we will use the built-in command of python 3:

```cmd
python -m venv venv
```

where the last **venv** is the folder's name where the virtual enviroment configuration will exist.

Now activate the virtual environment:

```cmd
venv\Scripts\activate
```

### Installing Api dependencies

To install dependencies necessary for the api project, do:

```cmd
pip install -r requirements.txt
```

## Run the project

you can run the project with the following commands.

Backend:

```cmd
cd src && python app.py
```

### Folder structure

```
src
├── basics.py                # basics (but not obvious) python language features.
├──                          # .
```
