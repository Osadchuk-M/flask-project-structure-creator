# flask-controller
___
Use this in your command line.

    % python flask-controller.py --help
    
    Usage: flask-controller.py command [options]

    Options:
      -h, --help  show this help message and exit

    Commands:
      create-project  Create flask project tree.

## Example
___

### Create project:

> % python flask-controller.py create-project <your_project_name>

    python flask-controller.py create-project MyProject

take a look a project structure:
    
    % tree MyProject
    MyProject/
    ├── app
    │   ├── decorators.py
    │   ├── email.py
    │   ├── exceptions.py
    │   ├── __init__.py
    │   ├── main
    │   │   ├── errors.py
    │   │   ├── forms.py
    │   │   ├── __init__.py
    │   │   └── views.py
    │   ├── models.py
    │   ├── static
    │   │   ├── css
    │   │   ├── fonts
    │   │   └── js
    │   └── templates
    │       └── index.html
    ├── config.py
    ├── manage.py
    ├── README.md
    └── tests
        └── __init__.py

