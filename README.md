# Docker image for ivos/citeproc-js-server

## Usage

To create the docker image execute the following commands:

```bash
git clone https://github.com/ivos/citeproc-js-server-docker.git
cd citeproc-js-server-docker
docker build -t myciteproc .
```

To start the docker image execute the following command:

```bash
docker run -d -p 8085:8085 -t myciteproc
```
