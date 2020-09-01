# cookiecutter-lib

Cookiecutter template for a basic python library.

This is for packages that aren't meant to be pushed to pypi, they'd live on my github.

But it still uses `setuptools` so that the python package is importable from anywhere on the system.

Run:

```
cookiecutter gh:seanbreckenridge/cookiecutter-lib
cd package_name
# to install
pip install --user ./package_name
# to intall in editable mode, so changes to code update global package immediately
pip install --user -e ./package_name
```
