(🇬🇧Scroll down for English Version.)

[🇯🇵 日本語]
# AO-Workshop 公式 VCC リポジトリ

*ExrolTools により運営*

これは **AO Nails Auto Installer** 用の公式 VRChat Creator Companion (VCC) リポジトリです。
このツールを使用することで、対応しているVRChatアバターへ AO-Workshop のネイルデザインをわずか数クリックで簡単にフィット・設定・導入できます。

🔗 **[AO-Workshop BOOTHストア](https://ao-workshop.booth.pm/)**
💬 **[サポート・アップデート用 Discord に参加する](https://discord.gg/S2U74x9pQG)**

---

## 📥 1. インストール方法

最も簡単な導入方法は、VRChat Creator Companion から直接インストールする方法です。

### Step 1: VCCへリポジトリを追加する
1. 以下のリンクをクリックしてリポジトリを追加してください：
   **[Add to VCC](vcc://vpm/addRepo?url=https://ExrolTools.github.io/AONails-Installer/index.json)**
2. ブラウザが VRChat Creator Companion を開くか確認してきますので、**Yes** を押してください。
3. VCC上でリポジトリ追加の警告画面が表示されますので、**I Understand, Add Repository** を押してください。
4. VCC の **Settings > Packages** を開き、**AO-Workshop Official Repository** のチェックボックスが有効になっていることを確認してください。

### Step 2: プロジェクトへインストールする
> ⚠️ **重要な前提条件:** AO Nails Installer は **[Modular Avatar](https://modular-avatar.nadena.dev/)** を利用して、安全にアセットを適用します。導入前に必ず Modular Avatar がプロジェクトへインストールされていることを確認してください。

1. VCC の **Projects** タブを開き、対象アバタープロジェクトの **Manage Project** をクリックしてください。
2. 一番下までスクロールすると **AO Nails Auto Installer** が表示されます。
3. **(Not Installed)** をクリックし、ドロップダウンから最新バージョンを選択してインストールしてください。

---

## 💅 2. インストーラーの使い方

1. Unityプロジェクトを開いてください。
2. Unity上部メニューバーの **AO-Workshop** → **AO Nails Auto Installer** を開いてください。
3. **Target Avatar:** Scene Hierarchy 内のアバターを "Drag Avatar Here" スロットへドラッグ＆ドロップしてください。
   * *ツールが自動で使用している素体を検出し、緑色で表示します。*
   * *アバターが大きく改変されている場合や検出に失敗した場合は、**"Incorrect body base? Click here"** を押して対応素体一覧から手動選択してください。*
4. **Select Nail Design:** インストールしたいネイルデザインを選択してください。
   （すでに所有していてプロジェクトへインポート済みのデザインは上部へ優先表示されます。）
5. **Install:**
   * **One-Click Install:** 標準設定でインストールします。手用ネイル、足用ネイル、VRChatメニュー、カラー変更メニュー（対応デザインのみ）を自動で導入します。
   * **Advanced Install Options:** 詳細設定モードです。手のみ、足のみの導入、パラメータ節約のためのメニュー削除、インストール前の **BlendShape**（例: ハイヒール対応）調整などを行えます。

### デザイン変更・再インストール
別のネイルデザインへ変更したい場合や再インストールしたい場合：

1. Hierarchy内の `AO_Nails_[AvatarName]_AO_Workshop` Prefab を削除してください。
2. ツールを開き、再度インストールを実行してください。

### ツールのアップデート
新しいバージョンのインストーラーが公開された場合、新しいzipファイルをダウンロードする必要はありません。
VCC の **Manage Project** を開き、AO Nails Auto Installer のバージョン選択欄から最新バージョンを選択するだけで更新できます。

---

## ⚖️ ライセンス

本ソフトウェアおよび関連アセットは proprietary（独占ライセンス）です。
再配布、無断共有、改変、アセット抽出は禁止されています。

詳細については同梱されている `LICENSE.md` をご確認ください。

---

[🇬🇧 EN]
# AO-Workshop Official VCC Repository

*Operated by ExrolTools*

This is the official VRChat Creator Companion (VCC) repository for the **AO Nails Auto Installer**. This tool allows you to effortlessly fit, and configure AO-Workshop nail designs onto supported VRChat avatars with two clicks.

🔗 **[Visit the AO-Workshop BOOTH Store](https://ao-workshop.booth.pm/)**
💬 **[Join the Discord for Support & Updates](https://discord.gg/S2U74x9pQG)**

---

## 📥 1. Installation Instructions

The easiest way to install the tool is directly through the VRChat Creator Companion.

### Step 1: Add the Repository to VCC
1. Click the following link to add the repo: **[Add to VCC](vcc://vpm/addRepo?url=https://ExrolTools.github.io/AONails-Installer/index.json)**
2. Your browser will prompt you to open the VRChat Creator Companion. Click **Yes**.
3. VCC will display a warning asking if you want to add the repository. Click **I Understand, Add Repository**.
4. In VCC, go to **Settings > Packages**. Scroll down and ensure the box next to **AO-Workshop Official Repository** is checked.

### Step 2: Install to your Project
> ⚠️ **IMPORTANT PREREQUISITE:** The AO Nails installer relies on **[Modular Avatar](https://modular-avatar.nadena.dev/)** to safely apply assets without breaking your avatar. Please ensure Modular Avatar is installed in your project!

1. In VCC, go to the **Projects** tab and click **Manage Project** on your desired avatar project.
2. Scroll to the bottom to find **AO Nails Auto Installer**.
3. Click the **(Not Installed)** field and select the latest version from the dropdown menu to install it into your project.

---

## 💅 2. How to Use the Installer

1. Open your Unity Project.
2. At the very top menu bar in Unity, click **AO-Workshop** -> **AO Nails Auto Installer**.
3. **Target Avatar:** Drag and drop your avatar from the Scene Hierarchy directly into the "Drag Avatar Here" slot.
   * *The tool will automatically detect your body base and display it in green.*
   * *If your avatar is heavily edited or fails to detect, simply click **"Incorrect body base? Click here"** to select your base manually from the supported dropdown list.*
4. **Select Nail Design:** Choose the nail design you wish to install. (Designs you currently own and have imported into your project will be highlighted at the top).
5. **Install:**
   * **One-Click Install:** Click this for the default setup. It automatically installs hand nails, feet nails, VRChat toggles, and color customization menus (if supported by the design).
   * **Advanced Install Options:** Click this to customize your install. Here you can choose to install only hands or only feet, selectively remove VRChat toggle menus to save parameter space, and adjust specific **Blendshapes** (like High Heels) before installation!

### Making Changes / Updating Designs
If you want to swap to a different nail design or reinstall:
1. Delete the `AO_Nails_[AvatarName]_AO_Workshop` prefab from your avatar in the hierarchy.
2. Open the tool and run the installation process again!

### Updating the Tool
Whenever a new version of the installer is released, you do not need to download a new zip file! Simply open VCC, click **Manage Project**, and select the newest version from the dropdown menu next to the AO Nails Auto Installer.

---

## ⚖️ License
This software and its associated assets are proprietary. Redistribution, unauthorized sharing, modification, or asset extraction is strictly prohibited. For full details, please read the included `LICENSE.md`.


[🇯🇵 日本語]
# AO-Workshop 公式 VCC リポジトリ

*ExrolTools により運営*

これは **AO Nails Auto Installer** 用の公式 VRChat Creator Companion (VCC) リポジトリです。
このツールを使用することで、対応しているVRChatアバターへ AO-Workshop のネイルデザインをわずか数クリックで簡単にフィット・設定・導入できます。

🔗 **[AO-Workshop BOOTHストア](https://ao-workshop.booth.pm/)**
💬 **[サポート・アップデート用 Discord に参加する](https://discord.gg/S2U74x9pQG)**

---

## 📥 1. インストール方法

最も簡単な導入方法は、VRChat Creator Companion から直接インストールする方法です。

### Step 1: VCCへリポジトリを追加する
1. 以下のリンクをクリックしてリポジトリを追加してください：
   **[Add to VCC](vcc://vpm/addRepo?url=https://ExrolTools.github.io/AONails-Installer/index.json)**
2. ブラウザが VRChat Creator Companion を開くか確認してきますので、**Yes** を押してください。
3. VCC上でリポジトリ追加の警告画面が表示されますので、**I Understand, Add Repository** を押してください。
4. VCC の **Settings > Packages** を開き、**AO-Workshop Official Repository** のチェックボックスが有効になっていることを確認してください。

### Step 2: プロジェクトへインストールする
> ⚠️ **重要な前提条件:** AO Nails Installer は **[Modular Avatar](https://modular-avatar.nadena.dev/)** を利用して、安全にアセットを適用します。導入前に必ず Modular Avatar がプロジェクトへインストールされていることを確認してください。

1. VCC の **Projects** タブを開き、対象アバタープロジェクトの **Manage Project** をクリックしてください。
2. 一番下までスクロールすると **AO Nails Auto Installer** が表示されます。
3. **(Not Installed)** をクリックし、ドロップダウンから最新バージョンを選択してインストールしてください。

---

## 💅 2. インストーラーの使い方

1. Unityプロジェクトを開いてください。
2. Unity上部メニューバーの **AO-Workshop** → **AO Nails Auto Installer** を開いてください。
3. **Target Avatar:** Scene Hierarchy 内のアバターを "Drag Avatar Here" スロットへドラッグ＆ドロップしてください。
   * *ツールが自動で使用している素体を検出し、緑色で表示します。*
   * *アバターが大きく改変されている場合や検出に失敗した場合は、**"Incorrect body base? Click here"** を押して対応素体一覧から手動選択してください。*
4. **Select Nail Design:** インストールしたいネイルデザインを選択してください。
   （すでに所有していてプロジェクトへインポート済みのデザインは上部へ優先表示されます。）
5. **Install:**
   * **One-Click Install:** 標準設定でインストールします。手用ネイル、足用ネイル、VRChatメニュー、カラー変更メニュー（対応デザインのみ）を自動で導入します。
   * **Advanced Install Options:** 詳細設定モードです。手のみ、足のみの導入、パラメータ節約のためのメニュー削除、インストール前の **BlendShape**（例: ハイヒール対応）調整などを行えます。

### デザイン変更・再インストール
別のネイルデザインへ変更したい場合や再インストールしたい場合：

1. Hierarchy内の `AO_Nails_[AvatarName]_AO_Workshop` Prefab を削除してください。
2. ツールを開き、再度インストールを実行してください。

### ツールのアップデート
新しいバージョンのインストーラーが公開された場合、新しいzipファイルをダウンロードする必要はありません。
VCC の **Manage Project** を開き、AO Nails Auto Installer のバージョン選択欄から最新バージョンを選択するだけで更新できます。

---

## ⚖️ ライセンス

本ソフトウェアおよび関連アセットは proprietary（独占ライセンス）です。
再配布、無断共有、改変、アセット抽出は禁止されています。

詳細については同梱されている `LICENSE.md` をご確認ください。
