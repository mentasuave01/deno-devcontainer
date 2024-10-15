 🦕 Deno Dev Container
---------------------

This repository provides a development environment for [Deno](https://deno.com/) using Visual Studio Code's [Dev Containers](https://containers.dev/).

## About Deno

Deno (/ˈdiːnoʊ/, pronounced dee-no) is an open source JavaScript, TypeScript, and WebAssembly runtime with secure defaults and a great developer experience. It's built on V8, Rust, and Tokio.

## Prerequisites

Before you begin, make sure you have the following tools installed on your system:
* [Visual Studio Code](https://code.visualstudio.com/)
* [Docker](https://www.docker.com/)
* [Docker Desktop](https://www.docker.com/products/docker-desktop/)


## Instalation

###1:

tl;dr: Just drop the .yaml release file into your project and docker desktop will do the rest for you on create

1. Download compose-dev.yaml file: https://github.com/mentasuave01/devcontainer-bun/releases/download/bun-devContainer/compose-dev.yaml
2. Copy it into the target repo/folder
3. Open docker desktop -> Dev Enviroments -> create 
4. Just point choice source to the repo you uploaded the .yaml file or the local folder it's in

###2:
1.Open your workspace and install [ms-vscode-remote.remote-containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)
2.reopen the project on container

## Additional Information

For more information on Bun, check out the official [Deno documentation](https://docs.deno.com/).

If you encounter any issues or have questions, please feel free to open an issue in this repository.

For more information on Visual Studio Code DevContainers, refer to the [official documentation](https://code.visualstudio.com/docs/devcontainers/containers).

## License

This project is licensed under the MIT License.

