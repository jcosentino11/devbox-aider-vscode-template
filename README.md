# devbox-aider-vscode-template

Template for new vscode projects that uses [devbox](https://www.jetify.com/docs/devbox/) for nix-based dependency management.

Includes console integration with [aider](https://aider.chat) for easy LLM usage within the project window.

https://github.com/user-attachments/assets/5737e02a-55ce-4120-b184-8b2966bdce2d


## One-time setup

Install the following if not already on your machine:

* [devbox](https://www.jetify.com/docs/devbox/)
* [aider](https://aider.chat)
* vscode extensions from `.vscode/extensions.json`

## Project Setup

### Aider (Console AI Agent)

* Add API keys to a `.env` file (see `.env.example`)
* Add [model](https://aider.chat/docs/llms.html) to an `.aider-model` file (see `.aider-model.example`)

## Usage

1) Open your project in vscode
2) cmd+shift+p, `Devbox: Reopen in Devbox shell environment`

## Helpful Docs

* https://www.jetify.com/docs/devbox/quickstart/
