# What is this project?
This is an app that creates PDF invoices out of Excel files.


## Upload packages to pypi
```commandline
    write setup.py
    python setup.py sdist
    pip install twine
    twine upload --skip-existing dist/*
```