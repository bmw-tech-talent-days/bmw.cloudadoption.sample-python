# bmw.cloudadoption.sample-python

## Prerequisites

1. [Visual Studio Code](https://code.visualstudio.com/)
2. [Docker Desktop](https://www.docker.com/products/docker-desktop/)

## Getting Started

1. Open the repo in VS Code.
2. Install the recommended "Dev Containers" extension.
3. When prompted to re-open the project in the remote container say yes. This will re-open the project in a container and all extensions should auto-install. This may take some time. You may have to "reload" vscode when it prompts you. If `pylance` is done
installing you can open up `sample.py` which will trigger the reload prompt. Alternatively, you can `CTRL+SHIFT+P` and run 
`Developer - Reload Window`.
4. If for some reason the Python dependencies fail to install please open a vscode terminal and run the `pipenv install --dev --deploy`.

### Running the sample application
In the "Run and Debug" tab, click run (or debug) on the "Python: Run Sample" configuration.

Take note of the phrase printed to the terminal. We may ask for this phrase on the tech talent day to verify
that your environment is properly setup.