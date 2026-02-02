# 🚨 FCMOH 
### The First Comprehensive Multimodal Offensive and Hate Speech Twitter Dataset and Experiments 🖼️📝

## 📌 Overview
This repository provides a curated dataset and experimental notebooks for **Multimodal Offensive and Hate Speech Detection**.  
The dataset includes **tweet IDs** and **binary labels (Offensive|Hate|Normal)**, enabling researchers and students to explore **image–text Offensive and Hate Speech Detection** on social media platforms.

The accompanying notebook demonstrates how to load the dataset, conduct ablation experiments, and evaluate multimodal learning architectures in a reproducible manner.

---

## 📂 Dataset Format
The dataset is released as "MafiaNetDataset.csv" with the following structure:

- `id` – Twitter Tweet ID  
- `label` – Class label (`2` = Offensive, `1` = Hate, `0` = Normal)   

✔️ Only Tweet IDs are shared to fully comply with Twitter/X data-sharing policies.

---
## 📊 FCMOH Dataset Summary
-The following table summarizes the construction of the FCMOH dataset in terms of annotation strategy, context, and class distribution.

| Dataset          | Annotators | Context                                 | Normal     | Hate      | Offensive | Total      |
| ---------------- | ---------- | --------------------------------------- | ---------- | --------- | --------- | ---------- |
| Founta et al.    | 5–20       | HateBase and offensive words dictionary | 7,360      | 191       | 1,430     | 8,981      |
| MeToo            | 3          | MeToo movement                          | 7,635      | 552       | –         | 8,187      |
| Zerouk et al.    | 1          | List of users                           | 862        | 158       | –         | 1,020      |
| Hateval          | 3+         | Immigrant and Women                     | 810        | 197       | –         | 1,007      |
| Davidson et al.  | 3+         | HateBase keywords                       | 213        | 36        | 505       | 754        |
| HASOC            | 2–3        | List of keywords                        | 461        | 148       | 105       | 714        |
| HAR              | 2–3        | Harassment keywords                     | 51         | 20        | –         | 71         |
| **FCMOH (Ours)** | **19–20**  | **All above contexts**                  | **17,392** | **1,302** | **2,040** | **20,734** |

---

## 🧪 Notebook (Ablation Study)
The provided notebook includes the following experimental settings:
- 📝 **Text Encoder Only** Text Encoder Only.ipynb
- 🖼️ **Image Encoder Only** Image Encoder only.ipynb
- ❌ **MAFIA-Net without MARBERTv2** Without Marbert.ipynb
- ❌ **MAFIA-Net without EfficientNet-B1** Without efficientnetb1.ipynb
- ❌ **MAFIA-Net without HCMA** Without HCMA.ipynb
- ❌ **MAFIA-Net without VGTA** Without VGTA.ipynb
- ✅ **Full MAFIA-Net Model** MafiaNet.ipynb

These experiments highlight the contribution of each module to multimodal fake news detection.

---

## 🔐 Accessing the Full Dataset
Due to Twitter/X content redistribution policies, the **full hydrated dataset** is not publicly released.

📩 To request access, please fill out the following Google Form:  
👉 https://docs.google.com/forms/d/1RAmKljzO_0poMIDWBeHqbJchwi_RfAyMvlasbwY46E4/edit

Requests are intended for **research and academic use only**.

---

## 📚 Citation
If you use this dataset or code in your research, please cite:

@article{mafianet2026,
  title={The-First-Comprehensive-Multimodal-Offensive-and-Hate-Speech-Twitter-Dataset-and-Experiments},
  author={},
  journal={},
  year={2026}
}

---

## ⚖️ License
This repository is released for **research and educational purposes**.  
Tweet IDs are shared in accordance with Twitter/X Developer Policy.

