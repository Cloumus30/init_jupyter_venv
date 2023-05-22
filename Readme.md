# Installation  After Cloning
1. running or execute **setupvenv.sh** to set Python virtual environtment

2. execute **python_venv/bin/activate** to activate virtual environtment

3. running <code>pip install -r requirements.txt</code> to install library

4. running <code>python -m ipykernel install --name={your kernel name}</code> to register kernel into jupyter notebook

5. check kernel with <code>jupyter kernelspec list</code>, if your kernel name exist, it means that kernel already registered

6. run <code>jupyter notebook</code> and change kernel into imageclassiflatihan, and congrats start coding.


NB: After Installing a new library run <code>pip freeze > requirements.txt</code> to syncron library list into requirements.txt file