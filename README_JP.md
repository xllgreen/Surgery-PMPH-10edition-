# Surgery-PMPH-10edition
<div align="center">

> *「21世紀 医学生ガイド」*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Skills](https://img.shields.io/badge/skills.sh-Compatible-green)](https://skills.sh)

<br>
> 人民衛生出版社『外科学』第10版に基づく臨床スキルハンドブック — 240の外科・救急・集中治療臨床スキル
<br>
<br>
<img src="https://github.com/xllgreen/Surgery-PMPH-10edition-/blob/main/assets/Surgery.png" width="260px">
<br>

分厚い教科書を全部読む必要なんてありません<br>
質問を入力するだけで、教科書から自動的に解決策を見つけられます

<br>

**他の言語 / Other Languages:**

[English](README_EN.md) · [日本語](README_JP.md) · [Français](README_FR.md) · [Русский](README_RU.md)

</div>

---

## プロジェクト概要

本プロジェクトは、臨床外科学、救急・集中治療医学、周術期管理、外傷治療、腫瘍総合治療、感染制御、多系統疾患の診断と治療などの中核領域を体系的に統合し、**240の主要臨床スキル**を17の大分類にまとめています。

**対象読者**: 外科医、救急医、ICUチーム、医学生

**参考教科書**: 人民衛生出版社『外科学』第10版

## プロジェクト構成

```
Surgery-PMPH-10edition/
├── SKILL.md              # コア設定 — 240スキルのレジストリ
├── README.md             # プロジェクト説明と使用ガイド
├── <skill-name>/         # 各スキルの詳細定義
│   └── SKILL.md          #   スキル詳細（使用時期、手順、参考資料）
├── scripts/              # 実行可能ツールスクリプト
│   ├── skill-search.sh   #   スキルキーワード検索
│   └── skill-report.sh   #   スキル一覧レポート生成
├── config/               # 設定ファイル
│   └── skill-config.yaml #   スキル分類とメタデータ設定
└── tests/                # 検証とテスト
    └── validate-all.sh   #   整合性チェックスクリプト
```

## スキル分類一覧

| 分類 | スキル数 | 説明 |
|------|----------|------|
| 🚑 救急・蘇生 | 14 | CPR、ショック蘇生、電解質異常 |
| 🦴 外傷・骨折 | 27 | 骨折分類、整復固定、神経損傷 |
| 🩺 一般外科・腹部救急 | 22 | 虫垂炎、腸閉塞、ヘルニア、腹膜炎 |
| 🫁 肝胆膵脾外科 | 19 | 胆道結石、膵炎、肝外傷 |
| 🩻 胃腸外科 | 10 | 胃癌、大腸癌、GERD |
| 🫘 泌尿器科 | 24 | 結石、腫瘍、感染、尿道損傷 |
| 🩸 血管外科 | 7 | DVT、静脈瘤、血管修復 |
| 🔥 熱傷・形成外科 | 8 | 面積推定、深度分類、植皮 |
| 🧬 腫瘍外科・総合治療 | 16 | TNM分類、化学放射線療法、四肢温存手術 |
| 📋 周術期管理 | 18 | 術前最適化、抗生物質、栄養サポート |
| 💉 麻酔・疼痛 | 11 | 気道管理、脊椎麻酔、局所麻酔 |
| ⚖️ 内分泌・代謝 | 6 | 副甲状腺機能亢進症、脱水、電解質 |
| 🦠 感染・免疫 | 7 | 結核、敗血症、破傷風 |
| 📡 画像診断・インターベンション | 10 | 血管造影、内視鏡、IVR |
| 🏋️ リハビリテーション・機能評価 | 12 | 骨折リハビリ、神経評価 |
| 🦿 リウマチ・脊椎疾患 | 5 | 強直性脊椎炎、脊柱管狭窄症 |
| 🔧 その他の専門スキル | 10 | ARDS、AKI、除細動など |

## クイックスタート

### インストール

CLI：
```bash
openclaw skills install surgery-pmph-10edition
```

Prompt：
```bash
Before installing anything, inspect the ClawHub skill metadata and setup requirements.
If the skill asks you to install a third-party package or CLI, verify its source, maintainer, and package contents before running the install command.
Install the skill "Surgery-PMPH-10edition" (xllgreen/surgery-pmph-10edition) from ClawHub only after those checks pass.
Skill page: https://clawhub.ai/xllgreen/surgery-pmph-10edition
Keep the work scoped to this skill only.
After install, help me finish setup from verified skill metadata.
Use only the metadata you can verify from ClawHub; do not invent missing requirements.
Ask before making any broader environment changes.
```

### スキル検索

```bash
# キーワード検索
bash scripts/skill-search.sh 虫垂炎

# スキル一覧レポート生成
bash scripts/skill-report.sh
```

### 使用方法

各スキルは4つのセクションで構成されています：
1. **使用時期** — このスキルをいつ実行するか
2. **手順** — 標準化された操作フロー
3. **注意事項** — 禁忌と警告
4. **参考資料** — 詳細な補足資料

## 著者について

**xllgreen ([xllgreen.github.io](https://xllgreen.github.io))** — 九江学院臨床医学院の医学生 · テックギーク

## ライセンス

本プロジェクトの内容は、人民衛生出版社『外科学』第10版に基づいて整理されたものであり、学習参考のみを目的としています。

## Star History

<a href="https://www.star-history.com/?repos=xllgreen%2FSurgery-PMPH-10edition-&type=date&legend=top-left">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=xllgreen/Surgery-PMPH-10edition-&type=date&theme=dark&legend=top-left" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=xllgreen/Surgery-PMPH-10edition-&type=date&legend=top-left" />
   <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=xllgreen/Surgery-PMPH-10edition-&type=date&legend=top-left" />
 </picture>
</a>
