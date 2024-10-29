# Jenkins Pipeline Project

This project demonstrates a Jenkins pipeline that performs various stages including spell check, Python code quality check, shell check, running tests, building a Docker container, and pushing the image to Docker Hub.

## Project Structure

- **details-app**: Contains the application code, Dockerfile, and tests.
- **docker**: Contains Docker Compose and Dockerfiles for Jenkins main and worker containers.
- **Jenkinsfile**: Defines the Jenkins pipeline.

## Pipeline Stages

1. **Spell Check**: Runs spell check using `codespell`.
2. **Python Code Quality Check**: Runs code quality checks using `pylint`.
3. **Shell Check**: Runs shell script checks using `shellcheck`.
4. **Run Tests**: Executes tests using `pytest`.
5. **Build Container**: Builds a Docker image for the application.
6. **Push to Docker Hub**: Pushes the Docker image to Docker Hub.

## Authors

- Danor Sinai (responsible for spell check, code check, and shell check)
- Yossi Avni (responsible for runing the pytests and docker builds parts)

- [Install file](INSTALL.md)
- [Contributing](CONTRIBUTIONS.md)
