# Systematic Anatomy 10th Edition

<div align="center">

> *「A 21st Century Medical Student's Guide」*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![ClawHub](https://img.shields.io/badge/ClawHub-Compatible-orange)](https://clawhub.ai)

<br>
> A clinical anatomy skills handbook based on *Systematic Anatomy* (10th Edition, People's Medical Publishing House) — 112 Core Anatomy Skills
<br>
<br>
<img src="/assets/Systematic-Anatomy-10edition.jpg" width="260px">
<br>

Why struggle through an entire book?<br>
Just ask a question and get solutions directly from the textbook.

<br>

**其他语言 / Other Languages:**

[简体中文](README.md) · [日本語](README_JP.md) · [Français](README_FR.md) · [Русский](README_RU.md)

</div>

---

## Project Overview

This project systematically integrates core domains including human anatomy, neuroanatomy, clinical applied anatomy, and integrated Chinese-Western anatomical analysis, covering **112 key anatomy skills** across 8 major categories.

**Target Audience**: Medical students, clinical physicians, anatomy researchers, surgical residents

**Reference Textbook**: *Systematic Anatomy* (10th Edition) by People's Medical Publishing House (Chief Reviewer: Ding Wenlong; Editors-in-Chief: Cui Huixian, Liu Xuezheng)

**⚠️ Disclaimer ⚠️**: This skill set covers human structure descriptions, anatomical variation analysis, surgical approach evaluation, and clinical localization diagnosis. It is not a substitute for professional anatomy instruction or clinical practice.

## Project Structure

```
systematic-anatomy-10edition/
├── SKILL.md                        # Core skill registry (ClawHub entry point)
├── catalog.md                      # Skill index and category navigation
├── README.md                       # This file — project overview and usage guide
├── README_EN.md                    # English Documentation
├── README_JP.md                    # 日本語ドキュメント
├── README_FR.md                    # Documentation en Français
├── README_RU.md                    # Документация на русском
├── <skill-name>/                   # Detailed definitions for each skill
│   └── SKILL.md                    #   Skill details (usage context, steps, references)
├── scripts/                        # Executable utility scripts
├── config/                         # Configuration files
├── tests/                          # Validation and testing
└── assets/                         # Static resources (icons, images, etc.)
```

## Skill Categories at a Glance

| Category | Skills | Description |
|----------|--------|-------------|
| 🦴 Bones & Joints | 14 | Bone classification, ossification mechanisms, fracture assessment, joint structure & stability |
| 🧠 Nervous System & Brain/Spinal Cord | 22 | Brain functional localization, neural pathways, spinal cord, brainstem, ventricular system |
| 👤 Head & Neck Anatomy | 23 | Skull, cranial nerves, eye/ear/nose/throat, neck muscles & vessels |
| 💪 Trunk & Limbs | 9 | Muscle function, innervation, skin incisions, inguinal region |
| ❤️ Visceral Systems & Clinical Application | 20 | Heart, vessels, lymphatics, digestive, urinary, reproductive systems |
| 🔄 Sensory & Reflex Pathways | 5 | Sensory transmission, reflex arc mechanisms, referred pain localization |
| 🏥 Chinese Medicine Anatomy & Specialty Analysis | 5 | Integrated Chinese-Western medicine, meridian-related anatomy, specialized orthopedic analysis |
| 📚 Textbook & Terminology Standards | 9 | Textbook revision principles, terminology standards, authoring guidelines |

## Quick Start

### Installation

CLI:
```bash
openclaw skills install systematic-anatomy-10edition
```

Prompt:
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

### Usage

Each skill contains four sections:
1. **When to Use** — When to trigger this skill
2. **Procedure** — Standardized anatomical analysis workflow
3. **Cautions** — Anatomical variations and clinical warnings
4. **References** — Detailed supplementary materials

### Usage After Installation
Instruct the agent with the following:
```bash
Before answering, please first check the corresponding medical skill to confirm.
```

### Finding Skills

```bash
# Search by keyword
bash scripts/skill-search.sh appendicitis

# Generate skill list
bash scripts/skill-report.sh
```

### Example Queries

#### 1. Concept Query
```bash
Location and divisions of the internal capsule
```
```bash
## Internal Capsule
The internal capsule is a white matter plate located between the caudate nucleus, lentiform nucleus, and dorsal thalamus. It appears **「><」-shaped** in horizontal section.

### Divisions
| Division | Location | Tracts Passing Through |
|----------|----------|------------------------|
| **Anterior limb** | Between the head of the caudate nucleus and the lentiform nucleus | Frontopontine fibers, anterior thalamic radiation |
| **Genu** | The bend between the anterior and posterior limbs | Corticobulbar tract |
| **Posterior limb** | Between the lentiform nucleus and the dorsal thalamus | Corticospinal tract, central thalamic radiation, auditory radiation, optic radiation |
...

### Clinical Significance
- **Genu of internal capsule** injury → Contralateral paralysis of tongue and lower facial muscles (supranuclear palsy)
- **Posterior limb** injury → Contralateral hemiplegia (corticospinal tract) + contralateral hemisensory loss (central thalamic radiation)
```

#### 2. Clinical Case Analysis
```bash
A 65-year-old male patient presents with sudden right-sided limb weakness and speech difficulties for 3 hours. Physical exam: right upper and lower limb muscle strength grade 0, right central facial paralysis, decreased pain and temperature sensation on the right side, gaze preference to the left. Please analyze the possible lesion location.
```
```bash
## Case Analysis

| Parameter | Presentation |
|-----------|-------------|
| Age | 65 years → high risk for stroke |
| Onset | Sudden (acute) → vascular etiology |
| Motor deficits | Right hemiplegia (grade 0) + central facial paralysis → left corticospinal tract + corticobulbar tract |
| Sensory deficits | Right-sided decreased pain and temperature sensation → left central thalamic radiation |
| Gaze | Gaze preference to the left → left frontal gaze center (frontal eye field) or destructive lesion |

### Localization Diagnosis
**Left posterior limb of internal capsule lesion** (most likely)
- Corticospinal tract and central thalamic radiation involved simultaneously
- Incomplete form of the classic **"three hemis" syndrome** (hemiplegia + hemisensory loss)
- Internal capsule lesions may compress or affect multiple fiber tracts in the posterior limb

### Differential Diagnosis — Cortical Lesion vs. Internal Capsule Lesion
| Feature | Internal Capsule Lesion | Cerebral Cortex Lesion |
|---------|------------------------|------------------------|
| Hemiplegia distribution | Equal in upper and lower limbs | May be worse in upper limb (or vice versa) |
| Sensory loss | Equal across the hemibody | May be more pronounced in one area |
| Gaze preference | May or may not appear | Frontal gaze center lesion → gaze preference toward the lesion side |
| Aphasia | Absent | May occur in dominant hemisphere lesions |

### Emergency Management
1. Immediate head CT to rule out hemorrhage
2. Assess eligibility for rt-PA thrombolysis (within 3 hours of onset)
3. Maintain airway patency, monitor blood pressure and blood glucose
4. Antiplatelet therapy, statins
```

#### 3. Exam Questions
```bash
Which of the following statements about the internal capsule is INCORRECT?
A. Located between the caudate nucleus, lentiform nucleus, and dorsal thalamus
B. The genu contains the corticobulbar tract
C. The posterior limb contains the corticospinal tract
D. Internal capsule injury does not cause sensory deficits
```
```bash
**Answer: D. Internal capsule injury does not cause sensory deficits**

**Explanation:**
- A ✅ Correct. The internal capsule is a white matter plate between the caudate nucleus, lentiform nucleus, and dorsal thalamus
- B ✅ Correct. The genu of the internal capsule contains the corticobulbar tract, which innervates brainstem motor nuclei
- C ✅ Correct. The posterior limb contains the corticospinal tract, which controls voluntary movement of the trunk and limbs
- D ❌ Incorrect. The posterior limb also contains the **central thalamic radiation**, which transmits both superficial and deep sensation from the entire body. Therefore, internal capsule injury can cause contralateral hemisensory loss

**Further Reading:** Complete internal capsule injury → classic **"three hemis" syndrome**:
1. Contralateral hemiplegia (corticospinal tract)
2. Contralateral hemisensory loss (central thalamic radiation)
3. Contralateral homonymous hemianopia (optic radiation)
```

**More Examples:**
- "Analyze the fiber crossing pattern of the optic chiasm and the visual field defect patterns associated with lesions at different locations."
- "Explain the anatomical basis of intervertebral disc herniation and its relationship with radicular pain."
- "Compare the sympathetic and parasympathetic nervous systems in terms of origin, distribution, and function."

## Reference Textbook

*Systematic Anatomy* (10th Edition) — People's Medical Publishing House  
Chief Reviewer: Ding Wenlong  
Editors-in-Chief: Cui Huixian, Liu Xuezheng  
ISBN: 8E94C5A2-F115-4B45-Bc4A-D68Ac5D5Bf8C

## About the Author

**Xllgreen ([xllgreen.github.io](https://xllgreen.github.io))** — Medical student at Jiujiang University School of Clinical Medicine · Tech enthusiast

## Technical Support

<br>
PDF2App Project: https://pdf2app.cn
<br>
Microsoft Visual Studio Code: https://code.visualstudio.com/
<br>
Claude Code for VS Code: https://claude.com/
<br>
© 2026 Anthropic PBC
<br>
<br>
<img src="https://cdn.deepseek.com/logo.png?x-image-process=image%2Fresize%2Cw_1920" width="130px">
<br>DeepSeek API: https://platform.deepseek.com/
<br>
<br>
<img src="https://cdn.cnbj1.fds.api.mi-img.com/aife/mimo-blog-fe/doc_build/static/image/logo.99baaffe.png" width="130px">
<br>Xiaomi Mimo API: https://platform.xiaomimimo.com/
Copyright © 2010 - 2026 Xiaomi. All Rights Reserved
<br>

## License

This project is compiled based on *Systematic Anatomy* (10th Edition) by People's Medical Publishing House for learning reference purposes only.

MIT License

## Star History

<a href="https://www.star-history.com/?repos=xllgreen%2FSystematic-Anatomy-10edition&type=date&legend=top-left">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=xllgreen/Systematic-Anatomy-10edition&type=date&theme=dark&legend=top-left" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=xllgreen/Systematic-Anatomy-10edition&type=date&legend=top-left" />
   <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=xllgreen/Systematic-Anatomy-10edition&type=date&legend=top-left" />
 </picture>
</a>
