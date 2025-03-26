![Flask Logo](https://upload.wikimedia.org/wikipedia/commons/3/3c/Flask_logo.svg)
# Flask Registration & Log

## Setup and Installation

### Create and Activate Virtual Environment
```sh
python -m venv env   # Create a virtual environment named 'env'
```
### Install requuirements 
```sh
python -r install requirements.txt   # Create a virtual environment named 'env'
```

#### Activate the virtual environment:
**Windows (PowerShell):**
```sh
.\env\Scripts\Activate.ps1
```
**Windows (Command Prompt):**
```sh
.\env\Scripts\activate
```
**Mac/Linux:**
```sh
source env/bin/activate
```

### Install Dependencies
```sh
pip install flask
pip install flask-cors
pip install mysql-connector-python
```

### Running the Application
```sh
python app.py  # Start the Flask web app
```

## Common Errors & Solutions

### Virtual Environment Activation Issue
**Error:**
```sh
PS C:\Users\YD01\flask_auth_system\venv\Scripts> .\Activate.ps1
```
**Solution:**
If you're using PowerShell and see an error related to execution policies, try running:
```sh
Set-ExecutionPolicy Unrestricted -Scope Process
```
Then, activate the environment again.

## Project Structure
```
flask_auth_system/
│-- env/                  # Virtual environment
│-- app.py                # Main Flask application
│-- requirements.txt       # List of dependencies
│-- static/               
│   ├── css/              
│   └── js/              
│-- templates/            # HTML files
└── README.md             # Project documentation
```

## Notes
- Ensure your virtual environment is activated before running commands.
- Update `requirements.txt` by running `pip freeze > requirements.txt` to save installed dependencies.

## License
This project is licensed under the MIT License.

