1. Open cmd
2. Navigate to project directory:
   cd D:\Projects\AI-bootcamp
-------------------------------------------------------
### Setup conda virtual environment

```
conda create -n [env-name]
```
Or to create env with a specific python version:
```
conda create -n [env-name] python=3.12
```
```
activate [env-name]
conda install pip 
pip install --upgrade tensorflow
pip install --upgrade pandas
pip install --upgrade matplotlib
pip install --upgrade seaborn
pip install --upgrade scikit-learn
```
```
pip install ipykernel
python -m ipykernel install --user --name=[env-name] --display-name "Python (ai-env)"
jupyter notebook 
```
To list all the installed packages in the virtual environment
```
conda list
```

### Activate/Deactivate Virtual environment
```
conda activate [env-name]
conda deactivate
```
