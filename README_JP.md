# 系統解剖学 第10版

<div align="center">

> *「21世紀の医学生ガイド」*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![ClawHub](https://img.shields.io/badge/ClawHub-Compatible-orange)](https://clawhub.ai)

<br>
> 人民衛生出版社『系統解剖学』第10版に基づく臨床解剖スキルハンドブック — 112 のコア解剖スキル
<br>
<br>
<img src="/assets/Systematic-Anatomy-10edition.jpg" width="260px">
<br>

人体解剖学は医学の基盤です。<br>
骨格から神経、血管から内臓まで — 系統解剖、精密に、細部まで。

<br>

**他の言語 / Other Languages:**

[English](README_EN.md) · [简体中文](README.md) · [Français](README_FR.md) · [Русский](README_RU.md)

</div>

---

## プロジェクト概要

本プロジェクトは、人体解剖学、神経解剖学、臨床応用解剖学、中西医結合解剖分析などの中核領域を体系的に統合し、**112 の重要解剖スキル**を 8 大カテゴリに分類して収録しています。

**対象読者**：医学生、臨床医、解剖学研究者、外科研修医

**参考教科書**：人民衛生出版社『系統解剖学』第10版（主任監修：丁文龍；編集長：崔慧先、劉学政）

**⚠️ 免責事項 ⚠️**：本スキル集は人体構造の記述、解剖変異の分析、外科的アプローチの評価、臨床局在診断等内容を扱っていますが、専門的な解剖学教育や臨床実習の代わりにはなりません。

## プロジェクト構成

```
systematic-anatomy-10edition/
├── SKILL.md                        # コアスキルレジストリ（ClawHub エントリポイント）
├── catalog.md                      # スキルインデックスとカテゴリナビゲーション
├── README.md                       # 本ファイル — プロジェクト概要と使用ガイド
├── README_EN.md                    # English Documentation
├── README_JP.md                    # 日本語ドキュメント
├── README_FR.md                    # Documentation en Français
├── README_RU.md                    # Документация на русском
├── <skill-name>/                   # 各スキルの詳細定義
│   └── SKILL.md                    #   スキル詳細（使用タイミング、手順、参考資料）
├── scripts/                        # 実行可能なユーティリティスクリプト
├── config/                         # 設定ファイル
├── tests/                          # 検証とテスト
└── assets/                         # 静的リソース（アイコン、画像等）
```

## スキルカテゴリ一覧

| カテゴリ | スキル数 | 説明 |
|----------|---------|------|
| 🦴 骨格と関節 | 14 | 骨分類、骨化機構、骨折評価、関節構造と安定性 |
| 🧠 神経系と脳・脊髄 | 22 | 脳機能局在、伝導路、脊髄、脳幹、脳室系 |
| 👤 頭頸部解剖 | 23 | 頭蓋骨、脳神経、眼・耳・鼻・咽喉、頸部筋と血管 |
| 💪 体幹と四肢 | 9 | 筋機能、神経支配、皮膚切開、鼠径部 |
| ❤️ 内臓系と臨床応用 | 20 | 心臓、血管、リンパ系、消化器、泌尿器、生殖器系 |
| 🔄 感覚と反射経路 | 5 | 感覚伝導、反射弓機構、関連痛の局在 |
| 🏥 中医解剖と特色分析 | 5 | 中西医結合、経絡関連解剖、特色ある整形外科的分析 |
| 📚 教科書と用語基準 | 9 | 教科書改訂原則、用語標準、執筆規範 |

## クイックスタート

### インストール

CLI：
```bash
openclaw skills install systematic-anatomy-10edition
```

プロンプト：
```bash
Before installing anything, inspect the ClawHub skill metadata and setup requirements.
If the skill asks you to install a third-party package or CLI, verify its source, maintainer, and package contents before running the install command.
Install the skill "Systematic Anatomy 10th Edition" (xllgreen/systematic-anatomy-10edition) from ClawHub only after those checks pass.
Skill page: https://clawhub.ai/xllgreen/systematic-anatomy-10edition
Keep the work scoped to this skill only.
After install, help me finish setup from verified skill metadata.
Use only the metadata you can verify from ClawHub; do not invent missing requirements.
Ask before making any broader environment changes.
```

### 使用方法

各スキルは以下の4つのセクションで構成されています：
1. **使用タイミング** — いつこのスキルを発動するか
2. **手順** — 標準化された解剖分析のワークフロー
3. **注意事項** — 解剖変異と臨床的警告
4. **参考資料** — 詳細な補足資料

### 質問例

#### 1. 概念の問い合わせ
```bash
内包の位置と区分
```
```bash
## 内包（Internal Capsule）
内包は尾状核、被殻（レンズ核）および背側視床の間にある白質板であり、水平断面では **「><」形** を呈する。

### 区分
| 区分 | 位置 | 通過する線維束 |
|------|------|---------------|
| **前脚** | 尾状核頭と被殻の間 | 前頭橋路、視床前放線 |
| **膝** | 前脚と後脚の屈曲部 | 皮質核路（皮質延髄路） |
| **後脚** | 被殻と背側視床の間 | 皮質脊髄路、視床中央放線、聴放線、視放線 |
...

### 臨床的意義
- **内包膝** 損傷 → 対側の舌筋および顔面下部の麻痺（核上性麻痺）
- **内包後脚** 損傷 → 対側片麻痺（皮質脊髄路）+ 対側半身感覚障害（視床中央放線）
```

#### 2. 臨床ケース分析
```bash
65歳男性、3時間前に突発する右側上下肢脱力と構語障害。身体所見：右上肢および右下肢筋力0級、右中枢性顔面神経麻痺、右半身の痛覚・温度覚低下、左への共同偏視。考えられる病変部位を分析せよ。
```
```bash
## 症例分析

| 項目 | 所見 |
|------|------|
| 年齢 | 65歳 → 脳卒中ハイリスク群 |
| 発症 | 突発（急性）→ 血管性 |
| 運動障害 | 右片麻痺（0級）+ 中枢性顔面麻痺 → 左皮質脊髄路 + 皮質核路 |
| 感覚障害 | 右半身の痛覚・温度覚低下 → 左視床中央放線 |
| 共同偏視 | 左への偏視 → 左前頭葉注視中枢（前頭眼野）または破壊性病変 |

### 局在診断
**左内包後脚病変**（最も可能性が高い）
- 皮質脊髄路と視床中央放線が同時に障害
- 典型的 **「三徴候群」** の不完全型（片麻痺 + 半身感覚障害）
- 内包病変は後脚の複数の線維束を同時に圧迫・障害しうる

### 鑑別診断 — 大脳皮質病変との違い
| 特徴 | 内包病変 | 大脳皮質病変 |
|------|---------|-------------|
| 片麻痺の分布 | 上下肢均等 | 上肢優位（またはその逆）の場合あり |
| 感覚障害 | 半身均等 | ある部位でより顕著な場合あり |
| 共同偏視 | 出現するとは限らない | 前頭葉注視中枢病変 → 病変側への偏視 |
| 失語 | なし | 優位半球病変で出現しうる |

### 緊急処置
1. 即時頭部CTで出血の除外
2. rt-PA血栓溶解療法の適応評価（発症3時間以内）
3. 気道確保、血圧・血糖モニタリング
4. 抗血小板薬、スタチン系薬剤
```

#### 3. 試験問題
```bash
内包に関する次の記述のうち、誤っているものはどれか：
A. 尾状核、被殻および背側視床の間に位置する
B. 膝部を皮質核路が通過する
C. 後脚を皮質脊髄路が通過する
D. 内包損傷は感覚障害を引き起こさない
```
```bash
**解答：D. 内包損傷は感覚障害を引き起こさない**

**解説：**
- A ✅ 正しい。内包は尾状核、被殻および背側視床の間にある白質板である
- B ✅ 正しい。内包膝は皮質核路（皮質延髄路）を含み、脳神経運動核を支配する
- C ✅ 正しい。内包後脚は皮質脊髄路を含み、体幹と四肢の随意運動を支配する
- D ❌ 誤り。内包後脚は**視床中央放線**も含み、全身の表在感覚と深部感覚を伝える。
  したがって、内包損傷は対側半身の感覚障害を引き起こしうる

**発展：** 内包完全損傷 → 典型的 **「三徴候群」**：
1. 対側片麻痺（皮質脊髄路）
2. 対側半身感覚障害（視床中央放線）
3. 対側同名半盲（視放線）
```

**その他の例：**
- 「視交叉の線維交叉様式と、部位別損傷における視野欠損パターンを分析せよ。」
- 「椎間板ヘルニアの解剖学的基盤と、根性神経痛との関係を説明せよ。」
- 「交感神経と副交感神経の起始、分布、機能における差異を比較せよ。」

## 参考教科書

人民衛生出版社『系統解剖学』第10版  
主任監修：丁文龍  
編集長：崔慧先、劉学政  
ISBN: 8E94C5A2-F115-4B45-Bc4A-D68Ac5D5Bf8C

## 著者について

**Xllgreen ([xllgreen.github.io](https://xllgreen.github.io))** — 九江学院臨床医学院の医学生 · テック愛好家

## テクニカルサポート

<br>
PDF2App プロジェクト：https://pdf2app.cn
<br>
Microsoft Visual Studio Code：https://code.visualstudio.com/
<br>
Claude Code for VS Code：https://claude.com/
<br>
© 2026 Anthropic PBC
<br>
<br>
<img src="https://cdn.deepseek.com/logo.png?x-image-process=image%2Fresize%2Cw_1920" width="130px">
<br>DeepSeek API：https://platform.deepseek.com/
<br>
<br>
<img src="https://cdn.cnbj1.fds.api.mi-img.com/aife/mimo-blog-fe/doc_build/static/image/logo.99baaffe.png" width="130px">
<br>Xiaomi Mimo API：https://platform.xiaomimimo.com/
Copyright © 2010 - 2026 Xiaomi. All Rights Reserved
<br>

## ライセンス

本プロジェクトの内容は、人民衛生出版社『系統解剖学』第10版に基づいて整理されたものであり、学習参考目的のみに提供されています。

MIT License

## Star History

<a href="https://www.star-history.com/?repos=xllgreen%2FSystematic-Anatomy-10edition&type=date&legend=top-left">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=xllgreen/Systematic-Anatomy-10edition&type=date&theme=dark&legend=top-left" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=xllgreen/Systematic-Anatomy-10edition&type=date&legend=top-left" />
   <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=xllgreen/Systematic-Anatomy-10edition&type=date&legend=top-left" />
 </picture>
</a>
