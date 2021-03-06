---
title: kyma alpha uninstall
---

Uninstalls Kyma from a running Kubernetes cluster.

## Synopsis

Use this command to uninstall Kyma from a running Kubernetes cluster.

```bash
kyma alpha uninstall [flags]
```

## Options

```bash
  -c, --components string   Path to a YAML file with component list to override.
```

## Options inherited from parent commands

```bash
      --ci                  Enables the CI mode to run on CI/CD systems. It avoids any user interaction (e.g. no dialog prompts) and ensures that logs are formatted properly in log files (e.g. no spinners for CLI steps).
  -h, --help                Displays help for the command.
      --kubeconfig string   Specifies the path to the kubeconfig file. By default, Kyma CLI uses the KUBECONFIG environment variable or "/$HOME/.kube/config" if the variable is not set.
      --non-interactive     Enables the non-interactive shell mode.
  -v, --verbose             Displays details of actions triggered by the command.
```

## See also

* [kyma alpha](#kyma-alpha-kyma-alpha)	 - Executes the commands in alpha testing stage.

