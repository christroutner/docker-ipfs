# docker-ipfs

This repository contains a docker-compose file for starting an instance of go-ipfs inside a Docker container. This is a proof-of-concept, used to build more sophisticated software around the IPFS Docker container.

This docker container expects two folders to exist in the directory above it:

- `data` is used to persist data used by IPFS, like blocks and configuration data.
- `export` is used to hold files that you want to make available via the IPFS network.

[More information on running IPFS inside Docker can be found here](https://docs.ipfs.io/how-to/run-ipfs-inside-docker/).
