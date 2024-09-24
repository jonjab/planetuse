Make sure to run this notebook in a virtual environment.

source .venv/bin/activate

on Windows, use .venv\Scripts\activate to active the venv

The benefit of this is all your dependencies are installed to the project directory, nothing except python on the system itself.
Don't forget to run 'deactivate' to the leave the venv

The .venv directory is .gitignored 


mkdir my-project
cd my-project
python -m venv .venv
source .venv/bin/activate
pip install jupyter
