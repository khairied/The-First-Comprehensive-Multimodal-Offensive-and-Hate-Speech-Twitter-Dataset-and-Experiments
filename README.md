# 🚨 MAFIA-Net  
### The First Comprehensive Multimodal Offensive and Hate Speech Twitter Dataset and Experiments 🖼️📝

## 📌 Overview
This repository provides a curated dataset and experimental notebooks for **Multimodal Offensive and Hate Speech Detection**.  
The dataset includes **tweet IDs** and **binary labels (Fake/Real)**, enabling researchers and students to explore **image–text Offensive and Hate Speech Detection** on social media platforms.

The accompanying notebook demonstrates how to load the dataset, conduct ablation experiments, and evaluate multimodal learning architectures in a reproducible manner.

---

## 📂 Dataset Format
The dataset is released as "MafiaNetDataset.csv" with the following structure:

- `id` – Twitter Tweet ID  
- `label` – Class label (`2` = Offensive, `1` = Hate, `0` = Normal)   

✔️ Only Tweet IDs are shared to fully comply with Twitter/X data-sharing policies.

---

## 📝 Linguistic Statistics
| Class     | Tweets   | Total Words | Unique Words | Avg. Words / Tweet |
| --------- | -------- | ----------- | ------------ | ------------------ |
| Real      | 3777     | 71,548      | 19,694       | 18.94              |
| Fake      | 1361     | 30,474      | 10,158       | 22.39              |
| **Total** | **5138** | **102,022** | **25,431**   | **19.86**          |

## 📊 Dataset Statistics
🔹 Distribution of Multimodal Tweets per Source Dataset

| Dataset    | # Real           | # Fake           | Total (%)       |
| ---------- | ---------------- | ---------------- | --------------- |
| ArCOV-19   | 265              | 339              | 604 (11.8%)     |
| Covid3s400 | 287              | 28               | 315 (6.1%)      |
| FakeReal   | 686              | 200              | 886 (17.2%)     |
| MFH        | 176              | 144              | 320 (6.2%)      |
| NewID      | 216              | 167              | 383 (7.5%)      |
| Covid5K700 | 505              | 190              | 695 (13.5%)     |
| Rumor      | 1642             | 293              | 1935 (37.7%)    |
| **Total**  | **3777 (73.5%)** | **1361 (26.5%)** | **5138 (100%)** |


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

