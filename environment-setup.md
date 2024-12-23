1. Open cmd
2. Navigate to project directory:
```
cd D:\Projects\AI-bootcamp
```

### Setup conda virtual environment

```
conda create -n [env-name]
```
Or to create env with a specific python version:
```
conda create -n [env-name] python=3.12
```
Activate the environment that was just created
```
activate [env-name]
```

Install pip and other required packages
```
conda install pip 
pip install --upgrade tensorflow
pip install --upgrade pandas
pip install --upgrade matplotlib
pip install --upgrade seaborn
pip install --upgrade scikit-learn
```

Install ipykernel and associate a kernel to your virtual environment
```
pip install ipykernel
python -m ipykernel install --user --name=[env-name] --display-name "Python (any name)"
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

#### References
1. https://github.com/margaretmz/deep-learning/blob/master/setup-anaconda-jupyter-tf-keras.md
   
