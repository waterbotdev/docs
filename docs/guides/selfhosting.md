hero: Guides - Selfhosting Setup

# Selfhosting

Again, I would prefer you to not host this bot yourself, as there are a lot
of configurations to do. If you still want to proceed, follow the steps.

## Prerequisites

You need a working PC/Server/Laptop(Obviously) and a Python 3 interpreter.

### Check your python version

You need to check if your python is in one of the [supported python versions](#supported-python-versions)

!!! danger
    Python 2 will **NOT** be supported.

If you do not have python installed, you can use a pre-packaged standalone application(Windows only)
by going to https://github.com/waterbotdev/waterbot/releases

If you are on MacOS and you don't have Python installed, install one of the 
[supported versions](#supported-python-versions) by downloading it from 
[here](https://www.python.org/downloads/mac-osx/)

If you are on a Linux machine, I suggest you install pyenv as it is guaranteed to work.

If you already have pyenv, or you don't want to use pyenv, you can skip this step.

#### Installing Pyenv
To install pyenv, run the following command.
```bash
curl https://pyenv.run | bash # Downloads and run the pyenv setup script.
```
Then, depending on your configuration, the following warning might occur.
```
WARNING: seems you still have not added 'pyenv' to the load path.

# Load pyenv automatically by adding
# the following to ~/.bashrc:

export PATH="/home/test/.pyenv/bin:$PATH"
eval "$(pyenv init -)"
eval "$(pyenv virtualenv-init -)"
```

### Installing dependencies

You can install the dependencies by opening up a command prompt(Windows) or a Terminal(MacOS/Linux)
and type
```bash
pip install -r requirements.txt
```

### Supported Python versions
|  /  |3.8|3.7|3.6|3.5|3.4|3.3|
|-----|:-:|:-:|:-:|:-:|:-:|:-:|
|0.1.0| X | X | X | X |   |   |
|0.0.5|   | X | X | X | X | X |