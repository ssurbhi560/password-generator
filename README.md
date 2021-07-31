# Password Generator

This website generates random passwords.
    
## Setup locally using virtual environment
1. Clone the repo (or fork if you plan to contribute).

	- To just test the site:
		  `git clone https://github.com/ssurbhi560/password-generator`

	- To enable contributions and send PRs:
		`git clone <url-of-fork>`

2. `cd` to the directory you wish to have your project in, and run `python3 -m venv venv` (the latter venv in the command is name of your virtual environmnet)

3. Activate it by `source venv/bin/activate`. You may use any other name than `venv`, but make sure to use the same name while activating the virtual environment.

4. Run `pip install --upgrade pip` to, as expected, upgrade pip, and then install the dependencies by:
> `pip3 install -r requirements.txt`

5. Now `cd` to the directory where you cloned `password-generator`, and (ensure virtual environmnet is activated and `manage.py` file is in your current folder) run the following commands after that :
> `python3 manage.py runserver` 

6. Open your browser and search for `localhost:8000`, and hit enter. 

6. Some of the links might be broken since it's still under development.

So, manually change the URL to whatever route you like.
Refer to `urls.py` for all urls available, and manually change the URLs to navigate.

## Useful links
  - [venv](https://docs.python.org/3/library/venv.html#module-venv)