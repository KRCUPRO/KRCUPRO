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

### 💡 プロフィール (Executive Overview)

はじめまして！宣言型ベアメタルインフラ、分散ストレージ、高スループットAIゲートウェイ、および自律エージェントランタイムを専門とするシステム＆クラウドネイティブエンジニア **KRCUPRO (조효준)** です。

**宣言的な再現性と高パフォーマンスな実行力が両立するアーキテクチャ**を構築します。Rook Ceph分散ストレージを備えた4ノード物理NixOSクラスタから、分散MCPパイプラインを統括するGoスーパーバイザや無停止マイクロサービスまで、妥協のないエンジニアリングを追求しています。

---

### 🏛️ コアエンジニアリング領域 & アーキテクチャ

#### 1. 🌐 ベアメタルインフラ & 宣言型GitOps
- **4ノード物理クラスタ (`myu`)**: NixOS Flakesで一元管理されるベアメタルKubernetesクラスタ（`ken` コントロールプレーン、`decker`, `calder`, `usher` ワーカーノード）。
- **GitOps継続的デリバリー**: **FluxCD**によるクラスタ全体の自動同期、CNI、デュアルIngress、自動化されたTLSライフサイクル管理。
- **分散ストレージ**: 物理NVMe/SSDを統合し、高可用なブロックおよび共有ファイルシステムを提供する **Rook Ceph** の運用。

#### 2. ⚡ AIゲートウェイ、MCPプロトコル & 自律ランタイム
- **エンタープライズAIゲートウェイ**: クォータ管理、負荷分散、5ms未満の自動フェイルオーバーを備えた高並行リバースプロキシ（`myu-gateway`, `mcp-gateway`）。
- **ネイティブエージェントスーパーバイザ**: **Goプロセススーパーバイザ**、ブルー/グリーンPythonワーカー分離、冪等なツール実行基盤。
- **Model Context Protocol (MCP)**: ハードウェア暗号金庫（DPAPI）やCloudflareエッジルーティングと連携した分散MCPオーケストレーション。

#### 3. 🛡️ システムフォレンジック & アクティブ防御
- **SecOps & テレメトリダッシュボード**: マルチノードクラスタのリアルタイム監視、SSHセッション監査、アクティブ防御スイート。
- **ゼロ依存システム研究**: 定数時間暗号実装（AEAD, Ed25519）とゼロアロケーションバイナリ解析（`dev-timeline`）。

---

### 💻 総合技術スタック (Technology Stack)

| ドメイン | 主要技術 & ツール |
| :--- | :--- |
| **言語 & ランタイム** | `Go`, `Rust`, `TypeScript`, `Nix`, `Python`, `Shell (Bash / PowerShell)`, `SQL` |
| **クラウドネイティブ & オーケストレーション** | `Kubernetes (Kubeadm)`, `NixOS Flakes`, `FluxCD (GitOps)`, `Rook Ceph`, `Docker / Compose`, `Containerd` |
| **AIゲートウェイ & プロトコル** | `Model Context Protocol (MCP)`, `Claude Code Router (CCR)`, `REST / gRPC`, `WebSocket`, `Webhooks` |
| **エッジ、インプレス & ネットワーク** | `Cloudflare Workers / D1 / Queues`, `Nginx`, `WireGuard`, `PCAP / パケット解析` |
| **オブザーバビリティ & セキュリティ** | `クラスタテレメトリダッシュボード`, `SSH監査システム`, `アクティブ防御`, `定数時間暗号` |

---

### 📁 主なアーキテクチャリポジトリ (Featured Repositories)

- **[`kuber-nixos-config`](https://github.com/KRCUPRO/kuber-nixos-config)** — 4ノード `myu` クラスタの宣言型ホスト基盤（NixOS flakes, Ceph準備, Kubeadm連携）。
- **[`kuber-infrastructure`](https://github.com/KRCUPRO/kuber-infrastructure)** — CNI、Ingress、ストレージクラスを管理するFluxCD GitOpsリポジトリ。
- **[`chatgpt-windows-work`](https://github.com/KRCUPRO/chatgpt-windows-work)** — Goスーパーバイザとブルー/グリーン構成を備えたWindowsネイティブMCPランタイム。
- **[`ui-reference-screens`](https://github.com/KRCUPRO/ui-reference-screens)** — エンタープライズAPIゲートウェイ運用画面およびランディング画面のリファレンス。
- **[`dev-timeline`](https://github.com/KRCUPRO/dev-timeline)** — ゼロ依存の暗号学・バイナリ解析研究コミット元帳（2022–現在）。

---

<div align="center">
  <a href="https://github.com/KRCUPRO">
    <img src="./assets/stats.svg" alt="Focus and Capabilities" width="100%" />
  </a>

  <br /><br />
  <sub><i>"シンプルさは信頼性の前提条件であり、宣言的な状態は平穏の前提条件である。"</i></sub>
</div>
