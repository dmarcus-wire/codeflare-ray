# CodeFlare on OpenShift

Codeflare and ray setup for distributed training on OpenShift

## Getting Started

As a cluster-admin you can import new notebook images.

Import the CodeFlare-Notebook image from `quay.io/project-codeflare/notebook:latest`
![images](docs/import-notebook.png)

Launch a `Terminal`
![images](docs/jupyter-terminal.png)

Git clone in the codeflare-sdk
![images](docs/clone-codeflare.png)

Get your cluster API token
![images](docs/cluster-token.png)
![images](docs/cluster-token-1.png)

Copy and Paste your oc login command
![images](docs/oc-login.png)

Upgrade pip and the latest codeflare
![images](docs/pip-install.png)

[!NOTE]
Import and add the following to mute the warnings
```
import warnings
warnings.filterwarnings('ignore')
```

See the documentation for the different examples