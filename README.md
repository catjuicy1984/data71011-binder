# DATA71011 Week 5: basic Binder setup

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/catjuicy1984/data71011-binder/main?urlpath=%2Fdoc%2Ftree%2Fenvironment_check.ipynb)

This example contains synthetic data only. No survey responses, personal data or assessed PROV work are included.

## Run

Click the Binder badge, then use Run > Run All Cells in environment_check.ipynb.
Expected x values: 0, 1, 2, 3, 4. Expected y values: 0, 1, 4, 9, 16.
You can also run `python hello.py` in a terminal.

## Environment

requirements.txt pins NumPy, pandas and Matplotlib. runtime.txt sets the Python major/minor version.
These files do not lock all transitive dependencies or operating-system packages.
For an immutable source version, replace main in the Binder URL with a commit SHA.

## Save your work

Binder sessions are temporary. Download changed notebooks and commit them back to GitHub before leaving.

## Sources

- Course workshop: https://canvas.manchester.ac.uk/courses/86354/modules/items/4145552
- Tutorial: https://book.the-turing-way.org/communication/binder/zero-to-binder/
