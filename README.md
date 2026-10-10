# OpenClaw Local AI Agent Demo

A hands-on experiment running OpenClaw with a local Ollama model inside Ubuntu Linux on VMware.

<img width="1600" height="1041" alt="image" src="https://github.com/user-attachments/assets/a012b3b9-c1d4-4c6e-b37c-23cca25b83f4" />


## Overview

This project documents my experience setting up a locally running AI agent and testing its ability to interact with the Linux desktop environment.

The goal was to explore how a local AI agent can interpret instructions, execute file operations, and verify results without relying on a cloud-based language model provider.

## Environment

- **Operating System:** Ubuntu Linux
- **Virtualization:** VMware running on Windows 11
- **AI Agent:** OpenClaw
- **Local Model Runtime:** Ollama
- **Model tested:** Llama 3.1 8B
- **Hardware:** AMD Ryzen 5 4600H, NVIDIA GeForce GTX 1660 Ti 6 GB VRAM, 16 GB system RAM

## Demonstration

The initial experiment involved asking OpenClaw to create a text file on the Ubuntu Desktop.

The resulting file, `dem1.txt`, was visible on the desktop and verified through its file properties.

**File location:**

```text
/home/rauf/Desktop/dem1.txt
```

This demonstrated a basic file-creation workflow. Further testing is needed to evaluate reliability, execution time, and more advanced agent operations.

## Goals

- Run an AI agent locally using Ollama.
- Connect OpenClaw to a local language model.
- Test command execution on Ubuntu Linux.
- Verify file operations performed by the agent.
- Investigate model performance, context limits, and resource usage.

## Getting Started

Install and configure Ollama and OpenClaw according to their official documentation.

1. Install Ollama and download a supported model.
2. Install OpenClaw.
3. Configure OpenClaw to use the local Ollama provider.
4. Start a new agent session.
5. Test a simple file operation and verify the result in the Linux filesystem.

## Privacy and Security

This project is intended for local experimentation. Keep API keys, authentication tokens, personal configuration files, and private conversation logs out of the repository.

Review all files before pushing them to GitHub.

## Status

**Proof of concept — in progress.**

This repository documents an initial local AI agent experiment and will be updated as additional tests and improvements are completed.
