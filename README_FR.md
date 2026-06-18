# Anatomie Systématique 10e édition

<div align="center">

> *« Le Guide de l'Étudiant en Médecine du XXIe Siècle »*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![ClawHub](https://img.shields.io/badge/ClawHub-Compatible-orange)](https://clawhub.ai)

<br>
> Un manuel de compétences en anatomie clinique basé sur *l'Anatomie Systématique* (10e édition, People's Medical Publishing House) — 112 Compétences Fondamentales en Anatomie
<br>
<br>
<img src="/assets/Systematic-Anatomy-10edition.jpg" width="260px">
<br>

Pourquoi peiner à lire tout un livre ?<br>
Posez simplement une question et trouvez la solution directement dans le manuel.

<br>

**其他语言 / Other Languages:**

[English](README_EN.md) · [日本語](README_JP.md) · [简体中文](README.md) · [Русский](README_RU.md)

</div>

---

## Présentation du Projet

Ce projet intègre de manière systématique les domaines fondamentaux de l'anatomie humaine, la neuroanatomie, l'anatomie clinique appliquée et l'analyse anatomique intégrée sino-occidentale, couvrant **112 compétences anatomiques clés** réparties en 8 grandes catégories.

**Public cible** : Étudiants en médecine, cliniciens, chercheurs en anatomie, internes en chirurgie

**Manuel de référence** : *Anatomie Systématique* (10e édition) — People's Medical Publishing House (Réviseur en chef : Ding Wenlong ; Rédacteurs en chef : Cui Huixian, Liu Xuezheng)

**⚠️ Avertissement ⚠️** : Ce recueil de compétences couvre les descriptions de la structure corporelle, l'analyse des variations anatomiques, l'évaluation des voies d'abord chirurgicales et le diagnostic topographique clinique. Il ne remplace pas un enseignement anatomique professionnel ni une formation clinique pratique.

## Structure du Projet

```
systematic-anatomy-10edition/
├── SKILL.md                        # Registre central des compétences (point d'entrée ClawHub)
├── catalog.md                      # Index des compétences et navigation par catégories
├── README.md                       # Ce fichier — présentation du projet et guide d'utilisation
├── README_EN.md                    # English Documentation
├── README_JP.md                    # 日本語ドキュメント
├── README_FR.md                    # Documentation en Français
├── README_RU.md                    # Документация на русском
├── <skill-name>/                   # Définitions détaillées de chaque compétence
│   └── SKILL.md                    #   Détails de la compétence (contexte d'utilisation, procédure, références)
├── scripts/                        # Scripts utilitaires exécutables
├── config/                         # Fichiers de configuration
├── tests/                          # Validation et tests
└── assets/                         # Ressources statiques (icônes, images, etc.)
```

## Aperçu des Catégories de Compétences

| Catégorie | Nb de compétences | Description |
|-----------|-------------------|-------------|
| 🦴 Os & Articulations | 14 | Classification osseuse, mécanismes d'ossification, évaluation des fractures, structure et stabilité articulaires |
| 🧠 Système Nerveux & Cerveau/Moelle épinière | 22 | Localisation fonctionnelle cérébrale, voies nerveuses, moelle épinière, tronc cérébral, système ventriculaire |
| 👤 Anatomie de la Tête et du Cou | 23 | Crâne, nerfs crâniens, œil/oreille/nez/gorge, muscles et vaisseaux du cou |
| 💪 Tronc & Membres | 9 | Fonction musculaire, innervation, incisions cutanées, région inguinale |
| ❤️ Systèmes Viscéraux & Application Clinique | 20 | Cœur, vaisseaux, lymphatiques, systèmes digestif, urinaire et reproducteur |
| 🔄 Voies Sensorielles & Réflexes | 5 | Transmission sensorielle, mécanismes de l'arc réflexe, localisation de la douleur projetée |
| 🏥 Anatomie en Médecine Chinoise & Analyse Spécialisée | 5 | Médecine intégrée sino-occidentale, anatomie des méridiens, analyse orthopédique spécialisée |
| 📚 Normes de Manuel & Terminologie | 9 | Principes de révision des manuels, normes terminologiques, directives de rédaction |

## Guide de Démarrage Rapide

### Installation

CLI :
```bash
openclaw skills install systematic-anatomy-10edition
```

Invite :
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

### Utilisation

Chaque compétence comporte quatre sections :
1. **Quand l'utiliser** — Quand déclencher cette compétence
2. **Procédure** — Processus d'analyse anatomique standardisé
3. **Précautions** — Variations anatomiques et alertes cliniques
4. **Références** — Documents complémentaires détaillés

### Utilisation après installation
Il faut indiquer ce qui suit à l'agent :
```bash
Avant de répondre, veuillez d'abord vérifier la compétence médicale correspondante pour confirmer.
```

### Recherche de compétences

```bash
# Recherche par mot-clé
bash scripts/skill-search.sh appendicite

# Générer la liste des compétences
bash scripts/skill-report.sh
```

### Exemples de Requêtes

#### 1. Interrogation de Concept
```bash
Position et divisions de la capsule interne
```
```bash
## Capsule Interne (Internal Capsule)
La capsule interne est une lame de substance blanche située entre le noyau caudé, le noyau lenticulaire et le thalamus dorsal. Elle a une forme de **« >< »** en coupe horizontale.

### Divisions
| Division | Position | Faisceaux qui la traversent |
|----------|----------|------------------------------|
| **Bras antérieur** | Entre la tête du noyau caudé et le noyau lenticulaire | Faisceau fronto-pontique, radiation thalamique antérieure |
| **Genou** | Le coude entre les bras antérieur et postérieur | Faisceau corticobulbaire (cortico-nucléaire) |
| **Bras postérieur** | Entre le noyau lenticulaire et le thalamus dorsal | Faisceau corticospinal, radiation thalamique centrale, radiation auditive, radiation optique |
...

### Signification Clinique
- **Lésion du genou de la capsule interne** → Paralysie contro-latérale de la langue et des muscles faciaux inférieurs (paralysie supranucléaire)
- **Lésion du bras postérieur** → Hémiplégie contro-latérale (faisceau corticospinal) + hémianesthésie contro-latérale (radiation thalamique centrale)
```

#### 2. Analyse de Cas Clinique
```bash
Homme de 65 ans, faiblesse brutale du côté droit et troubles de la parole depuis 3 heures. Examen : force musculaire du membre supérieur et inférieur droit à 0, paralysie faciale centrale droite, diminution de la sensibilité douloureuse et thermique à droite, déviation du regard vers la gauche. Analysez la localisation lésionnelle probable.
```
```bash
## Analyse du Cas

| Paramètre | Présentation |
|-----------|-------------|
| Âge | 65 ans → haut risque d'AVC |
| Début | Brutal (aigu) → étiologie vasculaire |
| Déficits moteurs | Hémiplégie droite (0) + paralysie faciale centrale → faisceau corticospinal + corticobulbaire gauche |
| Déficits sensitifs | Diminution de la sensibilité douloureuse et thermique droite → radiation thalamique centrale gauche |
| Regard | Déviation vers la gauche → centre du regard frontal gauche (champ oculaire frontal) ou lésion destructrice |

### Diagnostic Topographique
**Lésion du bras postérieur de la capsule interne gauche** (la plus probable)
- Atteinte simultanée du faisceau corticospinal et de la radiation thalamique centrale
- Forme incomplète du **syndrome « trois hémis »** classique (hémiplégie + hémianesthésie)
- Les lésions de la capsule interne peuvent comprimer ou affecter plusieurs faisceaux du bras postérieur

### Diagnostic Différentiel — Lésion Corticale vs Lésion de la Capsule Interne
| Caractéristique | Lésion de la Capsule Interne | Lésion du Cortex Cérébral |
|-----------------|------------------------------|---------------------------|
| Distribution de l'hémiplégie | Égale aux membres supérieur et inférieur | Peut prédominer au membre supérieur (ou inversement) |
| Perte sensitive | Égale sur tout l'hémicorps | Peut être plus prononcée dans une zone |
| Déviation du regard | Peut ou non apparaître | Lésion du centre frontal du regard → déviation vers le côté lésé |
| Aphasie | Absente | Possible en cas de lésion de l'hémisphère dominant |

### Prise en Charge Urgente
1. Scanner cérébral immédiat pour exclure une hémorragie
2. Évaluation de l'éligibilité à la thrombolyse par rt-PA (dans les 3 heures suivant le début)
3. Maintien de la perméabilité des voies aériennes, surveillance de la pression artérielle et de la glycémie
4. Traitement antiplaquettaire, statines
```

#### 3. Questions d'Examen
```bash
Parmi les affirmations suivantes concernant la capsule interne, laquelle est INCORRECTE ?
A. Située entre le noyau caudé, le noyau lenticulaire et le thalamus dorsal
B. Le genou contient le faisceau corticobulbaire
C. Le bras postérieur contient le faisceau corticospinal
D. Une lésion de la capsule interne n'entraîne pas de déficit sensitif
```
```bash
**Réponse : D. Une lésion de la capsule interne n'entraîne pas de déficit sensitif**

**Explication :**
- A ✅ Correct. La capsule interne est une lame de substance blanche entre le noyau caudé, le noyau lenticulaire et le thalamus dorsal
- B ✅ Correct. Le genou de la capsule interne contient le faisceau corticobulbaire, qui innerve les noyaux moteurs des nerfs crâniens
- C ✅ Correct. Le bras postérieur contient le faisceau corticospinal, qui contrôle le mouvement volontaire du tronc et des membres
- D ❌ Incorrect. Le bras postérieur contient également la **radiation thalamique centrale**, qui transmet les sensations superficielles et profondes de tout le corps. Par conséquent, une lésion de la capsule interne peut entraîner une hémianesthésie contro-latérale

**Pour aller plus loin :** Lésion complète de la capsule interne → **syndrome « trois hémis »** classique :
1. Hémiplégie contro-latérale (faisceau corticospinal)
2. Hémianesthésie contro-latérale (radiation thalamique centrale)
3. Hémianopsie latérale homonyme contro-latérale (radiation optique)
```

**Autres exemples :**
- "Analysez le schéma de croisement des fibres du chiasma optique et les types de déficits du champ visuel associés aux lésions à différents niveaux."
- "Expliquez les bases anatomiques de la hernie discale et sa relation avec la douleur radiculaire."
- "Comparez les systèmes sympathique et parasympathique en termes d'origine, de distribution et de fonction."

## Manuel de Référence

*Anatomie Systématique* (10e édition) — People's Medical Publishing House  
Réviseur en chef : Ding Wenlong  
Rédacteurs en chef : Cui Huixian, Liu Xuezheng  
ISBN : 8E94C5A2-F115-4B45-Bc4A-D68Ac5D5Bf8C

## À Propos de l'Auteur

**Xllgreen ([xllgreen.github.io](https://xllgreen.github.io))** — Étudiant en médecine à l'École de Médecine Clinique de l'Université de Jiujiang · Passionné de technologie

## Support Technique

<br>
Projet PDF2App : https://pdf2app.cn
<br>
Microsoft Visual Studio Code : https://code.visualstudio.com/
<br>
Claude Code for VS Code : https://claude.com/
<br>
© 2026 Anthropic PBC
<br>
<br>
<img src="https://cdn.deepseek.com/logo.png?x-image-process=image%2Fresize%2Cw_1920" width="130px">
<br>API DeepSeek : https://platform.deepseek.com/
<br>
<br>
<img src="https://cdn.cnbj1.fds.api.mi-img.com/aife/mimo-blog-fe/doc_build/static/image/logo.99baaffe.png" width="130px">
<br>API Xiaomi Mimo : https://platform.xiaomimimo.com/
Copyright © 2010 - 2026 Xiaomi. All Rights Reserved
<br>

## Licence

Ce projet est compilé à partir de *l'Anatomie Systématique* (10e édition) de People's Medical Publishing House à des fins d'apprentissage uniquement.

MIT License

## Star History

<a href="https://www.star-history.com/?repos=xllgreen%2FSystematic-Anatomy-10edition&type=date&legend=top-left">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=xllgreen/Systematic-Anatomy-10edition&type=date&theme=dark&legend=top-left" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=xllgreen/Systematic-Anatomy-10edition&type=date&legend=top-left" />
   <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=xllgreen/Systematic-Anatomy-10edition&type=date&legend=top-left" />
 </picture>
</a>
