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
