# .NET on Windows Reliability Config

### Current state

The `master-msi-archive.txt` indicates which branch to use for the `master` VM .NET tracer.

The `pdh_check.yaml` is copied to each machine on a schedule.

### Desired state

The `AgentConfig` folder is versioned and copied automatically to each of the virtual machines so we can update any checks we want to.

We also should have a self-updating script in order to manage the machines from a single place.