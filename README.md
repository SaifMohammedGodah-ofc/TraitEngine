# 🧩 TraitEngine

> **Layer-based NFT Generator** — Create unique collections with full rarity control, no limits, and zero paywalls.

![TraitEngine Banner](images/banner.png)

---

## 🚀 Overview

**TraitEngine** is a fully customizable NFT generation system built for creators, developers, and studios.  
It combines **layer-based image compositing**, **rarity weighting**, and **metadata export** — all in a clean, offline Python app.

Whether you’re building a small art drop or a full generative collection, TraitEngine gives you total control without ads, cloud limits, or subscriptions.

---

## ✨ Features

- 🎨 **Layer System:** Add multiple layers and upload transparent PNGs for each trait.  
- ⚖️ **Rarity Control:** Assign custom weights (%) to each item.  
- 🔢 **Unique Generation:** Automatically avoids duplicate combinations.  
- 🧮 **Max-Combinations Display:** Live calculation of total unique possible NFTs.  
- 💾 **Metadata Export:** Generates JSON metadata files compatible with ERC-721 and IPFS.  
- 🧠 **Smart Provenance:** Produces a `_provenance.json` file with trait + image hashes.  
- 🧰 **Save/Load Projects:** Keep your collection setup in a `.json` project file.  
- 🖼️ **Preview System:** Instantly preview the current layer combination before generation.  
- 💻 **No Cloud Needed:** 100% local — no ads, no API calls, no internet required.

---

## 🧠 Tech Stack

| Component | Library |
|------------|----------|
| Core Image Engine | [Pillow (PIL)](https://python-pillow.org/) |
| GUI (Option A) | [PySide6 (Qt for Python)](https://doc.qt.io/qtforpython/) |
| GUI (Option B) | [Tkinter](https://docs.python.org/3/library/tkinter.html) *(built-in)* |
| Metadata & Logic | `json`, `hashlib`, `os`, `random`, `dataclasses` *(standard libs)* |

---

## ⚙️ Installation

Clone this repo:
```bash
git clone https://github.com/<your-username>/TraitEngine.git
cd TraitEngine
