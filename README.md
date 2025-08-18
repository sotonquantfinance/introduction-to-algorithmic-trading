<p align="center">
  <img src="assets/sqfs-banner.png" alt="Southampton Quantitative Finance Society banner" width="100%" />
</p>

<h1 align="center">📘 Introduction to Algorithmic Trading</h1>
<h3 align="center">Southampton Quantitative Finance Society — Workshop Series</h3>

<p align="center">
  <img src="assets/sqfs-logo.png" alt="SQFS Logo" height="90" />
</p>

<p align="center">
  <a href="#-quickstart">
    <img alt="Launch" src="https://img.shields.io/badge/run-jupyter-1F2937?style=for-the-badge">
  </a>
  <a href="https://github.com/<YOU>/introduction-to-algorithmi-trading/blob/main/LICENSE">
    <img alt="License" src="https://img.shields.io/badge/license-MIT-FFC857?style=for-the-badge">
  </a>
  <a href="https://github.com/<YOU>/introduction-to-algorithmi-trading/actions">
    <img alt="Build" src="https://img.shields.io/badge/build-ready-0B3D91?style=for-the-badge">
  </a>
</p>

---

Welcome to the official repository for our <b>Introduction to Algorithmic Trading</b> workshop.
This repo contains hands-on <b>Jupyter Notebooks</b> that guide you through core quant finance strategies.

> 💡 <i>For students, by students.</i> Educational use only — not financial advice.

---

## 🎯 Workshop Aims
By the end of this series, you will:
- Understand the concept of <b>mean reversion</b> and its application in trading.
- Build and backtest a simple <b>z-score mean reversion strategy</b>.
- Explore <b>pairs trading</b> using cointegration and spread z-scores.
- Gain confidence working with <b>Python, pandas, and Jupyter</b> for finance.

---

## 📂 Repository Structure
```
notebooks/
 ├─ 01_mean_reversion.ipynb   # z-score, rolling stats, simple backtest
 ├─ 02_pairs_trading.ipynb    # cointegration, spread, beta-neutral strategy
 └─ 99_society_intro.ipynb    # workshop overview, aims, and notes

requirements.txt              # Python dependencies
README.md                     # You are here
.gitignore                    # Ignore venvs, checkpoints, OS files
```

---

## ⚡ Quickstart
```bash
python -m venv .venv
# macOS/Linux
source .venv/bin/activate
# Windows
.venv\Scripts\activate

pip install -r requirements.txt
jupyter lab   # or: jupyter notebook
```

---

## 🗂 Notebooks
- <b>01_mean_reversion</b> — z-scores, rolling stats, simple backtest  
- <b>02_pairs_trading</b> — cointegration test, spread z-score, beta-neutral strategy  
- <b>99_society_intro</b> — workshop overview + logistics

---

## 🧭 About Southampton QFS
Southampton <b>Quantitative Finance Society</b> explores quant research, algorithmic trading, and data science in markets.
We run <b>workshops, talks, and collaborative projects</b>. Join us and build with peers.

<p align="center">
  <a href="https://<your_site_or_linktree>">🌐 Website</a> •
  <a href="mailto:<contact_email>">✉️ Contact</a> •
  <a href="https://www.linkedin.com/company/<your_page>">LinkedIn</a>
</p>

---

### Branding Notes
Place your assets here for the images above to render:

```
assets/
  sqfs-logo.png
  sqfs-banner.png
```
