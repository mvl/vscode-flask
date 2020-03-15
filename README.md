# Setup to build and run
This project is based on https://code.visualstudio.com/docs/python/tutorial-flask#_create-and-run-a-minimal-flask-app . After a git clone, the project needs the python virtual environment configured:
1. In the project's top level folder, run 'python3 -m venv env' on the command line. This should create the python virtual environment. 
2. Activate the environment, by running 'source ./env/bin/activate'
3. Verify the virtual env is active by running 'which python'. It should return the path relative to the newly-created env/ directory.
4. run 'pip install -r requirements.txt'. This should install Flask and other dependencies.
5. Deactivate the virtual environment in the shell by running 'deactivate'.
6. Open the project in VSCode with File->Open.. or File->Open Workspace...
7. Make sure VSCode uses the virtual env's python and activates it in the integrated terminal.

