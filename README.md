# nexus

This repo is the nexus of several repos which combine to form a compute platform for running containers.

The high level design involves several components:
`argus`: A gossip protocol-backed daemon that monitors system health and group membership.
`moirai`: A minimal container runtime that can build containers and host workloads on my own hardware/VMs.
`hydra`: A distributed control plane that operates the runtime, manages container lifecycle, and coordinates alerting.
`nexus`: This repo. It will contain manifests, tests, and documentation about how to integrate and operate the platform as a whole.
