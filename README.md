# New Python project template

A minimal starting point for Python projects that run inside a VS Code dev container.

## What's included

- **`.devcontainer/`**: a dev container based on the official Python 3.12 image, with Git and the Python and Pylance VS Code extensions. It installs `requirements.txt` when the container is created and mounts your host `~/.gitconfig` so commits use your identity.
- **`main.py`**: a placeholder script that prints a message, to check the environment works.
- **`requirements.txt`**: empty, ready for your dependencies.

## Using it

1. Create a new repo from this template and open it in VS Code.
2. Choose **Reopen in Container** when prompted (requires Docker and the Dev Containers extension).
3. Run `python main.py` to confirm the setup, then replace it with your own code.
