# flake8 Demo

From [this article][1]:

> "[flake8] is a great toolkit for checking your code base against coding style (PEP8), programming errors (like “library imported but unused” and “Undefined name”) and to check cyclomatic complexity."

- [flake8 on GitHub][1]
- [flake8 docs][2]
- [PEP 8 -- Style Guide for Python Code][3]

## Installation of flake8

- `conda install -c conda-forge flake8`
- `pip install flake8`
- `pipenv install --dev flake8; pipenv shell`

## Usage

Run from root of a Python project:

`flake8`

Run on a specific file:

`flake8 app.py`

Run with options (ignoring certain errors, changing settings):

`flake8 --max-line-length=119 --ignore=F401 --exclude=tests`

Options can be set in a config file (see `.flake8-example`)

## License

The `secrets.py` and `secret-edited.py` are derived from `secrets` module file
in the Python source code. [License][4]

Everything else:

***********************************************************  
"THE BEER-WARE LICENSE" (Revision 42):  
<ccl@chrisleonard.com> wrote this file.  As long as you retain this notice you
can do whatever you want with this stuff. If we meet some day, and you think
this stuff is worth it, you can buy me a beer in return.
***********************************************************

[1]: https://simpleisbetterthancomplex.com/packages/2016/08/05/flake8.html
[2]: https://github.com/PyCQA/flake8
[3]: https://flake8.pycqa.org/en/latest/
[4]: https://www.python.org/dev/peps/pep-0008/
[5]: https://github.com/python/cpython/blob/main/LICENSE
