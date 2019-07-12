## Instructions
```python
# In a directory, make a virtual environment (requires Python version >= 3.3)
python3 -m venv venv
# activate shell of venv
. ./venv/bin/activate 
# (optional) verify that the executable runs from venv
which pip 
# install the required python packages on venv
pip install -r requirements.txt
# enable jupyter server on port 8888, specifically for intro.ipynb
jupyter notebook intro.ipynb
# deactivate shell of venv
deactivate 
```
