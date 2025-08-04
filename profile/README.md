# Twingate

Welcome to the **Twingate** GitHub organization — home to officially supported tools and solutions maintained by our engineering team.

These projects power production‑grade infrastructure automation, cloud-native deployment, CI/CD workflows, and secure access built around the Twingate Zero Trust platform.

## Featured Tools

These are the core repositories we maintain and pin, used by engineers to build Zero Trust workflows and infrastructure:

- **[terraform-provider-twingate](https://github.com/Twingate/terraform-provider-twingate)** – Manage your Networks, Gateways, Services, Users, and other Twingate resources via Terraform. Ideal for IaC-based deployment and repeatable scripting.
- **[kubernetes-operator](https://github.com/Twingate/kubernetes-operator)** – Kubernetes controller exposing Twingate objects as CRDs. Enables GitOps-driven access policy and network configuration.
- **[kubernetes-access-gateway](https://github.com/Twingate/kubernetes-access-gateway)** – Securely exposes the Kubernetes API via a Twingate Access Gateway. Eliminates public cluster endpoints.
- **[github-action](https://github.com/Twingate/github-action)** – GitHub Action that connects workflows to Twingate-protected internal services (e.g. databases) with temporary credentials—no firewall change needed.
- **[helm-charts](https://github.com/Twingate/helm-charts)** – Official Helm charts for installing the Twingate Connector, Kubernetes components, and operator as Kubernetes workloads.
- **[pulumi-twingate](https://github.com/Twingate/pulumi-twingate)** – Pulumi provider that lets you manage Twingate infrastructure using Python, TypeScript, Go, or .NET

## How to Use These Tools

Explore, clone, and adapt. They're meant for:

- Automating the provisioning of resources
- Embedding access control in your CI/CD or GitOps pipelines
- Running Twingate access from Kubernetes or 3rd-party workflows

We recommend starting with the README in each repo to learn installation steps, example use cases, and supported architectures.

## Related Projects

- **[Twingate‑Solutions](https://github.com/twingate-solutions)** – Field-tested quickstarts and scripts for enterprise access deployment, built and maintained by the Customer Solutions team
- **[Twingate‑Community](https://github.com/twingate-community)** – Community‑driven integrations, creative workflows, and homelab projects

## 🤝 Contributing

Everything here is open-source and community-welcoming. Found a bug? Wrote an improvement or a new integration? Feel free to open an issue or submit a PR—your contributions are always appreciated!