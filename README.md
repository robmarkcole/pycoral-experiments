# pycoral-experiments
Experiment with PyCoral API


## Development Mac
Note: important to use USB-C to USB-C cable. Had some connection issues initially documented in [this issue](https://github.com/google-coral/pycoral/issues/35)

* python3 -m venv venv
* source venv/bin/activate
* pip install -r requirements.txt
* python3 -m pip install --index-url https://google-coral.github.io/py-repo/ --extra-index-url=https://pypi.python.org/simple pycoral
* venv/bin/jupyter lab
