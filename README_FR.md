# Surgery-PMPH-10edition
<div align="center">

> *« Guide de l'étudiant en médecine du XXIe siècle »*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Skills](https://img.shields.io/badge/skills.sh-Compatible-green)](https://skills.sh)

<br>
> Un manuel de compétences cliniques basé sur *Chirurgie* (10e édition) de la People's Medical Publishing House — 240 compétences cliniques en chirurgie et soins intensifs
<br>
<br>
<img src="https://github.com/xllgreen/Surgery-PMPH-10edition-/blob/main/assets/Surgery.png" width="260px">
<br>

Pourquoi se fatiguer à lire un manuel entier ?<br>
Il suffit de poser une question et d'obtenir automatiquement la solution tirée du manuel

<br>

**Autres langues / Other Languages:**

[English](README_EN.md) · [日本語](README_JP.md) · [Français](README_FR.md) · [Русский](README_RU.md)

</div>

---

## À propos de ce projet

Ce projet intègre systématiquement les domaines fondamentaux de la chirurgie clinique, de la médecine d'urgence et des soins intensifs, de la gestion périopératoire, des soins traumatologiques, du traitement oncologique global, du contrôle des infections et du diagnostic/traitement des maladies multisystémiques, couvrant **240 compétences cliniques clés** réparties en 17 grandes catégories.

**Public cible** : Chirurgiens, médecins urgentistes, équipes de soins intensifs, étudiants en médecine

**Manuel de référence** : *Chirurgie* (10e édition), People's Medical Publishing House

## Structure du projet

```
Surgery-PMPH-10edition/
├── SKILL.md              # Registre central — index des 240 compétences
├── README.md             # Ce fichier — présentation et guide d'utilisation
├── <skill-name>/         # Définition détaillée de chaque compétence
│   └── SKILL.md          #   Détails de la compétence (indications, étapes, références)
├── scripts/              # Scripts utilitaires exécutables
│   ├── skill-search.sh   #   Recherche par mot-clé des compétences
│   └── skill-report.sh   #   Générateur d'inventaire des compétences
├── config/               # Fichiers de configuration
│   └── skill-config.yaml #   Configuration des catégories et métadonnées
└── tests/                # Validation et tests
    └── validate-all.sh   #   Script de vérification d'intégrité
```

## Aperçu des catégories de compétences

| Catégorie | Nb comp. | Description |
|-----------|----------|-------------|
| 🚑 Urgences & Réanimation | 14 | RCP, réanimation du choc, troubles électrolytiques |
| 🦴 Traumatologie & Fractures | 27 | Classification des fractures, réduction et fixation, lésions nerveuses |
| 🩺 Chirurgie générale & Urgences abdominales | 22 | Appendicite, occlusion intestinale, hernie, péritonite |
| 🫁 Chirurgie hépatobiliaire et pancréatique | 19 | Lithiase biliaire, pancréatite, traumatisme hépatique |
| 🩻 Chirurgie gastro-intestinale | 10 | Cancer gastrique, cancer colorectal, RGO |
| 🫘 Urologie | 24 | Lithiase, tumeurs, infections, lésions urétrales |
| 🩸 Chirurgie vasculaire | 7 | TVP, varices, réparation vasculaire |
| 🔥 Brûlures & Chirurgie plastique | 8 | Estimation de surface, classification de profondeur, greffe cutanée |
| 🧬 Oncologie chirurgicale & Soins globaux | 16 | Classification TNM, radiochimiothérapie, sauvetage de membre |
| 📋 Gestion périopératoire | 18 | Optimisation préopératoire, antibiotiques, soutien nutritionnel |
| 💉 Anesthésie & Douleur | 11 | Gestion des voies aériennes, rachianesthésie, anesthésie locale |
| ⚖️ Endocrinologie & Métabolisme | 6 | Hyperparathyroïdie, déshydratation, électrolytes |
| 🦠 Infection & Immunité | 7 | Tuberculose, sepsis, tétanos |
| 📡 Imagerie & Intervention | 10 | Angiographie, endoscopie, radiologie interventionnelle |
| 🏋️ Réadaptation & Évaluation fonctionnelle | 12 | Rééducation des fractures, évaluation neurologique |
| 🦿 Rhumatologie & Pathologies rachidiennes | 5 | Spondylarthrite ankylosante, sténose vertébrale |
| 🔧 Autres compétences spécialisées | 10 | SDRA, IRA, défibrillation, etc. |

## Guide de démarrage rapide

### Installation

CLI :
```bash
openclaw skills install surgery-pmph-10edition
```

Prompt :
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

### Recherche de compétences

```bash
# Recherche par mot-clé
bash scripts/skill-search.sh appendicite

# Générer un inventaire des compétences
bash scripts/skill-report.sh
```

### Utilisation

Chaque compétence comporte quatre sections :
1. **Indications** — Quand déclencher cette compétence
2. **Étapes** — Procédure opératoire standardisée
3. **Précautions** — Contre-indications et avertissements
4. **Références** — Documents complémentaires détaillés

## À propos de l'auteur

**xllgreen ([xllgreen.github.io](https://xllgreen.github.io))** — Étudiant en médecine à la Faculté de médecine clinique de l'Université de Jiujiang · Passionné de technologie

## Licence

Le contenu de ce projet est compilé d'après *Chirurgie* (10e édition) de la People's Medical Publishing House, fourni à titre de référence pédagogique uniquement.

## Star History

<a href="https://www.star-history.com/?repos=xllgreen%2FSurgery-PMPH-10edition-&type=date&legend=top-left">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=xllgreen/Surgery-PMPH-10edition-&type=date&theme=dark&legend=top-left" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=xllgreen/Surgery-PMPH-10edition-&type=date&legend=top-left" />
   <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=xllgreen/Surgery-PMPH-10edition-&type=date&legend=top-left" />
 </picture>
</a>
