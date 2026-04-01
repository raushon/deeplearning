# deeplearning

# Create a virtual environment named 'venv'

python3 -m venv venv

# Activate the virtual environment

source venv/bin/activate

# Upgrade pip

pip install --upgrade pip

# Install required packages for your notebook

pip install numpy pandas tensorflow scikit-learn jupyter

# Command to get new kernel for jupyter and resolve conda conflict

source venv/bin/activate && pip install ipykernel && python -m ipykernel install --user --name venv --display-name "Python (venv)"

# to dactivate conda environment

conda deactivate
