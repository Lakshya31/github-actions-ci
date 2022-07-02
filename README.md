# github-actions-ci
CI training with GitHub Actions

This project is for my training of CI using Github Actions


[![Python application test with Github Actions](https://github.com/Lakshya31/azure-ci-cd/actions/workflows/main.yml/badge.svg)](https://github.com/Lakshya31/azure-ci-cd/actions/workflows/main.yml)


Running Instructions:

Install Python 3.7 & install basic dependencies (pip, pyvenv, pylint, pytest)
- Create a virtual environment using `make setup`
- Activate the virtual environment by running activate.sh in your virtual env directory
- Install Dependencies using `make install`
- Run Lint Test using `make lint`
- Run Test using `make test`
- Run `make all` for install, lint and test in 1 command

GitHub Actions:

Any updates pushed to Repo will trigger GitHub Actions, which runs `make install`, `make lint` and `make test` and updates status in the badge above. This ensure quality code and is a very small scale implementation of Continuous Integration.


Actions Running Successfully:

![image](https://user-images.githubusercontent.com/47375693/176997052-5b734c4c-44d7-4208-918b-d872eb6b86d5.png)
