# Marshal

**Coding agents at full speed. With full receipts.**

Marshal runs AI coding agents in isolated Kubernetes pods inside your own VPC, with credential
isolation, audited egress and live tool policies. Developers get agents that can work on their
own; security teams get a record of what every agent reached, ran and was allowed to do.

**[marshal.codes](https://marshal.codes/?utm_source=github&utm_medium=org-profile&utm_campaign=marshal)** ·
[Book a demo](https://marshal.codes/?utm_source=github&utm_medium=org-profile&utm_campaign=marshal&utm_content=demo#demo) ·
[Docs](https://docs.marshal.codes) ·
[Blog](https://marshal.codes/blog)

## What it is for

| If you are | Marshal gives you |
|---|---|
| **A security lead** | Agents that never hold your secrets, egress you can audit, and tool policies you can change while an agent is running |
| **An engineering lead** | Autonomous agents your developers can actually be allowed to use |
| **A platform lead** | One runtime for every coding agent, in your own cluster and your own VPC |

Marshal is self-hosted: it installs into a Kubernetes cluster you control.

## Open source

### [Runlease](https://runlease.online/?utm_source=github&utm_medium=org-profile&utm_campaign=marshal)

Cheap spot VMs for coding agents, in your own cloud. One command gives an agent, a CI job or you
a real Linux machine in your own AWS or Google Cloud account. It has no public address, your keys
never leave your computer, and it deletes itself when its lease ends. Free, Apache-2.0.
[Source and releases on GitHub](https://github.com/marshal-org/runlease).

```bash
curl -fsSL https://runlease.online/install.sh | sh
```

Runlease gives one agent one machine. Marshal is what you run when it is a whole team.

### [marshal-install](https://github.com/marshal-org/marshal-install)

The Terraform installer for self-hosted Marshal: one node with k3s, Google Kubernetes Engine, or
Amazon EKS. Start with the [install docs](https://docs.marshal.codes/installing/prerequisites).

## Talk to us

- A demo, pricing or a pilot: [book a demo](https://marshal.codes/?utm_source=github&utm_medium=org-profile&utm_campaign=marshal&utm_content=contact#demo) or `sales@marshal.codes`
- Questions about Runlease: `runlease@marshal.codes`
- A security report: `security@marshal.codes`
