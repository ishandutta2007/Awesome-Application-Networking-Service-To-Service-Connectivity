# Awesome-Application-Networking-Service-To-Service-Connectivity

# Awesome-Application-Networking-Service-To-Service-Connectivity 🔗 🌐



<p align="center">

  <img src="assets/banner.svg" alt="Awesome Application Networking Service To Service Connectivity Banner" width="100%">

</p>



<p align="center">

  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a>

  <a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>

  <a href="https://github.com/ishandutta2007/Awesome-Application-Networking-Service-To-Service-Connectivity"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Application-Networking-Service-To-Service-Connectivity?style=social" alt="GitHub_Stars"/></a>

  <a href="https://github.com/ishandutta2007/Awesome-Application-Networking-Service-To-Service-Connectivity/fork"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Application-Networking-Service-To-Service-Connectivity?style=social" alt="GitHub Forks"/></a>

  <a href="https://github.com/ishandutta2007/Awesome-Application-Networking-Service-To-Service-Connectivity/blob/main/LICENSE"><img src="https://img.shields.io/github/license/ishandutta2007/Awesome-Application-Networking-Service-To-Service-Connectivity?color=blue" alt="License"/></a>

  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>

</p>



---



## 🌟 Top Application Networking & Service-to-Service Connectivity Ecosystem



**Curated List of Commercial Service Mesh Platforms & Open-Source Application Networking Frameworks**  

*Focused on Zero-Trust Service Connectivity, mTLS, Sidecar & Sidecarless Architectures, Multi-Cluster Traffic Management & Self-Hosted Mesh Solutions*  



**Last updated: October 2026** 📅



---



### 📌 Overview & SEO Summary

Welcome to the ultimate curated directory of **application networking platforms**, **service-to-service connectivity solutions**, and **open-source service mesh frameworks**. Whether you are looking for enterprise-grade commercial offerings (such as *Amazon VPC Lattice*, *Solo.io Gloo Network*, *Tetrate Service Express*, and *F5 Distributed Cloud App Connect*), or high-performance open-source alternatives (like *Istio*, *Cilium*, *Linkerd*, and *Network Service Mesh*), this list covers category leaders, eBPF-based data planes, and cloud-native connectivity architectures.



---



## 📑 Table of Contents

- [🏢 SaaS & Commercial Platforms](#-saas--commercial-platforms)

- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)

- [🛠️ How to Contribute](#%EF%B8%8F-how-to-contribute)

- [📊 Star History](#-star-history)

- [🤝 Support & Sponsorship](#-support--sponsorship)

- [⚠️ Disclaimer](#%EF%B8%8F-disclaimer)



---



## 🏢 SaaS / Commercial Platforms



The service mesh and application networking market has consolidated around a handful of enterprise platforms built on open-source cores (Istio, Envoy, Cilium), with commercial differentiation focused on multi-cluster governance, AI gateway capabilities, and zero-trust security. Pricing models vary dramatically: Amazon VPC Lattice charges per service-hour plus data processing , Solo.io Gloo offers a free tier with sales-led enterprise plans , Tetrate provides free access to its Agent Router Service with pay-as-you-go pricing , HashiCorp Consul starts at $1/user/month with custom enterprise pricing for mesh features , and F5 Distributed Cloud requires a 3-year minimum commitment with annual true-ups .



| SaaS / Commercial Platform | Company / Owner | Valuation / Market Cap | Standard Edition Starting Price | Free Tier / Free Trial Limits | Description |

| :--- | :--- | :--- | :--- | :--- | :--- |

| **[Amazon VPC Lattice](https://aws.amazon.com/vpc/lattice/)** ☁️ | Amazon | ~$2.0 Trillion | Per service-hour + data processing; 300K requests/hr included per service  | No free tier; AWS Free Tier does not cover VPC Lattice | **Fully managed application networking** — Connect, secure, and monitor services across VPCs and accounts. Auth policies, service networks, and resource configs. No sidecar required . |

| **[Cilium Service Mesh](https://cilium.io/)** 🐝 | Isovalent (Cisco) | Private (Acquired by Cisco) | Cilium OSS free; Enterprise via Isovalent | **Cilium OSS free forever**; Enterprise trial available | **eBPF-based sidecarless mesh** — Kernel-level L3/L4 enforcement with optional Envoy for L7. Lowest CPU usage under low load . Used in production at Google, AWS, and Datadog. |

| **[Istio (Commercial Support)](https://istio.io/)** 🔷 | Google / IBM / Solo.io | N/A (Open Source) | Istio OSS free; commercial support via Tetrate, Solo.io, and cloud vendors | **Istio OSS free forever** | **The most widely adopted service mesh** — Sidecar-based (Envoy), multi-cluster, mTLS, traffic splitting. Commercial distributions add governance and support. |

| **[Linkerd (Commercial Support)](https://linkerd.io/)** 🦊 | Buoyant | Private | Linkerd OSS free; Buoyant Enterprise for Kubernetes (BEK) custom pricing | **Linkerd OSS free forever** | **Ultralight service mesh for Kubernetes** — Rust-based micro-proxy with lowest latency in benchmarks . Simplest operational model among major meshes. |

| **[Solo.io Gloo Network](https://www.solo.io/)** 🎛️ | Solo.io | Private | Free tier available; Enterprise custom quote  | **Free tier: limited usage, no credit card**  | **Envoy-based application networking** — Gloo Gateway (API gateway) and Gloo Mesh (Istio-based multi-cluster). AI gateway capabilities added in 2026. |

| **[Tetrate Service Express](https://tetrate.io/)** 🚀 | Tetrate | Private | Custom quote; Agent Router: $5 free credit + pay-as-you-go  | **Free plan available**; no free trial for enterprise tiers  | **Enterprise Istio and Envoy platform** — Tetrate Istio Subscription, Service Bridge (multi-cluster), and Agent Router Service for AI workloads. Available via AWS Marketplace . |

| **[HashiCorp Consul](https://www.consul.io/)** 🔐 | HashiCorp (IBM) | ~$5 Billion (Acquired by IBM) | Basic: $1/user/month ; Enterprise: Custom  | **Free tier available**; $500 credit on HCP  | **Service discovery and mesh** — Identity-based service networking across any runtime. Multi-runtime support (EKS, EC2, ECS, VMs, K8s, bare metal). API gateway included on Premium . |

| **[Traefik Hub](https://traefik.io/)** 🚦 | Traefik Labs | Private | Custom quote; **30-day free trial for API Gateway tier**  | **30-day free trial**; no permanent free tier | **Cloud-native API gateway and mesh** — Built on Traefik Proxy (MIT). Native WAF, multi-cluster management, OIDC/JWT auth, and FIPS compliance. Pricing gated behind sales contact . |

| **[F5 Distributed Cloud App Connect](https://www.f5.com/cloud)** 🔴 | F5 Networks | ~$10 Billion | Custom quote; **3-year minimum commitment, annual true-ups**  | No free tier; FCP-B program requires 3-year commitment | **Multi-cloud application networking** — App Connect (service mesh), WAF, API security, DDoS mitigation, and bot defense in a unified SaaS console . |

| **[Prosimo Application Mesh](https://www.prosimo.io/)** 🕸️ | Prosimo | Private | $1,000–$15,000/month  | **No free tier** | **Multi-cloud networking and application mesh** — Simplifies connectivity across AWS, Azure, and GCP. Hidden costs add ~50% to advertised price . |



---



## 🔓 Open-Source GitHub Projects



*Sorted by GitHub_Stars_Count (Descending)* 🌟



- **[Istio](https://github.com/istio/istio)** [![Stars](https://img.shields.io/github/stars/istio/istio?style=social&color=white)](https://github.com/istio/istio/stargazers)  

  **The most widely adopted service mesh**, Apache-2.0 licensed. ~37k+ stars. Sidecar-based architecture with Envoy proxy, mTLS, traffic management, observability, and multi-cluster support. Foundational technology behind Tetrate, Solo.io Gloo Mesh, and Google Cloud Service Mesh.  🛡️



- **[Cilium](https://github.com/cilium/cilium)** [![Stars](https://img.shields.io/github/stars/cilium/cilium?style=social&color=white)](https://github.com/cilium/cilium/stargazers)  

  **eBPF-based networking, security, and observability**, Apache-2.0 licensed. ~21k+ stars. Sidecarless service mesh with kernel-level L3/L4 enforcement and optional Envoy for L7. Lowest CPU usage under low load; eliminates per-pod proxy overhead.  🐝



- **[Linkerd](https://github.com/linkerd/linkerd2)** [![Stars](https://img.shields.io/github/stars/linkerd/linkerd2?style=social&color=white)](https://github.com/linkerd/linkerd2/stargazers)  

  **Ultralight service mesh for Kubernetes**, Apache-2.0 licensed. ~10k+ stars. Rust-based micro-proxy with **lowest response times** — outperforming Cilium by 29.85% and Istio by 63.43% in mTLS benchmarks. Simplest operational model.  🦊



- **[Envoy Proxy](https://github.com/envoyproxy/envoy)** [![Stars](https://img.shields.io/github/stars/envoyproxy/envoy?style=social&color=white)](https://github.com/envoyproxy/envoy/stargazers)  

  **Cloud-native high-performance edge/middle/service proxy**, Apache-2.0 licensed. ~26k+ stars. The data plane for Istio, Gloo, and countless service mesh implementations. L4/L7 proxy with dynamic configuration and observability. 🔷



- **[Network Service Mesh (NSM)](https://github.com/networkservicemesh/networkservicemesh)** [![Stars](https://img.shields.io/github/stars/networkservicemesh/networkservicemesh?style=social&color=white)](https://github.com/networkservicemesh/networkservicemesh/stargazers)  

  **Service mesh for Kubernetes with network service abstractions**, Apache-2.0 licensed. ~35 stars on main repo, active ecosystem of 20+ sub-repos . Provides complex network topologies for multi-cloud and telco workloads. Kubernetes SDK and SDK components available. 🌐



- **[Kuma](https://github.com/kumahq/kuma)** [![Stars](https://img.shields.io/github/stars/kumahq/kuma?style=social&color=white)](https://github.com/kumahq/kuma/stargazers)  

  **Universal service mesh by Kong**, Apache-2.0 licensed. ~3.8k+ stars. Supports both Kubernetes and VMs, multi-mesh, and zone-based deployments. Envoy-based data plane with policy management. 🐻



- **[Consul](https://github.com/hashicorp/consul)** [![Stars](https://img.shields.io/github/stars/hashicorp/consul?style=social&color=white)](https://github.com/hashicorp/consul/stargazers)  

  **Service discovery and mesh**, MPL-2.0 licensed. ~29k+ stars. Multi-runtime support (K8s, VMs, bare metal). Connect (mTLS), intentions, and API gateway. Enterprise adds advanced mesh features and support.  🔐



- **[Traefik Proxy](https://github.com/traefik/traefik)** [![Stars](https://img.shields.io/github/stars/traefik/traefik?style=social&color=white)](https://github.com/traefik/traefik/stargazers)  

  **Cloud-native application proxy**, MIT licensed. ~51k+ stars. Supports TCP/UDP/HTTP routing with automatic service discovery. Foundation for Traefik Hub commercial tiers.  🚦



- **[Bondy](https://github.com/bondy-io/bondy)** [![Stars](https://img.shields.io/github/stars/bondy-io/bondy?style=social&color=white)](https://github.com/bondy-io/bondy/stargazers)  

  **Scalable application networking platform**, Apache-2.0 licensed. ~200+ stars. Combines service mesh and event mesh capabilities. Implements WAMP (Web Application Messaging Protocol) in Erlang.  🔗



- **[Gloo Mesh (Solo.io)](https://github.com/solo-io/gloo-mesh)** [![Stars](https://img.shields.io/github/stars/solo-io/gloo-mesh?style=social&color=white)](https://github.com/solo-io/gloo-mesh/stargazers)  

  **Istio-based multi-cluster service mesh management**, Apache-2.0 licensed. ~500+ stars. Adds enterprise governance, RBAC, and unified control plane on top of Istio. Commercial version available.  🎛️



- **[Admiral (Istio Ecosystem)](https://github.com/istio-ecosystem/admiral)** [![Stars](https://img.shields.io/github/stars/istio-ecosystem/admiral?style=social&color=white)](https://github.com/istio-ecosystem/admiral/stargazers)  

  **Automatic configuration for multi-cluster Istio**, Apache-2.0 licensed. ~567 stars . Provides automatic configuration generation, syncing, and service discovery for Istio across multiple clusters. 🌍



- **[Pipy](https://github.com/flomesh-io/pipy)** [![Stars](https://img.shields.io/github/stars/flomesh-io/pipy?style=social&color=white)](https://github.com/flomesh-io/pipy/stargazers)  

  **Programmable proxy for cloud, edge, and IoT**, Apache-2.0 licensed. ~3k+ stars. Lightweight, scriptable proxy for building custom service mesh data planes and API gateways.  🔧



- **[Meshery](https://github.com/meshery/meshery)** [![Stars](https://img.shields.io/github/stars/meshery/meshery?style=social&color=white)](https://github.com/meshery/meshery/stargazers)  

  **Cloud-native management plane for service meshes**, Apache-2.0 licensed. ~5k+ stars. Adapters for Istio, Linkerd, Kuma, NGINX Service Mesh, and more. Multi-mesh lifecycle management and performance benchmarking.  📊



- **[Envoy Control](https://github.com/allegro/envoy-control)** [![Stars](https://img.shields.io/github/stars/allegro/envoy-control?style=social&color=white)](https://github.com/allegro/envoy-control/stargazers)  

  **Platform-agnostic production-ready Envoy control plane**, Apache-2.0 licensed. ~400+ stars. Provides service discovery and dynamic configuration for Envoy-based service meshes without Kubernetes dependency.  ⚙️



---



## 🛠️ How to Contribute



Contributions are welcome! Follow these steps to submit new application networking platforms or open-source service mesh software:



1. 🍴 **Fork** the repository.

2. 📝 **Add/edit** entries in `README.md` maintaining table/list structure and formatting.

3. 🔗 Include project title, official website/GitHub link, exact Stars_Count, license, and brief description.

4. 🚀 Submit a **Pull Request** with a descriptive summary of your changes.



---



## 📊 Star History



[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Application-Networking-Service-To-Service-Connectivity&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Application-Networking-Service-To-Service-Connectivity&type=date&legend=top-left)



---



## 🤝 Support & Sponsorship



If you find this application networking repository useful, please consider supporting the project:



- ⭐ **Star** this repository to increase visibility!

- 🔀 **Fork** and share with fellow developers & platform engineers.

- ☕ **Sponsor & Buy Me a Coffee**: Support ongoing open-source curation via the [GitHub Sponsor Dashboard](https://github.com/sponsors/ishandutta2007).



---



## ⚠️ Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement. ℹ️

- Service mesh architectures differ significantly in performance: Linkerd outperforms Istio and Cilium in latency benchmarks, while Cilium with eBPF has lowest CPU under low load . **Benchmark for your specific workload** before committing. 🔒

- Open-source service meshes (Istio, Linkerd, Cilium, Consul) provide self-hosted ownership and community support, but enterprise-grade SLA guarantees, multi-cluster governance, and vendor support remain primarily commercial offerings. 🔗



---



<p align="center">

  <b>Made with ❤️ for platform engineers, SREs, and open-source networking developers.</b>

</p>
