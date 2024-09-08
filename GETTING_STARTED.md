# Gettting started with the "Fun with Quantum" notebooks


## Running the notebooks in Binder

The repository is Binder-ready and can be opened in any Binder service. Simply click on the button below to launch using [mybinder.org](https://mybinder.org/):

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/vabarbosa/Fun-with-Quantum/main)


## Running the notebooks locally

The notebooks can be run locally but will required a some additional steps to properly set up the local environment needed.


### Pre-requisites

- Depending on the notebook you may need an [IBM Quantum account](https://quantum.ibm.com/)
- [Python](https://www.python.org/) 3.11
- A local copy of the repo
    - [Fork the repository](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo?tool=webui)
    - [Clone your fork](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo?tool=webui)


### Setting up the local environment

From a terminal,

1. Go into the directory of your cloned repo

    ```
    cd PATH_TO_REPO
    ```

    where `PATH_TO_REPO` is the path to where you downloaded the repo locally

1. Create a virtual Python environment

    ```
    python -m venv env
    ```

1. Activate the virtual Python environment

   ```
   source env/bin/activate
   ```

1. Install JupyterLab

   ```
   pip install jupyterlab
   ```

1. Install dependencies

    ```
    pip install -r requirements.txt
    ```


### Starting the local environment

From a terminal,

1. Go into the directory of your cloned repo

1. Activate the virtual Python environment

   ```
   source env/bin/activate
   ```

1. Launch JupyterLab

    ```
    jupyter lab
    ```

JupyterLab will launch in a new browser page where you should see all the notebooks. You now can open up the notebooks and go through them. Enjoy!


### Stopping the local environment

Exit the JupyterLab browser page and them return the terminal window where you launched JupyterLab

1. Stop JupyterLab in the terminal by pressing `CTRL+C`, then press `y` followed by `Enter`

1. Deactivate the Python environment

    ```
    deactivate
    ```

You can follow the [`Starting the local environment`](#starting-the-local-environment) section whenever you want to run the local environment.
