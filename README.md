# Reference files

Templates for projects.

Any suggestions for improvements are welcome via issues or pull requests.


## Dockerfiles

Templates for common Docker builds:

* Set up a Python Flask project for use in development or production (`Dockerfile.flask`)
* Build a Hugo project and put it in an nginx container (`Dockerfile.hugo`)
* Set up a Quasar project for development or production (`Dockerfile.quasar`)


## Github Workflows

Templates for common workflows:

* Perform a codeql analysis on a code base (`codeql-analysis.yml`)
* Build and publish Docker images (`docker.yml`)
* Build and publish of Docker images for multiple platforms (`docker-multiarch.yml`)
* Build and publish Docker images including security check by Trivy, do not publish if there are issues (`docker-security-reject.yml`)
* Build and publish Docker images including security check by Trivy, add issues to the security tab (`docker-security-warning.yml`)
* Perform a check for license issues using Fossa (`fossa.yml`)
* Perform a python code scan using `black` with line width 100; `-l 100` (`python-black.yml`)
* Perform a time-based check with Trivy of existing images (`trivy.yml`)
