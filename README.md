# Reference files

Templates for projects from SciLifeLab Data Centre.

Any suggestions for improvements are welcome via issues or pull requests.

## Github Workflows

Templates for common workflows:

* Build and publication of Docker images (`docker.yml`)
* Perform a python code scan using `black` with line width 100; `-l 100` (`python-black.yml`)
* Perform a codeql analysis on a code base (`codeql-analysis.yml`)

## Dockerfiles

Templates for common Docker builds:

* Build a Hugo project and put it in an nginx container (`Dockerfile.hugo`)
* Set up a Python Flask project for use in development or production (`Dockerfile.flask`)
* Set up a Quasar project for development or production (`Dockerfile.quasar`)
