# Welcome to nigiri-rice.com 🍙

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Outfit&size=24&pause=1000&color=2563EB&center=true&vCenter=true&width=650&height=50&lines=Enterprise+Hybrid+Cloud+Architecture;Zero-Trust+Identity+%26+Access+Governance;Practical+Open-Source+Engineering" alt="Typing SVG" />
</p>

<p align="center">
  <strong>自社インフラ・プライベートクラウドからゼロトラストID基盤、モダンWebアプリケーションまで、高可用性と自律運用を追求するエンジニアリング・オーガニゼーション</strong>
</p>

<p align="center">
  <a href="https://www.nigiri-rice.com" target="_blank">
    <img src="https://img.shields.io/badge/Official-Website-blue?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website" />
  </a>
  <a href="https://status.nigiri-rice.com" target="_blank">
    <img src="https://img.shields.io/badge/System-Status%20Page-emerald?style=for-the-badge&logo=statuspage&logoColor=white" alt="Status" />
  </a>
  <a href="https://www.nigiri-rice.com/portal/docs" target="_blank">
    <img src="https://img.shields.io/badge/Developer-Docs%20Portal-purple?style=for-the-badge&logo=gitbook&logoColor=white" alt="Docs" />
  </a>
</p>

---

## 🏛️ About Us & Engineering Philosophy

**nigiri-rice.com** では、「オープンスタンダードの徹底」「安全なゼロトラスト境界の確立」「運用の自動化」を行動規範とし、エンタープライズ水準の堅牢性と自律的なスケーラビリティを両立するインフラおよびソフトウェアを設計・実装しています。

- 🔑 **Identity-First (ID中心設計):** Keycloak を全システムの唯一無二の正本（Source of Truth）と定め、オンプレミスからマルチクラウドまでシームレスなゼロトラスト認可を実現。
- ⚡ **Hybrid Cloud (ハイブリッドクラウド):** パブリック VPS（k3s Kubernetes）とオンプレミス仮想化基盤（Proxmox VE）を WireGuard 暗号化メッシュ（Tailscale）で透過直結。
- 🛠️ **Practical OSS Customization (実践的オープンソース拡張):** 既存OSSの単なる導入にとどまらず、現場の課題を打破する独自のカーネル監視、同期デーモン、セキュリティゲートウェイを自社開発して公開。

---

## 🌟 Featured Projects (独自開発・主要オープンソース)

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <h3>🚀 <a href="https://github.com/nigiri-rice-com/hybrid-cloud-storage">hybrid-cloud-storage</a></h3>
      <p><strong>Nextcloud Hub × Samba 4 AD DC ハイブリッドストレージ基盤</strong></p>
      <ul>
        <li>デュアルプロトコル直接ローカルマウント（SMB 3.1.1 + WebDAV）</li>
        <li>Linux カーネル <code>inotify</code> リアルタイム差分検知＆デバウンス同期</li>
        <li>Keycloak OIDC 管理者権限自動昇格 & 姓名順最適化</li>
        <li>Windows / Mac / iOS / Android 全デバイスシームレス対応</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Nextcloud-v35-0082c9?style=flat-square&logo=nextcloud&logoColor=white" />
        <img src="https://img.shields.io/badge/Samba-AD%20DC-red?style=flat-square" />
        <img src="https://img.shields.io/badge/License-MIT-blue?style=flat-square" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>🔑 <a href="https://github.com/nigiri-rice-com/omusubi-idp-core">omusubi-idp-core</a></h3>
      <p><strong>OmusuBI — Keycloak 24+ を核とした全社統合IDプラットフォーム</strong></p>
      <ul>
        <li>全社Webサービス・仮想化基盤のゼロトラスト OIDC/SAML SSO</li>
        <li>日本語環境に最適化されたカスタム Tailwind UI テーマ</li>
        <li>Samba 4 Active Directory SAM DB 一方向属性強制上書き同期デーモン</li>
        <li>HashiCorp Vault 連携によるシークレット一元管理</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Keycloak-24.0+-red?style=flat-square&logo=keycloak&logoColor=white" />
        <img src="https://img.shields.io/badge/PostgreSQL-16-blue?style=flat-square&logo=postgresql&logoColor=white" />
        <img src="https://img.shields.io/badge/License-MIT-blue?style=flat-square" />
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🔒 <a href="https://github.com/nigiri-rice-com/mailcow-secure-share-gateway">mailcow-secure-share-gateway</a></h3>
      <p><strong>脱PPAP 自動迎撃＆暗号化ファイル共有ゲートウェイ</strong></p>
      <ul>
        <li>送信メールの添付ファイルを自動迎撃し、一時共有URLへ自動置換</li>
        <li>AES-256-GCM による強力なファイル暗号化と改ざん防止認証タグ</li>
        <li>受信者宛てワンタイムパスワード (OTP) 二要素認証</li>
        <li>Office / CSV / 3D CAD(STL) / SVG / PDF 全方位インラインWebプレビュー</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Python-3.10+-yellow?style=flat-square&logo=python&logoColor=white" />
        <img src="https://img.shields.io/badge/AES--256--GCM-Encrypted-success?style=flat-square" />
        <img src="https://img.shields.io/badge/License-MIT-blue?style=flat-square" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>📊 <a href="https://github.com/nigiri-rice-com/developer-portal-and-observability">developer-portal-and-observability</a></h3>
      <p><strong>7つの必須ドキュメント体系 開発者ポータル ＆ 統合監視基盤</strong></p>
      <ul>
        <li>Qiita人気知見（@komeri氏提唱）を参考に実務適用した7大ドキュメント統合ポータル（FastAPI）</li>
        <li>Mermaid.js によるアーキテクチャ図の動的描画＆全文検索エンジン</li>
        <li>Uptime Kuma による外形監視＆パブリックステータスページ</li>
        <li>Prometheus ＆ Grafana による包括的フルスタック可観測性</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/FastAPI-0.110+-009688?style=flat-square&logo=fastapi&logoColor=white" />
        <img src="https://img.shields.io/badge/Uptime%20Kuma-Monitoring-success?style=flat-square" />
        <img src="https://img.shields.io/badge/License-MIT-blue?style=flat-square" />
      </p>
    </td>
  </tr>
</table>

---

## 🛠️ Technology Stack

<p align="left">
  <!-- Infrastructure & Virtualization -->
  <img src="https://img.shields.io/badge/Kubernetes-k3s-326ce5?style=flat-square&logo=kubernetes&logoColor=white" alt="k3s" />
  <img src="https://img.shields.io/badge/Proxmox_VE-8.x-e57000?style=flat-square&logo=proxmox&logoColor=white" alt="Proxmox" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white" alt="Ubuntu" />
  <img src="https://img.shields.io/badge/Debian-A81D33?style=flat-square&logo=debian&logoColor=white" alt="Debian" />
  <br/>
  <!-- Networking & Edge -->
  <img src="https://img.shields.io/badge/Tailscale-WireGuard-000000?style=flat-square&logo=tailscale&logoColor=white" alt="Tailscale" />
  <img src="https://img.shields.io/badge/Caddy-v2-22b573?style=flat-square&logo=caddy&logoColor=white" alt="Caddy" />
  <img src="https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white" alt="Cloudflare" />
  <img src="https://img.shields.io/badge/ArgoCD-GitOps-EF6C00?style=flat-square&logo=argo&logoColor=white" alt="ArgoCD" />
  <br/>
  <!-- Languages & Runtimes -->
  <img src="https://img.shields.io/badge/Python-3.11+-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go" />
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white" alt="Bash" />
  <br/>
  <!-- Data & Cache -->
  <img src="https://img.shields.io/badge/PostgreSQL-16-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Redis-7-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis" />
  <img src="https://img.shields.io/badge/MariaDB-10.11-003545?style=flat-square&logo=mariadb&logoColor=white" alt="MariaDB" />
  <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" alt="SQLite" />
</p>

---

## 📬 Connect & Resources

- 🌐 **Corporate Website:** [https://www.nigiri-rice.com](https://www.nigiri-rice.com)
- 📊 **Service Status Page:** [https://status.nigiri-rice.com](https://status.nigiri-rice.com)
- 📚 **Developer Portal:** [https://www.nigiri-rice.com/portal/docs](https://www.nigiri-rice.com/portal/docs)
- 💼 **Technology Portfolio:** [https://www.nigiri-rice.com/category/portfolio/](https://www.nigiri-rice.com/category/portfolio/)
- 📧 **Inquiries:** [info@nigiri-rice.com](mailto:info@nigiri-rice.com)

<p align="center">
  <sub>&copy; 2026 nigiri-rice.com. All rights reserved.</sub>
</p>