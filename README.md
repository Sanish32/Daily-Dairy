# Daily-Dairy
Learning related to configuration will be noted for solving same problems in the future.

# Purpose
As the technologies and cool features are on demand, its very common for netizens to activate `monk mode` on the primary targets such as studies, researches, or the work. This leaves many of us to ignore/slack on basic technicalities, especially configurating system components or pipelining several steps to achieve technical problems. 

Thus, I created a short and sweet description on several technical issues that I encountered. Keeping this dairy helps me to troubleshoot me in the future if I faced same problem again. 

If the description starts to expand, several ways of maintainance will be considered in future. 

## How to create and use virual environments in Python! (on Mac)
-> First, open the terminal.
-> Go to ur project folder.
-> Type 'python3 -m venv env' (tells the command to be run using python3. ii) `-m` flag tells the module should be run as scripts. iii) `vent` is just a module in python that allows to create virtual environments. iv) `env` is the name of the environmemt that I am about to create (honestly, this can be replaced with other names for convenience)

Once the virtual environment is created, it requires to be activated for use.
-> In terminal, type `source env/bin/activate`
You will see `(env) (base) lm3-500-28802:folder_name username $`

For deactivation of the virtual environment, type `deactivate` in the terminal. 
You will see `(base) lm3-500-28802:folder_name username $`

To use specific modules/packages in the virtual environment, install them first!
PIP (Preferred Installer Program) command is used to install such packages.

To see all the packages in the current virtual environment, type `pip list`. Then, all the packages in the current virtual environment will be shown.

## To save all the versions of the packages in the text file!
-> Type `pip freeze > requirements.txt` ( i)`pip freeze` outputs all the packages along with their versions, ii)`>` is a shell operator which takes the output from the left side and writes it to the `requirements.txt` file )

## Let's create another virtual environment.
-> So, deactivate whatever virtual environment is running/activating. 
-> Then, create new virtual environment by typing `python3 -m venv my_env`
-> Now, as usual, type `source my_env/bin/activate` to activate the virtual environment.
-> Now, typing `pip list` does not show all the packages that was installed in the previous virtual environment. 
-> To install the packages that were installed in the previous virtual environment (`env`), type `pip install -r requirements.txt`. (`pip install` install the package(s) that is(are) mentioned after `pip install`. ii)`-r` flag stands for requirements and install the packages listed in next txt)


# To see if I belong to grp-cubbli-ssh-access at UH.


