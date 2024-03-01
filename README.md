# Implementing a Retrieval Augmented Generation pattern with OpenAI and OpenSearch

Create an [OpenSearch](https://opensearch.org/) datastore from wikipedia zipfiles to use with the OpenAI API for a Retrieval Augmented Generation pattern.

## Getting Started

This repo uses a jupyter notebook to walk through the process of creating an OpenSearch datastore in Aiven and searching against it using the OpenAI API.

### Setup your Aiven Account

You will need an [Aiven](https://aiven.io/) account. You can sign up for a

### [Option 1] Create a new codespace in GitHub

You can use the `code` button in the top right of the repo or the badge at the top of the readme to create a new codespace in GitHub. This will create a new environment with all the required dependencies to run the notebook.

### [Option 2] Setup the project locally

- fork the repo to your own GitHub account
- clone the repo to your local machine
- ensure Python is installed. You can download it from [python.org](https://www.python.org/downloads/) or use a package manager like [Homebrew](https://brew.sh/) on macOS, the Window Store on Windows, or your package manager of choice on Linux.
  ```shell
  python --version
  ```
- create a virtual environment based on your [operating system](https://docs.python.org/3/library/venv.html)
- install the dependencies

  You can install the python dependencies using pip.

  ```shell
  python -m pip install -r requirements.txt
  ```

### Follow the notebook

Follow the steps in [`notebook.pynb` 🔗](./notebook.pynb).:> [!WARNING]
