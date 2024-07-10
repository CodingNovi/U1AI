# U1AI
Replicating the env: 
**Make and activate a venv then run:
conda create --name <name of your env>
conda env create -f environment.yml
conda activate myenv
pip install -r requirements.txt



Saving the env (when including new packages):
conda env export > environment.yml
pip freeze > requirements.txt