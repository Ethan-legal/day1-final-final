1. Create README.md file for taking notes

## SAVING CODE
1. On LHS of screen, go to "source control"
2. client to add files to the commit (i.e., stage changes)
3. Enter a commit message (anything)
4. click "Commit"
5. click "sync changes"
6. check GitHub repository to confirm

## SETTING UP ENVIRONMENT (IN TERMINAL)
1. create virtual environment
> python -m venv .venv
2. activate virtual environment
> source .venv/bin/activate
3. to install libraries / dependencies, first create a requirements.txt file
4. add openai, streamlit, python-dotenv to requirements.txt file
5. install dependencies by referring to requirements.txt file
> pip install -r requirements.txt
6. create a .env file
7. ensure .env file is grayed out (git ignored) - if not edit .gitignore to include .env
8. add secrets to .env
> OPENAI_API_KEY = "<insert>"

#