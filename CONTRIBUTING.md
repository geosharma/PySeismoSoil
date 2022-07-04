# Contributing Instructions

- In general, contributors should make code changes on a branch, and then [create a pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request) to have the changes merged
- It is strongly recommended that contributors work on code changes in an isolated Python environment
    + Use `pip install -e .` to install this library locally, so that any local code changes are reflected immediately in your current Python environment
- To make sure your code style is compliant, run `./run_linting.sh` locally on your computer to check style violations
    + You might want to run `chmod +x run_linting.sh` to make `run_linting.sh` executable
- Please also run all unit tests by running `./run_tests.sh` before committing code to GitHub
    + You might want to run `chmod +x run_tests.sh` to make `run_tests.sh` executable
- Even if you don't run unit tests and check code styles locally, unit tests and code styles are checked on every push at GitHub