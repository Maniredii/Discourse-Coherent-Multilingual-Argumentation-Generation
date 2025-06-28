# Discourse-Coherent Multilingual Argumentation Generation

> Generate coherent arguments across multiple languages using AI models like MarianMT, BART, and IndicTrans.

![Model Workflow](https://img.shields.io/badge/NLP-Multilingual-green?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Active-blue?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

---

## 🧠 Project Overview

This project implements a **Multilingual Argumentation Generator** that accepts a claim, supports coherent argument generation in English using BART, and translates the results into Indian languages like Tamil and Telugu using MarianMT and AI4Bharat IndicTrans models.

✅ Built for discourse-level coherence  
✅ Supports multilingual generation (English + regional languages)  
✅ Integrates grammar correction, translation, and argument generation

---

## 📌 Features

- **Discourse-Aware Argument Generation** with BART
- **Multilingual Translation** (English ↔ Tamil/Telugu)
- **Grammar Correction** using Gramformer
- **Interactive Colab Interface**
- Modular & extensible pipeline for future enhancements

---

## 🛠️ Technologies Used

| Component        | Tools/Models                              |
|------------------|--------------------------------------------|
| NLP Models       | `facebook/bart-large`, `Helsinki-NLP/opus-mt`, AI4Bharat IndicTrans |
| Grammar Check    | Gramformer                                 |
| Libraries        | Transformers, Torch, spaCy, OpenNMT        |
| Notebook Runtime | Google Colab / Jupyter                     |

---

Run each cell in the notebook sequentially:

Input a claim

Generate arguments in English

Translate arguments to other languages

🌐 Sample Output
Input Claim:
"Social media reduces real-world social interaction."

Generated Argument (English):
"Overuse of platforms like Instagram and Facebook leads to a decline in face-to-face conversations."

Translated Argument (Tamil):
"இன்ஸ்டாகிராம் மற்றும் ஃபேஸ்புக் போன்றவற்றை过ப்பயன்படுத்துவதால் நேரடி உரையாடல்கள் குறைகின்றன."

🤝 Contribution
Contributions are welcome! Please open issues or submit PRs if you'd like to improve translation support, add UI, or integrate additional languages.

📜 License
This project is licensed under the MIT License. See LICENSE for details.

👨‍💻 Author
Manideep Reddy Eevuri
