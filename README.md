# Homebrew Tap for Ink

[Ink](https://ml.ink) is a cloud platform designed for AI agents to deploy and manage services autonomously. It makes deployments simple enough that fully autonomous agents can handle the entire lifecycle — create, deploy, monitor, and scale services without human intervention.

This repository contains Homebrew formulae for Ink tools.

## Install

```bash
brew install mldotink/tap/ink
```

## Usage

```bash
ink login
ink deploy my-app --repo my-repo --port 3000
ink list
ink status my-app
ink logs my-app
```

For more information, visit [ml.ink](https://ml.ink).
