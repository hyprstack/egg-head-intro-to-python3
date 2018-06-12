## Virtual environment allow us to keep dependencis for diffenrent places in different places

### To use it

`pip install virtualenv`

*Then create a directory for the project*

- In the new project directory then run `virtualenv py3 -p /usr/local/bin/paython3`
- This will create new directory **py3** with all the requirements to run the new environment
- Run `source py3/bin/actvate` to start the new virtual environment
- Run normal commands as you usually would (this includes installing libraries)
- Run `pip freeze > requirements.txt` to create a file with a snapshot of the current state of the virtual environment to rebuild later fro anywhere
- Run `cat requirements.txt` to see the new file created with the current requirements for the virtual environment
- Run `pip install -r requirements.txt` to instantiate a new virtual environment based on the requirements file
- Run `deactivate` to deactivate the virtual environment
- Exclude the file name given to your virtual environment from your source control
