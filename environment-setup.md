1. Open cmd
2. Navigate to project directory:
   cd D:\Projects\AI-bootcamp
-------------------------------------------------------
Setup conda virtual environment

conda create -n ai-env #OR create env with a specific python version: conda create -n ai-env-312 python=3.12
activate ai-env
conda install pip 
pip install --upgrade numpy
pip install --upgrade pandas
pip install --upgrade matplotlib
pip install --upgrade seaborn
pip install --upgrade scikit-learn
pip install --upgrade keras
pip install ipykernel
python -m ipykernel install --user --name=ai-env --display-name "Python (ai-env)"

jupyter notebook 
-------------------------------------------------------
Activate/Deactivate Virtual environment
conda activate ai-env
conda deactivate
