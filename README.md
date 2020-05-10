# taq

Backend for queueing system for TA help.

## Development

### Setup
This project uses Python 3.8 and will most likely be incompatible with previous versions. We recommend using `pyenv` to install the latest version of Python 3.8.

After cloning the repo and changing into the directory, use `pyenv local 3.8.x` (where x is whatever version you have) to set the python version for the directory to be `3.8.x`. Then use `python -m venv x` (where x is the name of your virtual environment) to create your virtual environment and then activate it. Next, if Poetry is not already installed, you will need to install it. Then run `poetry install`. Finally, run the tests to make sure everything is working as expected. Great, now you're ready to develop!

### Formatting and code style
This project uses the black formatter with line length set to 99 and string normalization turned off. We generally use single quotes, except in docstrings and strings that are meant to be outputted, for example, logging and exceptions. Note that developers need not run the formatter on their code, as once a commit is pushed, the CI pipeline will run the formatter automatically.

### Committing changes
Read [this](https://chris.beams.io/posts/git-commit/) before committing anything.

### Testing
Make sure any newly added or modified code has well-written, passing tests associated with it. We use pytest as our testing library.