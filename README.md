# AI-Generated Advertising Visuals Brand Safety & Distortion Guard

> Prevent embarrassing AI image blunders on ad campaigns. 25-point visual QA audit rubric and vetted negative prompt library.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Format: TEMPLATE_FRAMEWORK](https://img.shields.io/badge/Format-TEMPLATE--FRAMEWORK-green.svg)](#)
[![Tier: 1](https://img.shields.io/badge/Tier-1-orange.svg)](#)
[![Region: MENA](https://img.shields.io/badge/Region-Egypt%20%7C%20GCC%20%7C%20Saudi-purple.svg)](#)
[![Tests: Passing](https://img.shields.io/badge/Tests-Passing-brightgreen.svg)](#)
[![Owner: mahmoudabdelnaby1](https://img.shields.io/badge/Owner-mahmoudabdelnaby1-blue.svg)](https://github.com/mahmoudabdelnaby1)

---

## 📌 Problem Statement & Target Persona

### Target Persona
**PRO** operating in high-growth e-commerce, digital publishing, and direct-response marketing across Saudi Arabia, UAE, and Egypt.

### Core Problem
Create an enterprise quality control framework for AI-generated marketing imagery: 1) 25-point visual artifact checklist (Anatomy, Text & Logos, Lighting Consistency, Cultural Appropriateness for MENA), 2) Curated negative prompt library for Midjourney and Flux, 3) Real-world defect gallery with failure analysis, 4) Sign-off workflow template for agency art directors.

---

## 🛠️ Repository Architecture & Deliverables

This repository provides self-contained, documented implementations and specifications:

- `checklists/25-point-ai-visual-qa.md`
- `examples/saudi-logistics-case-study.md`
- `gallery/defect_examples.md`
- `guidelines/mena-cultural-visual-standards.md`
- `LICENSE`
- `playbooks/mena-client-approval-sop.md`
- `prompts/negative-prompt-library.json`
- `README.md`
- `templates/art-director-signoff.md`
- `templates/case-study-interview-guide.md`
- `templates/one-pager-slide-template.md`
- `tests/test_data_integrity.py`


---

## 🚀 Quick Start & How to Run Locally

### Run Test Suite Locally
```bash
# Ensure no bytecode generation
export PYTHONDONTWRITEBYTECODE=1  # Linux / macOS
$env:PYTHONDONTWRITEBYTECODE="1"  # Windows PowerShell

# Run Python unittest discovery
python -m unittest discover -s tests
```

---

## 📊 Sample Input & Output Fixtures

> **Data Disclosure:** Any included sample data is illustrative and may be synthetic; it is not a measured customer result or market benchmark unless a source and collection method are stated alongside it. These files run offline with standard libraries and require no paid third-party API credentials.

```json
{
  "domain": "content",
  "repository": "ai-ad-visual-brand-safety-guard",
  "status": "READY_FOR_LOCAL_REVIEW",
  "license": "MIT"
}
```

---

## ⚠️ Known Technical & Domain Constraints

- **Synthetic Visual Artifacts:** Screens AI-generated ad imagery for common generative distortions (mangled hands, warped text, unnatural symmetry).
- **GCC Modesty & Visual Decency:** Audits visual assets against regional advertising modesty standards to prevent ad rejection under GAMR guidelines.
- **Mobile Viewport Clarity:** Verifies that product focal points remain clear and un-cropped across 1:1, 4:5, and 9:16 mobile aspect ratios.

---

## 📚 Primary Documentation & Verifiable References

- [Saudi General Authority for Media Regulation (GAMR): Visual Standards](https://gcam.gov.sa/) - Statutory regulations governing commercial media visual decency and truth in advertising.
- [Meta Advertising Standards: Creative Quality & Brand Safety](https://transparency.fb.com/policies/ad-standards/) - Platform-level quality thresholds prohibiting deceptive imagery and low-quality visuals.
- [IEEE Standards: Synthetic Media & AI Visual Quality](https://www.ieee.org/) - Foundational engineering frameworks for assessing computer vision and synthetic artifacts.

---


## 👤 Maintainer & License

- **Author & Maintainer:** [Mahmoud Abdelnaby](https://github.com/mahmoudabdelnaby1) (`@mahmoudabdelnaby1`)
- **License:** [MIT License](LICENSE) - Open-source, auditable, and freely adaptable for internal enterprise or commercial use.
