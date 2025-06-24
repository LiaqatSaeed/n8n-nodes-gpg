# n8n-nodes-gpg

🔐 Encrypt and decrypt files using GPG via system-level CLI within your n8n workflows.

## Features
- GPG Encrypt: Encrypt any file with a public key
- GPG Decrypt: Decrypt a file using a private key and passphrase
- Powered by the `Execute Command` wrapper with GPG CLI

## Requirements
- GPG must be installed on the server/container where n8n runs  
- Test GPG with: `gpg --version`

## Usage
Drag the `GPG` node into your n8n workflow and configure:
- Operation: Encrypt / Decrypt
- File path (input/output)
- Key or passphrase

> ⚠️ For serverless or container installs, use a custom Docker image with GPG pre-installed
