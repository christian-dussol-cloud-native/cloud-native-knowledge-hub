# CNCF Project Focus Series

> Educational deep-dives into CNCF projects through hands-on learning and real-world application in Financial Services environments.

## 📚 About This Series

The CNCF Project Focus is a learning series where I explore Cloud Native Computing Foundation projects by building production-ready examples, documenting lessons learned, and sharing practical insights from implementing these technologies in FinTech contexts.

**Focus Areas:**
- Hands-on GitHub repositories with deployable examples
- Real-world use cases in Financial Services
- Governance and FinOps patterns
- Integration with existing toolchains (Kyverno, ArgoCD, etc.)

**Format:**
- LinkedIn carousel for quick overview
- GitHub repository with complete examples
- Medium article for deep technical dive

---

## Published Episodes

### Arc #1 — Disciplined Composition: Infrastructure Foundations

> How do you compose cloud-native infrastructure that is reliable, observable, and cost-efficient? This first arc explores three foundational CNCF projects that answer this question from complementary angles: compute, infrastructure and networking.

| Episode | Project | GitHub Repository | Carousel | Medium Article | Published | Focus |
|---------|---------|-------------------|----------|----------------|-----------|-------|
| **#1** | **Knative** | [knative](https://github.com/christian-dussol-cloud-native/knative) | [Carousel](https://github.com/christian-dussol-cloud-native/knative/blob/main/carousel/CNCF%20Project%20Focus%20%231%20-%20Knative.pdf) | [Medium Article](https://medium.com/@christian.dussol/knative-stop-paying-for-idle-kubernetes-pods-ac5e6ec350fa) | Dec 2025 | Serverless, Cost Optimization, Auto-scaling |
| **#2** | **Crossplane** | [crossplane](https://github.com/christian-dussol-cloud-native/crossplane) | [Carousel](https://github.com/christian-dussol-cloud-native/crossplane/blob/main/carousel/CNCF%20Project%20Focus%20%232%20-%20Crossplane.pdf) | [Medium Article](https://medium.com/@christian.dussol/from-terraform-to-crossplane-exploring-multi-cloud-infrastructure-management-7dd65f3a81c7) | Jan 2026 | Multi-cloud, IaC, Platform Engineering |
| **#3** | **Cilium** | [cilium](https://github.com/christian-dussol-cloud-native/cilium) | [Carousel](https://github.com/christian-dussol-cloud-native/cilium/blob/main/carousel/CNCF%20Project%20Focus%20%233%20-%20Cilium.pdf) | [Medium Article](https://medium.com/@christian.dussol/cilium-eliminating-the-hidden-network-overhead-in-kubernetes-cfa6ac10d084) | Jan 2026 | eBPF-based networking, security, and observability solution for Kubernetes |
| **Arc #1 Synthesis** | **Arc Closure** | — | [Carousel](carousels/CNCF%20Project%20Focus%20-%20ARC%231%20infrastructure%20foundations.pdf) | [Medium Article](https://medium.com/aws-in-plain-english/disciplined-composition-building-cloud-native-infrastructure-that-scales-b5de85ab5893) | Feb 2026 | Disciplined Composition — synthesizing Knative, Crossplane & Cilium |

---

## 📋 Episode Details

### Episode #1: Knative - Serverless on Kubernetes

**Description:**  
Exploring Knative for serverless workloads with focus on cost optimization and auto-scaling patterns in Financial Services.

**Key Topics:**
- Serverless on Kubernetes
- Cost optimization strategies
- Auto-scaling configurations
- Cold start optimization

---

### Episode #2: Crossplane - Multi-Cloud Infrastructure Management

**Description:**  
From Terraform to Crossplane - exploring unified infrastructure management across multiple cloud providers with Kubernetes-native workflows.

**Key Topics:**
- Multi-cloud infrastructure management
- Comparison: Terraform vs Crossplane
- Provider, Managed Resource, Composition, XRD patterns
- FinTech governance with Kyverno integration

---

### Episode #3: Cilium - eBPF-Powered Kubernetes Networking

**Description:**
Exploring Cilium CNI for high-performance networking with focus on security policies, observability and cost optimization in Financial Services.

**Key Topics:**
- eBPF fundamentals and kernel-level networking
- NetworkPolicies: L3/L4/L7 security enforcement
- Hubble observability without agents
- Service mesh alternative (no sidecars)
- Kyverno integration for Policy-as-Code governance
- PCI-DSS compliant architecture patterns

---

### Arc #1 Synthesis: Disciplined Composition — Building Cloud-Native Infrastructure That Scales

**Description:**
This synthesis article closes the first arc of the series by drawing the connecting thread between Knative, Crossplane, and Cilium. Together, these three projects embody the principle of *disciplined composition*: building cloud-native infrastructure from focused, interoperable primitives rather than monolithic platforms.

**Key Themes:**
- How Knative, Crossplane and Cilium complement each other as infrastructure primitives
- The "disciplined composition" pattern: assembling capabilities without coupling concerns
- Lessons learned from applying these tools in FinTech/Financial Services contexts
- A framework for evaluating future CNCF projects through the same lens

**Medium Article:** [Disciplined Composition — Building Cloud-Native Infrastructure That Scales](https://medium.com/aws-in-plain-english/disciplined-composition-building-cloud-native-infrastructure-that-scales-b5de85ab5893)

---

## Learning Philosophy

**Building beats consuming**
Each episode includes complete, deployable code rather than theoretical explanations. All examples are tested and production-ready.

**Context over hype**  
Honest comparisons with existing tools (Terraform, Istio, etc.) and clear guidance on when to use each technology based on real-world context.

**FinTech focus**  
Examples and patterns tailored for Financial Services requirements: compliance, governance, cost control, and regulatory considerations.

**Learning in Public**  
Documenting the learning journey authentically, including challenges, mistakes, and discoveries.

---

## 📬 Connect

**LinkedIn:** [Christian Dussol](https://www.linkedin.com/in/christiandussol/)
