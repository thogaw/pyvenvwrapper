# Pyvenv Wrapper
Simple wrapper tool to simplify the interaction with pyvenv.

This tool is my effort to simplify the usage of the pyvenv tool for python development. It will get new/more features as required or requested.

At the moment the wrapper is implemented as simple as possible. It has no error
handling or logging.

## Installation
For installation please clone the repository into a local directory. For example
`~/.venv`

```bash
git clone git@github.com:thogaw/pyvenvwrapper.git ~/.venv
echo "source ${HOME}/.venv/bin/pyvenvwrapper" >> ~/.bashrc
```

After editing your `~/.bashrc` you have to restart your terminal, so the wrapper scripts are processed.

## Usage
After installing the wrapper script your bash has two functions registered.

- create_env
- activate_env

Each function expects the environment name as parameter.

## Contribution
If you want to contribute. Feel free to fork and file a pull-request. Or file an issue at the repositories issue-tracker.
