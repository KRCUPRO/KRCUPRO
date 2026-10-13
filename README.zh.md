<div align="center">

<p align="center">
  <a href="./README.md"><strong>🇺🇸 English</strong></a> &nbsp;•&nbsp;
  <a href="./README.ko.md"><strong>🇰🇷 한국어</strong></a> &nbsp;•&nbsp;
  <a href="./README.ja.md"><strong>🇯🇵 日本語</strong></a> &nbsp;•&nbsp;
  <a href="./README.zh.md"><strong>🇨🇳 简体中文</strong></a> &nbsp;•&nbsp;
  <a href="./README.es.md"><strong>🇪🇸 Español</strong></a><br />
  <a href="./README.fr.md"><strong>🇫🇷 Français</strong></a> &nbsp;•&nbsp;
  <a href="./README.de.md"><strong>🇩🇪 Deutsch</strong></a> &nbsp;•&nbsp;
  <a href="./README.ru.md"><strong>🇷🇺 Русский</strong></a> &nbsp;•&nbsp;
  <a href="./README.pt-BR.md"><strong>🇧🇷 Português</strong></a> &nbsp;•&nbsp;
  <a href="./README.ar.md"><strong>🇸🇦 العربية</strong></a>
</p>

<a href="https://github.com/KRCUPRO">
  <img src="./assets/hero.svg" alt="KRCUPRO Hero Banner" width="100%" />
</a>

<p align="center">
  <a href="https://github.com/KRCUPRO">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=16&duration=2800&pause=1200&color=38BDF8&center=true&vCenter=true&width=880&lines=Architecting+Bare-Metal+NixOS+Clusters+%26+FluxCD+GitOps;Engineering+High-Throughput+AI+Gateways+%26+MCP+Runtimes;Deploying+Distributed+Storage+with+Rook+Ceph+%26+Kubernetes;Building+Reliable+Systems+with+Go%2C+Rust+%26+TypeScript" alt="Typing SVG" />
  </a>
</p>

<a href="https://github.com/KRCUPRO">
  <img src="./assets/terminal.svg" alt="Developer Terminal" width="100%" />
</a>

</div>

<br />

### 💡 概览 (Executive Overview)

你好！我是 **KRCUPRO (조효준)** —— 专注于声明式裸金属基础设施、分布式存储、高吞吐AI网关及自主智能体运行时的系统与云原生平台工程师。

我致力于构建**兼具声明式可复现性与极致性能**的工程系统：从运行Rook Ceph存储的4节点物理NixOS集群，到调度分布式MCP流水线的Go进程管理器及高可用微服务。

---

### 🏛️ 核心工程支柱与架构设计

#### 1. 🌐 裸金属基础设施与声明式GitOps
- **4节点物理集群 (`myu`)**: 基于NixOS Flakes全声明式构建的裸金属Kubernetes集群（`ken` 控制平面，`decker`, `calder`, `usher` 工作节点）。
- **GitOps持续交付**: 采用 **FluxCD** 进行集群全局状态自动化协调，管理CNI、双Ingress网关及自动化TLS证书生命周期。
- **分布式存储体系**: 深度集成企业级 **Rook Ceph**，基于物理NVMe/SSD盘提供高可用块存储与共享分布式文件系统。

#### 2. ⚡ AI网关体系、MCP协议与智能体运行时
- **企业级AI中继网关**: 支持Token配额约束、多通道负载均衡及5ms以内无缝故障转移的高并发网关（`myu-gateway`, `mcp-gateway`）。
- **原生智能体调度器**: 采用 **Go进程管理器**、蓝绿Python工作者隔离及幂等工具调用引擎构建的Windows原生Agent架构。
- **Model Context Protocol (MCP)**: 结合硬件安全金库（DPAPI）与Cloudflare边缘网络编排的分布式MCP工具链。

#### 3. 🛡️ 系统底层分析与主动防御体系
- **SecOps审计控制台**: 多节点集群实时遥测看板、SSH会话审计追踪与主动安全防护套件。
- **无依赖底层系统研究**: 高精度密码学工程实现（AEAD, Ed25519, 常数时间检验）与零分配二进制分析流水线（`dev-timeline`）。

---

### 💻 完整技术栈清单 (Technology Stack)

| 领域 | 核心技术与工具 |
| :--- | :--- |
| **编程语言与运行时** | `Go`, `Rust`, `TypeScript`, `Nix`, `Python`, `Shell (Bash / PowerShell)`, `SQL` |
| **云原生与编排调度** | `Kubernetes (Kubeadm)`, `NixOS Flakes`, `FluxCD (GitOps)`, `Rook Ceph`, `Docker / Compose`, `Containerd` |
| **AI网关与通信协议** | `Model Context Protocol (MCP)`, `Claude Code Router (CCR)`, `REST / gRPC`, `WebSocket`, `Webhooks` |
| **边缘计算、网络与接入** | `Cloudflare Workers / D1 / Queues`, `Nginx`, `WireGuard`, `PCAP / 流量分析` |
| **可观测性与安全防护** | `集群实时遥测看板`, `SSH审计系统`, `主动防御系统`, `常数时间密码学` |

---

### 📁 代表性核心架构仓库 (Featured Repositories)

- **[`kuber-nixos-config`](https://github.com/KRCUPRO/kuber-nixos-config)** — 4节点 `myu` 集群声明式宿主机底座（NixOS flakes, Ceph配置, Kubeadm调度）。
- **[`kuber-infrastructure`](https://github.com/KRCUPRO/kuber-infrastructure)** — 统一管理CNI、Ingress、存储类及全集群工作负载的FluxCD GitOps仓库。
- **[`chatgpt-windows-work`](https://github.com/KRCUPRO/chatgpt-windows-work)** — 具备Go调度器、蓝绿进程隔离及Cloudflare入口的原生MCP运行时。
- **[`ui-reference-screens`](https://github.com/KRCUPRO/ui-reference-screens)** — 企业级API网关运营控制台与高标准落地页设计基准。
- **[`dev-timeline`](https://github.com/KRCUPRO/dev-timeline)** — 纯零依赖密码学工程与系统逆向研究长期提交总账（2022–至今）。

---

<div align="center">
  <a href="https://github.com/KRCUPRO">
    <img src="./assets/stats.svg" alt="Focus and Capabilities" width="100%" />
  </a>

  <br /><br />
  <sub><i>"简约是可靠的前提，声明式状态是安心的基石。"</i></sub>
</div>
