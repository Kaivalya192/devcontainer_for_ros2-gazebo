# ros2_ws with docker using vscode devcontainer

**if you want to use GPU**

Modify .devcontainer/devcontainer.json
```json
  "runArgs": [
    "--privileged",
    "--gpus all"
  ],
```