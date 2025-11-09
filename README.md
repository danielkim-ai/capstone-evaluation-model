# ✨ Capstone Design Project: Evaluation Model for AI-Assisted Authoring Tools

This repository summarizes my contributions to the **Last Episod** capstone project at Yonsei University, which aims to **optimize contextual sentence prediction models** for creative writing.

> 🧭 *Private industrial repository — this page shares conceptual design and documentation only.*

---

## 🧠 Overview
**Goal:** Develop an advanced evaluation model that objectively scores AI-generated sentence recommendations based on contextual quality, creativity, and fluency.

**My Role:** Evaluation Model Team Member (2 of 4)
- Designed evaluation rubrics integrating **Contextual Coherence**, **Creativity**, and **Fluency**.
- Engineered and refined **LLM-as-judge** evaluation prompts for Gemini-2.5 models.
- Created **110 test cases** (20 per book × 11 books) for calibration and consistency checks.
- Implemented structured feedback extraction and result analysis pipelines.

---

## ⚙️ System Summary
- **Input:** Paragraph-level context packets from Episod authoring interface  
- **Evaluation Model:** Gemini-2.5-flash (LLM-as-Judge)  
- **Output:** 5-criteria scoring (0–10 scale) with concise reasoning text  


---

## 🧩 Future Work
- Automate feedback extraction using structured JSON outputs  
- Integrate pairwise comparison evaluation (as proposed in *BESPOKE*, 2024)
- Incorporate weighted composite metrics for information consistency

---

## 📎 Related Link
- [Episod Official Service Page](https://episod.ink/)
