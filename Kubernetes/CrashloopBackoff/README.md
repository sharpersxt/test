
CrashloopBackoff
================

Overview
--------

Creates a pod in a continuous failure state.  This results in a Crashloop 
Backoff state in the Kubernetes scheduler.

Deployment
----------

```bash
$ kubectl --kubeconfig /path/to/kubeconfig apply -f CrashloopBackoff.yaml
```

Removal
-------

```bash
$ kubectl --kubeconfig /path/to/kubeconfig delete -f CrashloopBackoff.yaml
```

