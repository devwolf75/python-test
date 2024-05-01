# Basic Pytest Module

##### This is a template project for running only tests of a given module or API.

To run simply install `requirements.txt` into your local environment or virtual environment. Run with `python -m pytest` in order to execute the test suite and all of the test cases.

To run a single test directory, use `python -m pytest ./tests/<directory>`. This will exclude any other folder for the report.

To configure a test suite for Jenkins, copy the base Jenkinsfile groovy from `groovy-files` to its own separate file and configure as needed.

Use `.env` file to specify the environment to test and configure the application or module for local execution.
