# LooprProject
Develop a defect detection system for carbon fiber products using this dataset https://www.kaggle.com/datasets/nexuswho/aitex-fabric-image-database


## create python venv

## syntax
python3 -m venv <virtual environment name>

## example that would create a virtual environment named 'myenv'
python3 -m venv myenv

## activate
source <virtual environment name>/bin/activate


## install packages using pip
pip install -r requirements.txt


## create ipykernel

## syntax
python3 -m ipykernel install --user --name=<projectname>


## example that would create a kernel named 'myproject'
python3 -m ipykernel install --user --name=myproject

## download data from kaggle
https://www.kaggle.com/datasets/nexuswho/aitex-fabric-image-database
archive file should be sibling to the notebook folder in the LooprProject folder

run all cells in the demo notebook to train and view kfolds cross validation