## Django Project Setup

### Create a project folder

From windows terminal run the following commands:
This will open the `DjangoProject` folder in vscode.

```
mkdir DjangoProject
cd DjangoProject
code .
```

<br>

Run the following commands from vscode terminal:

### Create a virtual environment

```
python -m venv venv
```

Activate the virtual environment

```
venv\Scripts\activate
```

### Create a django project

Create a `src` folder for your project

```
mkdir src
cd src
```

Inside the `src` folder start a django project

```
django-admin startproject myproject .
```

### Run the Development Server

```
python manage.py runserver
```
