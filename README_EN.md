# Surgery-PMPH-10edition
<div align="center">

> *「21st Century Medical Student Guide」*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Skills](https://img.shields.io/badge/skills.sh-Compatible-green)](https://skills.sh)

<br>
> A clinical skills handbook based on *Surgery* (10th Edition) by People's Medical Publishing House — 240 surgical & critical care clinical skills
<br>
<br>
<img src="https://github.com/xllgreen/Surgery-PMPH-10edition-/blob/main/assets/Surgery.png" width="260px">
<br>

Why slog through a whole textbook?<br>
Just ask a question and get the solution directly from the source.

<br>

**其他语言 / Other Languages:**

[English](README_EN.md) · [日本語](README_JP.md) · [Français](README_FR.md) · [Русский](README_RU.md)

</div>

---

## About This Project

This project systematically integrates core domains including clinical surgery, emergency & critical care medicine, perioperative management, trauma care, comprehensive cancer treatment, infection control, and multi-system disease diagnosis & treatment, covering **240 key clinical skills** across 17 major categories.

**Target Audience**: Surgeons, emergency physicians, ICU teams, medical students

**Reference Textbook**: *Surgery* (10th Edition), People's Medical Publishing House

## Project Structure

```
Surgery-PMPH-10edition/
├── SKILL.md              # Core registry — 240 skills index
├── README.md             # This file — project overview & usage guide
├── <skill-name>/         # Detailed definition for each skill
│   └── SKILL.md          #   Skill details (indications, steps, references)
├── scripts/              # Executable utility scripts
│   ├── skill-search.sh   #   Keyword search for skills
│   └── skill-report.sh   #   Skill inventory report generator
├── config/               # Configuration files
│   └── skill-config.yaml #   Skill categorization & metadata config
└── tests/                # Validation & testing
    └── validate-all.sh   #   Integrity check script
```

## Skill Categories at a Glance

| Category | Skills | Description |
|----------|--------|-------------|
| 🚑 Emergency & Resuscitation | 14 | CPR, shock resuscitation, electrolyte disorders |
| 🦴 Trauma & Fractures | 27 | Fracture classification, reduction & fixation, nerve injury |
| 🩺 General Surgery & Abdominal Emergencies | 22 | Appendicitis, bowel obstruction, hernia, peritonitis |
| 🫁 Hepatobiliary & Pancreatic Surgery | 19 | Biliary stones, pancreatitis, liver trauma |
| 🩻 Gastrointestinal Surgery | 10 | Gastric cancer, colorectal cancer, GERD |
| 🫘 Urology | 24 | Stones, tumors, infections, urethral injury |
| 🩸 Vascular Surgery | 7 | DVT, varicose veins, vascular repair |
| 🔥 Burns & Plastic Surgery | 8 | Area estimation, depth classification, skin grafting |
| 🧬 Surgical Oncology & Comprehensive Care | 16 | TNM staging, chemoradiation, limb salvage |
| 📋 Perioperative Management | 18 | Preoperative optimization, antibiotics, nutritional support |
| 💉 Anesthesia & Pain | 11 | Airway management, spinal anesthesia, local anesthesia |
| ⚖️ Endocrine & Metabolism | 6 | Hyperparathyroidism, dehydration, electrolytes |
| 🦠 Infection & Immunity | 7 | Tuberculosis, sepsis, tetanus |
| 📡 Imaging & Intervention | 10 | Angiography, endoscopy, interventional radiology |
| 🏋️ Rehabilitation & Functional Assessment | 12 | Fracture rehabilitation, neurological assessment |
| 🦿 Rheumatology & Spinal Disorders | 5 | Ankylosing spondylitis, spinal stenosis |
| 🔧 Other Specialty Skills | 10 | ARDS, AKI, defibrillation, etc. |

## Quick Start

### Installation

CLI:
```bash
openclaw skills install surgery-pmph-10edition
```

Prompt:
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

### Searching Skills

```bash
# Search by keyword
bash scripts/skill-search.sh appendicitis

# Generate skill inventory report
bash scripts/skill-report.sh
```

### Usage

Each skill contains four sections:
1. **Indications** — When to trigger this skill
2. **Steps** — Standardized operating procedure
3. **Precautions** — Contraindications & warnings
4. **References** — Detailed supplementary materials

## About the Author

**xllgreen ([xllgreen.github.io](https://xllgreen.github.io))** — Medical student at Jiujiang University School of Clinical Medicine · Tech geek

## License

This project is compiled based on *Surgery* (10th Edition) by People's Medical Publishing House, for learning reference only.

## Star History

<a href="https://www.star-history.com/?repos=xllgreen%2FSurgery-PMPH-10edition-&type=date&legend=top-left">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=xllgreen/Surgery-PMPH-10edition-&type=date&theme=dark&legend=top-left" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=xllgreen/Surgery-PMPH-10edition-&type=date&legend=top-left" />
   <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=xllgreen/Surgery-PMPH-10edition-&type=date&legend=top-left" />
 </picture>
</a>
