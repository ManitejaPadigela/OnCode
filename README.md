# OnCode

Django Webapp project

## Getting Started

1. Clone the repository to local machine \
  `git clone https://github.com/ASLManasa/OnCode.git`

2. Create Virtual environment \
  `$ python -m venv .venv`
      or
  `virtualenv -p python3 .venv`
  *NOTE: If you have already a virtual environment then don't create one skip to step 3*

3. Activate the python virtual environment \
  **On Windows** \
  `c:\> .venv\bin\activate.ps1` \
  or 
  `$ cd .venv`
  `$ . Scripts/activate `
  `$ pip freeze`
 **On Linux** \
  `$ source ./.venv/bin/activate`

4. Install Requirements \
  `$ pip install -r requirements.txt`

5. Run the django server \
  `$ python manage.py runserver` \
  You will get following output:

  ```sh
  $ python ./manage.py runserver
  Watching for file changes with StatReloader
  Performing system checks...

  System check identified no issues (0 silenced).
  May 19, 2021 - 12:42:47
  Django version 3.2, using settings 'oncode.settings'
  Starting development server at http://127.0.0.1:8000/
  Quit the server with CONTROL-C.
  ```

  *Goto the given URL*
