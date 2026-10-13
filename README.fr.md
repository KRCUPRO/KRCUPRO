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

### 💡 Vue d'ensemble (Executive Overview)

Bonjour ! Je suis **KRCUPRO (조효준)** — Ingénieur Systèmes & Plateformes Cloud-Native spécialisé dans l'infrastructure bare-metal déclarative, le stockage distribué, les passerelles d'IA à haut débit et les moteurs d'agents autonomes.

Je conçois des systèmes où **la reproductibilité déclarative rencontre les performances extrêmes** : des clusters physiques NixOS à 4 nœuds avec stockage Ceph jusqu'aux superviseurs Go orchestrant des pipelines MCP distribués.

---

### 🏛️ Piliers d'Ingénierie & Architectures

#### 1. 🌐 Infrastructure Bare-Metal & GitOps Déclaratif
- **Cluster Physique à 4 Nœuds (`myu`)**: Cluster Kubernetes bare-metal orchestré via NixOS Flakes (`ken` plan de contrôle, `decker`, `calder`, `usher` nœuds de calcul).
- **Livraison Continue GitOps**: Réconciliation automatisée à l'échelle du cluster via **FluxCD**, gérant le CNI, les contrôleurs ingress et le cycle de vie TLS.
- **Stockage Distribué**: Déploiement de **Rook Ceph** de classe entreprise offrant des volumes distribués haute disponibilité sur disques physiques.

#### 2. ⚡ Passerelles d'IA, Protocoles MCP & Runtimes Autonomes
- **Passerelles d'IA d'Entreprise**: Reverse proxy et routage de modèles haute concurrence (`myu-gateway`, `mcp-gateway`) avec gestion des quotas et basculement sous 5ms.
- **Superviseurs d'Agents Natifs**: Architecture native Windows avec **superviseur de processus en Go**, isolation blue/green et exécution idempotente d'outils.
- **Model Context Protocol (MCP)**: Chaînage et orchestration de serveurs MCP distribués avec sécurité matérielle DPAPI et routage edge Cloudflare.

#### 3. 🛡️ Rétro-ingénierie & Défense Active d'Infrastructure
- **Tableaux de Bord SecOps**: Télémétrie de cluster multi-nœuds en temps réel, audit de sessions SSH et suites de remédiation active.
- **Recherche Système Sans Dépendance**: Implémentations cryptographiques rigoureuses (AEAD, Ed25519, temps constant) et analyse binaire (`dev-timeline`).

---

### 💻 Stack Technologique Complète (Technology Stack)

| Domaine | Technologies et Outils |
| :--- | :--- |
| **Langages & Runtimes** | `Go`, `Rust`, `TypeScript`, `Nix`, `Python`, `Shell (Bash / PowerShell)`, `SQL` |
| **Cloud-Native & Orchestration** | `Kubernetes (Kubeadm)`, `NixOS Flakes`, `FluxCD (GitOps)`, `Rook Ceph`, `Docker / Compose`, `Containerd` |
| **Passerelles IA & Protocoles** | `Model Context Protocol (MCP)`, `Claude Code Router (CCR)`, `REST / gRPC`, `WebSocket`, `Webhooks` |
| **Edge, Ingress & Réseau** | `Cloudflare Workers / D1 / Queues`, `Nginx`, `WireGuard`, `PCAP / Analyse de paquets` |
| **Observabilité & Sécurité** | `Tableaux de bord de télémétrie`, `Audit SSH`, `Défense active`, `Cryptographie en temps constant` |

---

### 📁 Dépôts d'Architecture Remarquables

- **[`kuber-nixos-config`](https://github.com/KRCUPRO/kuber-nixos-config)** — Fondation déclarative des hôtes du cluster `myu` à 4 nœuds (NixOS flakes, Ceph, Kubeadm).
- **[`kuber-infrastructure`](https://github.com/KRCUPRO/kuber-infrastructure)** — Dépôt GitOps FluxCD gérant le CNI, l'Ingress et les charges de travail du cluster.
- **[`chatgpt-windows-work`](https://github.com/KRCUPRO/chatgpt-windows-work)** — Runtime MCP natif avec superviseur Go, isolation blue/green et ingress Cloudflare.
- **[`ui-reference-screens`](https://github.com/KRCUPRO/ui-reference-screens)** — Console d'opérations et écrans de référence pour passerelles d'API d'entreprise.
- **[`dev-timeline`](https://github.com/KRCUPRO/dev-timeline)** — Journal de recherche système et registre de commits sans dépendance externe (2022–présent).

---

<div align="center">
  <a href="https://github.com/KRCUPRO">
    <img src="./assets/stats.svg" alt="Focus and Capabilities" width="100%" />
  </a>

  <br /><br />
  <sub><i>"La simplicité est la condition préalable de la fiabilité. L\'état déclaratif est la condition de la sérénité."</i></sub>
</div>
