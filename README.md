# Scarlet: Your K8s Cluster Co-Pilot 🤖✨

**Meet Scarlet, the intelligent agent living in your Kubernetes cluster, designed to empower engineers and streamline incident response.**

Scarlet is your proactive partner, providing critical context, enabling swift actions, and offering seamless interaction to keep your cluster healthy and your applications running smoothly.

---

## 🚀 What Scarlet Does

Scarlet brings a new level of interaction and control to your Kubernetes environment:

* **🔍 Deep Contextual Awareness:** In the event of an incident, Scarlet doesn't just alert you; it dives deep! It accesses **Grafana, Prometheus, Kubernetes API, and more** to gather and present a comprehensive picture, giving engineers the immediate context needed to diagnose and resolve issues faster.
* **📲 Proactive Incident Notification:** When trouble strikes, Scarlet can directly **call the engineer's Scarlet mobile app**, ensuring critical alerts are never missed.
* **🔒 Secure Command Execution:** Need to run `kubectl` commands? Scarlet allows engineers to execute commands directly on the cluster, secured with **facial recognition** for an added layer of protection.
* **🛠️ Custom Tool Integration:** Scarlet is extensible! It can seamlessly access and utilize your **custom tools and serverless functions (e.g., Knative services)**, bringing all your operational power into one interface.
* **🗣️ Voice-Activated Interaction:** Communicate naturally. Scarlet understands **voice commands**, allowing engineers to query, instruct, and interact hands-free.
* **📊 Cluster Health & Application Insights:** Stay informed! Scarlet provides on-demand **information about your cluster's health, application status, and performance metrics.**

---

## 🌟 Why Scarlet?

* **Faster Incident Resolution:** By providing immediate context and enabling quick, secure actions, Scarlet significantly reduces Mean Time To Resolution (MTTR).
* **Enhanced Operational Efficiency:** Automate routine checks, gather data, and execute commands with voice or a simple tap.
* **Improved Engineer Experience:** Reduce the cognitive load on engineers during stressful situations by providing a smart, interactive assistant.
* **Secure by Design:** With features like facial recognition for command execution, Scarlet prioritizes the security of your cluster.
* **Extensible & Adaptable:** Integrate Scarlet with your existing toolchain and custom solutions.

---

## 🔮 The Vision

Scarlet aims to be an indispensable member of your DevOps team, learning and evolving to provide increasingly sophisticated support for managing complex Kubernetes environments.

---

## 🛠️ Getting Started

### Prerequisites

* Kubernetes cluster (v1.19+)
* [kubectl](https://kubernetes.io/docs/tasks/tools/) installed and configured
* [Pulumi](https://www.pulumi.com/docs/install/) installed
* [Go](https://golang.org/doc/install) (v1.18+)
* [ArgoCD CLI](https://argo-cd.readthedocs.io/en/stable/cli_installation/) (optional, for advanced management)

### Installation

1. Clone this repository:
   ```
   git clone https://github.com/yourusername/scarlet.git
   cd scarlet
   ```

2. Bootstrap the environment:
   ```
   cd 40-bootstrap
   pulumi up --stack dev
   ```

3. Access the Scarlet dashboard:
   Once deployed, you can access the Scarlet dashboard through the provided URL in the installation output.

### Architecture

Scarlet consists of several key components:

* **Platform Layer:** Core infrastructure services including monitoring (Prometheus, Grafana, Loki, Tempo), messaging (RabbitMQ), and serverless capabilities (Knative)
* **Notification Service:** Handles alerting and communication with engineers
* **API Gateway:** Central entry point for all Scarlet interactions
* **Mobile Application:** Companion app for engineers to receive alerts and interact with the cluster on-the-go

---

## 📱 Mobile App

The Scarlet mobile app is available for both iOS and Android, enabling:

* Push notifications for critical alerts
* Secure command execution with facial recognition
* Voice-activated cluster querying
* Monitoring dashboard access

*Mobile app download links will be available soon.*

---

## 🤝 Contributing

Scarlet is an open-source project and we welcome contributions! Here's how you can help:

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/amazing-feature`
3. Commit your changes: `git commit -m 'Add amazing feature'`
4. Push to the branch: `git push origin feature/amazing-feature`
5. Open a Pull Request

Please see our [Contributing Guide](00-docs/CONTRIBUTING.md) for more details.

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 📧 Contact

Project Maintainers - [your-email@example.com](mailto:your-email@example.com)

Project Link: [https://github.com/yourusername/scarlet](https://github.com/yourusername/scarlet)
