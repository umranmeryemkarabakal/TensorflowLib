# TensorflowLib

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter" />
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" alt="TensorFlow" />
  <img src="https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white" alt="Keras" />
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" alt="scikit-learn" />
</p>

## 🇬🇧 Overview

Three TensorFlow/Keras notebooks: price regression on a bicycle dataset (model saved as `.keras` and `.h5`), car price regression on the Mercedes dataset, and an overfitting study on a malicious website classification dataset.

**Quick start:** `jupyter notebook`

## 🇹🇷 Proje hakkında

TensorFlow/Keras ile üç uygulama defteri.

## 📚 İçerik

- `01`: bisiklet fiyatı regresyonu, Keras + scikit-learn; model `bisiklet_modeli.keras` olarak kaydedilir
- `02`: Mercedes araç fiyatı regresyonu (`merc.xlsx`)
- `03`: kötü amaçlı site sınıflandırmasında aşırı öğrenme ve önlemleri (`maliciousornot.xlsx`)

## ⚙️ Kurulum ve çalıştırma

```bash
python -m venv .venv
source .venv/bin/activate        # Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

```bash
jupyter notebook
```

## 📁 Dosya yapısı

```text
TensorflowLib/
├── 01-regresyon_keras_sklearn.ipynb
├── 02-tensorflowExample.ipynb
├── 03-overfitingExample.ipynb
├── bisiklet_fiyatlari.xlsx
├── bisiklet_modeli.h5
├── bisiklet_modeli.keras
├── maliciousornot.xlsx
└── merc.xlsx
```
