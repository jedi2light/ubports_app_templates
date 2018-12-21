# ubports_app_templates

A set of Ubuntu Touch (UBports) templates/skeleton Application created to speed up the developments of new applications.
You can create a new application using one of them as starting point.

Currently all the templates are “pure-qml-cmake - Pure QML App (built using Cmake)” 
(ie: qml+javascript based)

There are four templates: 
- AdaptiveLayout: to create an application based on the AdaptiveLayout Component
- ChartJs: to create an application that include chart creation using a javascript library
- ListView: to create an application that uses a ListView component (UbuntuListView) to show a list of items and PageStack for navigation
- PageStack:  to create an application that uses PageStack component for pages navigation


Requirements:
To use this template is necessary install the “cookiecutter” library (https://cookiecutter.readthedocs.io/en/latest/installation.html).
After the installation will be available the executable ‘cookiecutter’ from the command line.

Also the  installation of ‘clickable’  tool is nesessary (http://clickable.bhdouglass.com/en/latest/).
It is not mandatory to create new applications from the templates but will be necessary to continue the development of your new application.

How to use the templates:
1) donwload/clone the template project
2) open a shell in the folder where you want create your new application
3) run the following command:

$ cookiecutter <path to cookiecutter.json>

Where “<path to cookiecutter.json>” is the path to “cookiecutter.json”file  of the chosen template.
4) provide the required informations (press enter to use default values)

At the end, your new application will be placed in a folder whose name is the value provided for “project_name” entry.

Testing:
Note: ‘clcickable’ tool is necessary to perform this task
To test your new application, enter in his root folder (here you’ll find a file named ‘clickable.json’)
open a shell in that folder and run:

$ clickable desktop

If everything is ok, after a while your new application will start.

Now you are ready to start your new application development.

Good luck 