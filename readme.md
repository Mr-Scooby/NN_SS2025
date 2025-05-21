The exercise scripts can be run either in VS code development software (Method1) or in a browser based interactive python terminal (Method2)

Method1:
This is the easiest method and does not require any prior dependency. 

Visual Studio Code (VS Code) is a powerful and versatile code editor developed by Microsoft. 
It's designed to be lightweight and efficient, while also offering a wealth of features for developers.

Installation:

Download VS code development software from the official website: https://code.visualstudio.com/

Open VS Code -> Go to File -> Open Folder or use the shortcut Ctrl+O (Windows/Linux) or Cmd+O (macOS).
Navigate to the location of exercise folder and select it.

** Alternative to VS Code is to use PyCharm which is specifically a python development software.

Method2:

This method already requires that you have installed Python and pip installed. Follow the steps to install jupyterlab and start the server.

1. Install JupyterLab:

Ensure you have Python and pip installed. Then, open your terminal or command prompt and run the following command:

> pip install jupyterlab

2. Start the JupyterLab Server:

Once installed, you can start the JupyterLab server by running the following command in your terminal:

> jupyter lab

This will open your default web browser and launch the JupyterLab interface. 
Here you will see the folder structure of the directory from where you launched JupyterLab. If you want the server to load folders from a different path
then you have to use the following command

> jupyter lab --notebook-dir=/path/to/your/desired/directory

