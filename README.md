# ML-Project-2-End-to-End-MLOps-with-MLFlow-
This is an end to end ML project with MLflow
- Create a github repo, add .gitignore file ( python template ), add MIT license, make it public and write a short description
- Clone it in your local
-----------------------------------------------
1. Open your project folder in vscode
2. Create a template.py file ( for automation )
3. Create an environment with conda
- conda create --name mlproj
- conda activate mlproj
4. Run the template.py file 
- python3 template.py ( for mac )
- python template.py ( for windows )
5. Commit the latest code ( folder structure added )
6. Create the requirements.txt file and paste your dependencies
7. In the setup.py file write the code logic and run the command
- pip install -r requirements.txt

---------------CREATE LOGGING---------------------
8. Inside the src -> mlProject -> __init__.py file write your logging code and create a logger variable
9. In the main.py file test the logger object
from src.mlProject import logger
logger.info("Welcome to our custom logging")
Run the file, it should show logs in both the console and the logs folder

-------------------CREATE Utils ----------------------
10. Inside the utils/common.py write the utility functions that you will use often
11. Push the code to github