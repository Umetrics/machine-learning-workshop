# machine-learning-workshop
Material for Machine Learning workshops

To get started using when using conda on Windows:

```
conda env create -f environment.yml
activate umejug-env
jupyter notebook
```

To get started using when using conda on non-Windows:

```
conda env create -f environment.yml
source activate umejug-env
jupyter notebook
```

To get started using Python and virtualenv on non-Windows:

``` 
virtualenv umejug-env
source umejug-env/bin/activate
pip install -r requirements.txt
jupyter notebook
```

To get started using Python and virtualenv on Windows:

``` 
virtualenv umejug-env
umejug-env\Scripts\activate.bat
pip install -r requirements.txt
jupyter notebook
```

Python with venv

```
python -m venv c:\umejug-env
c:\umejug-env\Scripts\activate.bat
pip install -r requirements.txt
jupyter notebook
```
