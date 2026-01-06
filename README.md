# MadPunk Dev | FW Verification

![Status](https://img.shields.io/website?url=https%3A%2F%2Ffw.madpunk.dev&label=FW%20Status)
![License](https://img.shields.io/badge/license-MIT-green)

> **fw.madpunk.dev** is a dedicated subdomain for testing **Font Awesome Free** (SVG) rendering behaviors within the MadPunks ecosystem.
>
> **fw.madpunk.dev** は、MadPunksエコシステム内における **Font Awesome Free** (SVG) の描画挙動を検証するための専用サブドメインです。

---

## 🎯 Purpose / 目的

* **Verify Rendering:** Verify rendering of "Free" version SVG icons.
* **Favicon Test:** Test favicon compatibility across different browsers using Font Awesome assets.
* **Operational Efficiency with Transparency:** To simplify verification, the active file is always renamed to `icon.svg`. However, the original filename and source link are explicitly documented in the `index.html` UI to maintain respect for the source.

* **描画検証:** Font Awesome "Free" 版SVGアイコンの描画確認を行います。
* **Faviconテスト:** 各ブラウザにおけるファビコンの互換性を検証します。
* **透明性を保った運用効率化:** 検証を簡素化するため、使用するファイルは常に `icon.svg` にリネームして配置されます。ただし、ソース（配布元）へのリスペクトを維持するため、オリジナルのファイル名と出典リンクは `index.html` のUI上に明記されます。

## ⚙️ Workflow / 運用フロー

To maintain a consistent testing environment:
一貫した検証環境を維持するための手順:

1.  **Download:** Get the SVG from [Font Awesome Free](https://fontawesome.com).
    * [Font Awesome Free](https://fontawesome.com) からSVGをダウンロードします。
2.  **Rename:** Rename the file to `icon.svg` and upload it to the root directory.
    * ファイルを `icon.svg` にリネームし、ルートディレクトリにアップロードします。
3.  **Log:** Update the "Meta Info" section in `index.html` with the original filename and source URL.
    * `index.html` 内の "Meta Info" セクションを更新し、オリジナルのファイル名とソースURLを記載します。

## ⚖️ Credits & License / クレジットとライセンス

This project utilizes assets from **Font Awesome Free**.
このプロジェクトは **Font Awesome Free** のアセットを使用しています。

* **Icons:** [Font Awesome Free](https://fontawesome.com) 
* **License:** [CC BY 4.0](https://fontawesome.com/license/free)
* **Modifications:** The file content is used as-is. Only the filename is changed to `icon.svg` for system consistency.
    * **変更点:** ファイルの内容はそのまま使用しています。システムの整合性のため、ファイル名のみ `icon.svg` に変更しています。

---
&copy; 2026 MadPunk Dev.