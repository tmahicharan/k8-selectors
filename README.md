# k8-selectors

## Overview

Kubernetes scheduling examples involving taints, tolerations, node affinity, and pod affinity.


## Key Contents

The following file list is generated from the current local repository snapshot. It excludes common dependency folders and files that appear to contain credentials or private keys.

```text
01.taint.yaml
02-toleration.yaml
03-node-affinity.yaml
04-node-antiaffinity.yaml
05-pod-affinity.yaml
06-pod-antiaffinity.yaml
07-usecase.yaml
```

## Technologies

Kubernetes, Scheduling, YAML

## Getting Started

1. Clone the repository or open the project in your preferred editor.
2. Review the configuration and project files to understand the intended workflow.
3. Install the tools required by the files in this repository.
4. Configure environment-specific values using your own settings.
5. Test changes in a development or sandbox environment before using them elsewhere.

Specific commands depend on the actual configuration in this repository. Check its scripts, manifests, and configuration files before running deployment or infrastructure commands.

## Suggested Validation

These checks are suggestions based on the detected files and technologies. Adjust paths and options to the actual project, and review commands before running them.

- Review the manifests and test a suitable file with `kubectl apply --dry-run=client -f <manifest-file>`.

## Security Notes

- Never commit passwords, access keys, tokens, private keys, or real environment files.
- Review configuration files for account IDs, resource names, and environment-specific values before sharing or deploying.
- For infrastructure and deployment projects, review potential costs and permissions before applying changes.
- Treat scripts that delete, modify, or provision resources with care.

## Disclaimer

This repository is provided for learning and demonstration. Validate the configuration for your own environment before using it in production.
