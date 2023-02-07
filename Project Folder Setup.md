# Project Setup

- Make a directory to store your project (`mkdir directory_name`)

- Make the newly created folder your current working directory  (`cd directory_name`)

- Create a virtual environment using `venv`
  
  - **Windows**: `python -m venv env` where `env` is the name of the folder where the virtual environment will be stored inside your new project folder (_note: this may take some time; be patient_)

- Activate your new virtual environment `env` from inside your project directory to ensure you are using it for your project
  
  - **Windows**: `env\Scripts\activate`
  
  - Your command prompt will begin with the virtual environment name if you have successfully activated your environment (i.e., `(env) C:\Users\User_Name\..\directory_name`)

- Install any Python modules needed
  
  - Check which modules are already installed by typing `pip freeze`; should be none as you just created the new virtual environment.
  
  - **Django**
    
    - **Windows**: Inside project directory and with the virtual environment running, type `python -m pip install Django` 

- Create/Update list of installed Python modules (_requirements.txt_)
  
  - Inside project directory and with the virtual environment running, type `pip freeze > requirements.txt`. This will save all currently installed modules/libraries with versions into the `requirements.txt` file.
* When done working, make sure you remember to deactivate by typing `deactivate` in the command prompt or console
