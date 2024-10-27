I just use the single repo here now instead:

 https://github.com/purarue/cookiecutter-template

---

Cookiecutter template for a basic python library.

This is for packages that aren't meant to be pushed to pypi, they'd live on my github.

But it still uses `setuptools` so that the python package is importable from anywhere on the system.

Run:

```
cookiecutter gh:purarue/cookiecutter-lib
# to install
pip install --user ./package_name
# to install in editable mode, so changes to code update global package immediately
pip install --user -e ./package_name
```
