# SceneryShield
<img src="LicenceKeyGenerator.png" width="128" alt="LicenceKeyGenerator Icon">

**SceneryShield** is a professional-grade DRM and encryption solution designed specifically for Microsoft Flight Simulator (MSFS) scenery developers. It protects paid assets through a combination of secure physical isolation, hardcoded license validation, and traceable digital fingerprints—ensuring creators maintain control over their distribution while deterring piracy without disrupting the end-user experience.

The first production release has been successfully implemented for **Ryan Ye's Wenzhou Longwan Airport (ZSWZ)**.

---

## 🌐 Project Overview / 项目简介 / Présentation du Projet / プロジェクト概要

### English

SceneryShield provides a robust defense for high-value MSFS assets. By utilizing a library-link architecture, it ensures that your raw scenery files are never directly exposed in the user's Community folder, preventing easy "copy-paste" piracy while maintaining full compatibility with MSFS 2020 and 2024.

### 中文 (简体)

SceneryShield 为高价值 MSFS 资产提供坚实的防御。通过采用“库-链接”架构，它确保您的地景原始文件永远不会直接暴露在用户的 Community 文件夹中，在保持与 MSFS 2020 和 2024 完全兼容的同时，杜绝了简单的“复制粘贴”式盗版行为。首个正式版本已应用于 **Ryan Ye 温州龙湾机场 (ZSWZ)** 地景项目。

### Français

SceneryShield offre une défense robuste pour les actifs MSFS de haute valeur. En utilisant une architecture de type "bibliothèque-lien", il garantit que vos fichiers de scènes bruts ne sont jamais directement exposés dans le dossier Community de l'utilisateur, empêchant ainsi le piratage par simple "copier-coller" tout en maintenant une compatibilité totale avec MSFS 2020 et 2024. La première version a été implémentée pour l'aéroport **Wenzhou Longwan (ZSWZ) de Ryan Ye**.

### 日本語

SceneryShield は、高価値な MSFS アセットに強力な防御を提供します。ライブラリ・リンク・アーキテクチャを採用することで、シーナリーの生ファイルがユーザーの Community フォルダに直接公開されるのを防ぎます。これにより、MSFS 2020 および 2024 との完全な互換性を維持しながら、単純なコピー＆ペーストによる海賊版行為を防止します。初の正式リリースは **Ryan Ye 氏の温州龍湾国際空港 (ZSWZ)** プロジェクトに導入されています。

---

## 🛠️ Key Features / 核心功能 / Caractéristiques Principales / 主な機能

* **Secure Library Isolation**: Encapsulates scenery assets within a protected system directory, hidden from standard user access.
* **Symbolic Mapping Integration**: Seamlessly connects the hidden library to the MSFS `Community` folder via managed symbolic links.
* **Traceable Digital Watermarking**: Automatically embeds unique user identifiers, hardware IDs (HWID), and timestamps deep within the asset structure during installation for post-leak forensics.
* **Multi-Key License System**: Utilizes a custom-built License Key Generator to provide unique, 25-digit verification codes for every legitimate purchaser.

---

## 🖥️ Upcoming GUI Tool / GUI 自动化工具 / Outil GUI à Venir / GUI ツール

### English

A dedicated GUI application is currently in development to allow developers to self-encrypt their projects and manage releases independently. This tool will streamline the SceneryShield workflow, making advanced DRM accessible to all creators.

### 中文 (简体)

目前正在开发一款专用的 GUI 应用程序，允许开发者自行对项目进行加密并独立管理发布。该工具将简化 SceneryShield 的工作流程，让所有创作者都能轻松使用高级 DRM 保护。

### Français

Une application GUI dédiée est actuellement en cours de développement pour permettre aux développeurs de chiffrer eux-mêmes leurs projets et de gérer leurs sorties de manière indépendante. Cet outil simplifiera le flux de travail de SceneryShield, rendant les DRM avancés accessibles à tous les créateurs.

### 日本語

開発者が自身のプロジェクトを自ら暗号化し、独立してリリースを管理できる専用の GUI アプリケーションを現在開発中です。このツールにより、SceneryShield のワークフローが簡素化され、すべてのクリエイターが高度な DRM を利用できるようになります。

---

## ✉️ Contact for Early Access / 联系与测试 / Contact pour l'Accès Anticipé / 連絡先

### English

While the initial release is live, we are actively seeking scenery developers to participate in the early access phase for the upcoming GUI tool. We continue to offer **Free Packaging and Encryption Services** for high-quality scenery projects to further refine our security logic.

### 中文 (简体)

我们目前为少数地景开发者提供 **免费封装服务**，以测试 SceneryShield 的可靠性。如果您有兴趣为您即将发布的 MSFS 项目提供保护，请直接联系我以获取定制方案。

### Français

Bien que la version initiale soit déjà disponible, nous recherchons activement des développeurs de scènes pour participer à la phase d'accès anticipé du futur outil GUI. Nous continuons d'offrir des **services d'empaquetage et de chiffrement gratuits** pour les projets de scènes de haute qualité afin de perfectionner notre logique de sécurité.

### 日本語

現在、SceneryShield の有効性をテストするため、限定数のシーナリー開発者に **無料パッケージングサービス** を提供しています。新しい MSFS プロジェクトの保護にご興味のある方は、カスタムソリューションについて直接お問い合わせください。

---

## 📅 Roadmap / 开发路线图 / Feuille de Route / ロードマップ

* **February 2026**: V1.0 Release - Successfully implemented for **Ryan Ye ZSWZ Scenery**.
* **Active Development**: GUI automation tool for self-encryption and license management.
* **May 2026**: Expected release of the **SceneryShield GUI Developer Suite**.

---

**Author**: Chutian (Sky) Ning

**Location**: Toronto, Ontario, Canada
