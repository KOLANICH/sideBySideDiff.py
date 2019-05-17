sideBySideDiff.py [![Unlicensed work](https://raw.githubusercontent.com/unlicense/unlicense.org/master/static/favicon.png)](https://unlicense.org/)
==================
[![PyPi Status](https://img.shields.io/pypi/v/sideBySideDiff.svg)](https://pypi.org/project/sideBySideDiff)
[![GitLab Build Status](https://gitlab.com/KOLANICH/sideBySideDiff.py/badges/master/pipeline.svg)](https://gitlab.com/KOLANICH/sideBySideDiff.py/pipelines/master/latest)
![GitLab Coverage](https://gitlab.com/KOLANICH/sideBySideDiff.py/badges/master/coverage.svg)
[![Coveralls Coverage](https://img.shields.io/coveralls/KOLANICH/sideBySideDiff.py.svg)](https://coveralls.io/r/KOLANICH/sideBySideDiff.py)
[![Libraries.io Status](https://img.shields.io/librariesio/github/KOLANICH/sideBySideDiff.py.svg)](https://libraries.io/github/KOLANICH/sideBySideDiff.py)


This is a library to create 2-way side-by-side diffs and show them in CLI using ANSI color codes.

Requirements
------------
* [`Python >=3.4`](https://www.python.org/downloads/). [`Python 2` is dead, stop raping its corpse.](https://python3statement.org/) Use `2to3` with manual postprocessing to migrate incompatible code to `3`. It shouldn't take so much time. For unit-testing you need Python 3.6+ or PyPy3 because their `dict` is ordered and deterministic.

* [`RichConsole`]( https://gitlab.com/KOLANICH/RichConsole.py) [![PyPi Status](https://img.shields.io/pypi/v/RichConsole.svg)](https://pypi.org/pypi/RichConsole)
[![GitLab Build Status](https://gitlab.com/KOLANICH/RichConsole.py/badges/master/pipeline.svg)](https://gitlab.com/KOLANICH/RichConsole.py/pipelines/master/latest)
[![Coveralls Coverage](https://img.shields.io/coveralls/KOLANICH/RichConsole.py.svg)](https://coveralls.io/r/KOLANICH/RichConsole.py)
![GitLab Coverage](https://gitlab.com/KOLANICH/RichConsole.py/badges/master/coverage.svg)
[![Libraries.io Status](https://img.shields.io/librariesio/github/KOLANICH/RichConsole.py.svg)](https://libraries.io/github/KOLANICH/RichConsole.py)
[![Unlicensed work](https://raw.githubusercontent.com/unlicense/unlicense.org/master/static/favicon.png)](https://unlicense.org/) - a lib to style console output via control codes.
