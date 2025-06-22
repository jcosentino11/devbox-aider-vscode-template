# devbox-project-vscode-template

This template creates an empty [devbox](https://www.jetify.com/docs/devbox/) project for use in vscode.

## Features

* On startup, opens shells with aider and devbox, side-by-side.

## First-time setup

Complete the following per machine:

* Install recommended vscode extensions defined in `.vscode/extensions.json`
* Install [devbox](https://www.jetify.com/docs/devbox/)
* Install [aider](https://aider.chat)
* (optional) [ollama](https://ollama.com), for local LLM models

## Customization

* Configure the local LLM model used by modifying the aider command in `.vscode/restore-terminals.json`
    * make sure to download the model as well, `ollama pull llama3.2`

## Helpful Docs

* https://www.jetify.com/docs/devbox/quickstart/
