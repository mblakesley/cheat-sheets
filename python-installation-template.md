## First-time setup

1. Clone the repo & `cd` into it
2. Install python \<version> via pyenv
   1. Install `pyenv` (via APT, Homebrew, whatever)
   2. Run `pyenv install` to install python \<version> (specified in the file `.python-version` for pyenv to read)
   3. Run `pip -V` to confirm that python \<version> is now in use. The pathname in the output should show the `.pyenv` directory.
3. Create & activate a python virtual environment
   1. Run `python -m venv .venv` to create a virtualenv in the dir `.venv`
   2. Run `source .venv/bin/activate` to activate the virtual env
   3. Run `pip -V` to confirm the virtualenv is in use. The pathname in the output should show the `.venv` directory.
4. Install dependencies in the virtual env
   1. Run `pip install -r requirements.txt` to install packages in the virtual env

Now an IDE can find & use this virtual environment.

Note: Run `deactivate` to exit the virtual environment.
