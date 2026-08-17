![Banner image](https://user-images.githubusercontent.com/10284570/173569848-c624317f-42b1-45a6-ab09-f0ea3c247648.png)

<!-- CASTUO:BRAND:START -->
<p align="center">
  <img src="https://raw.githubusercontent.com/Traky12/Traky12/main/assets/brand/castuo-system-logo-square.jpg" alt="CASTÚO-SYSTEM official logo" width="180" />
</p>
<!-- CASTUO:BRAND:END -->

# n8n - Secure Workflow Automation for Technical Teams

n8n is a workflow automation platform that gives technical teams the flexibility of code with the speed of no-code. With 400+ integrations, native AI capabilities, and a fair-code license, n8n lets you build powerful automations while maintaining full control over your data and deployments.

![n8n.io - Screenshot](https://raw.githubusercontent.com/n8n-io/n8n/master/assets/n8n-screenshot-readme.png)

## Key Capabilities

- **Code When You Need It**: Write JavaScript/Python, add npm packages, or use the visual interface
- **AI-Native Platform**: Build AI agent workflows based on LangChain with your own data and models
- **Full Control**: Self-host with our fair-code license or use our [cloud offering](https://app.n8n.cloud/login)
- **Enterprise-Ready**: Advanced permissions, SSO, and air-gapped deployments
- **Active Community**: 400+ integrations and 900+ ready-to-use [templates](https://n8n.io/workflows)

## Quick Start

Try n8n instantly with [npx](https://docs.n8n.io/hosting/installation/npm/) (requires [Node.js](https://nodejs.org/en/)):

```
npx n8n
```

Or deploy with [Docker](https://docs.n8n.io/hosting/installation/docker/):

```
docker volume create n8n_data
docker run -it --rm --name n8n -p 5678:5678 -v n8n_data:/home/node/.n8n docker.n8n.io/n8nio/n8n
```

Access the editor at http://localhost:5678

## Resources

- 📚 [Documentation](https://docs.n8n.io)
- 🔧 [400+ Integrations](https://n8n.io/integrations)
- 💡 [Example Workflows](https://n8n.io/workflows)
- 🤖 [AI & LangChain Guide](https://docs.n8n.io/advanced-ai/)
- 👥 [Community Forum](https://community.n8n.io)
- 📖 [Community Tutorials](https://community.n8n.io/c/tutorials/28)

## Support

Need help? Our community forum is the place to get support and connect with other users:
[community.n8n.io](https://community.n8n.io)

## License

n8n is [fair-code](https://faircode.io) distributed under the [Sustainable Use License](https://github.com/n8n-io/n8n/blob/master/LICENSE.md) and [n8n Enterprise License](https://github.com/n8n-io/n8n/blob/master/LICENSE_EE.md).

- **Source Available**: Always visible source code
- **Self-Hostable**: Deploy anywhere
- **Extensible**: Add your own nodes and functionality

[Enterprise licenses](mailto:license@n8n.io) available for additional features and support.

Additional information about the license model can be found in the [docs](https://docs.n8n.io/sustainable-use-license/).

## Contributing

Found a bug 🐛 or have a feature idea ✨? Check our [Contributing Guide](https://github.com/n8n-io/n8n/blob/master/CONTRIBUTING.md) for a setup guide & best practices.

## Join the Team

Want to shape the future of automation? Check out our [job posts](https://n8n.io/careers) and join our team!

## What does n8n mean?

**Short answer:** It means "nodemation" and is pronounced as n-eight-n.

**Long answer:** "I get that question quite often (more often than I expected) so I decided it is probably best to answer it here. While looking for a good name for the project with a free domain I realized very quickly that all the good ones I could think of were already taken. So, in the end, I chose nodemation. 'node-' in the sense that it uses a Node-View and that it uses Node.js and '-mation' for 'automation' which is what the project is supposed to help with. However, I did not like how long the name was and I could not imagine writing something that long every time in the CLI. That is when I then ended up on 'n8n'." - **Jan Oberhauser, Founder and CEO, n8n.io**

<!-- CASTUO:PUBLIC-SURFACE -->
## CASTÚO integration boundary

This repository exposes only a bounded public integration surface. Its role, current state and claims are subordinate to the `Traky12/castuo-evolution` control plane.

This repository does not by itself claim production operation, certification, independent validation, customer contracts, revenue, autonomous authority, global federation or legal compliance. Do not publish secrets, credentials, private endpoints, customer data, private evidence or unpublished security findings.

See [`docs/CASTUO_PUBLIC_SURFACE.md`](docs/CASTUO_PUBLIC_SURFACE.md) for the public boundary. `Claim != Evidence`; `CURRENT != TARGET`; promotion requires control-plane authorization.
<!-- CASTUO:PUBLIC-SURFACE-END -->

<!-- CASTUO-PUBLIC-INTEGRATION:START -->
## CASTÚO-SYSTEM public integration

**Repository role:** Upstream integration.

Tecnología upstream integrada; no capacidad propietaria por defecto. The public reference surface is governed by the [Traky12 profile](https://github.com/Traky12/Traky12) and the [castuo-evolution control plane](https://github.com/Traky12/castuo-evolution). Current ecosystem status is documented in the [integration status](https://github.com/Traky12/castuo-evolution/blob/main/docs/GITHUB_INTEGRATION_STATUS_2026-08-16.md) and [blocker register](https://github.com/Traky12/castuo-evolution/blob/main/docs/GITHUB_INTEGRATION_BLOCKERS_2026-08-16.md).

> Identity is not evidence. Repository activity is not operational truth. No production, certification, legal-compliance, customer, revenue, continuous-operation or federation claim is implied by this README block.
<!-- CASTUO-PUBLIC-INTEGRATION:END -->

<!-- CASTUO:ECOSYSTEM-INTEGRATION:START -->
## CASTÚO-SYSTEM ecosystem integration

**Declared role:** Adaptador upstream de automatización; no es control plane soberano.

This repository is connected to the CASTÚO-SYSTEM ecosystem through the [Traky12 public profile](https://github.com/Traky12), the [Castuo-system core](https://github.com/Traky12/Castuo-system), and the [castuo-evolution governance control plane](https://github.com/Traky12/castuo-evolution). The canonical map defines relationships; repository activity does not become operational evidence by itself.

**Current bounded state:** GREEN-STAGING-CANDIDATE · EVIDENCE-SCOPED · PROMOTION-BLOCKED, unless this repository's own metadata declares a narrower state. Identity, implementation, tests, evidence, review and promotion remain separate dimensions.

**Evidence boundary:** This README does not claim production operation, certification, legal compliance, independent validation, customer traction, revenue, continuous operation, autonomous authority or federation. Such claims require scope-bound provenance, reproducible artifacts, security review, human review and an explicit promotion decision.

**Canonical references:** [CASTÚO-REPOSITORY-STANDARD-V1.0](https://github.com/Traky12/Castuo-system/blob/main/README.md), [CASTÚO public claim boundary](https://github.com/Traky12/Traky12/blob/main/PUBLIC_CLAIM_BOUNDARY.md), and the [public profile](https://github.com/Traky12/Traky12).
<!-- CASTUO:ECOSYSTEM-INTEGRATION:END -->
