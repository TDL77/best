# Release checklist

- GitHub issues attended to
- version number upgraded (in `setup.py`)
- changelist updated
- locally built docs aren't obviously broken (`cd docs && make html` and check API page)
- pushed to GitHub
- docs are (automatically) updated on best.readthedocs.io
- delete old build files (see UPGRADE.txt)
- build new package
- release new package
- new package available on PyPI
- add a release message to the tag on GitHub
