# Multimodal-Reasoning-ImageCLEF-2025
Zero-shot pipeline for Visual Question Answering in the ImageCLEF 2025 Multimodal Reasoning task. 
---

## 🔍 System Overview

This pipeline addresses the multilingual VQA task by:

1. Accepting an image of an exam question (with MCQs, tables, graphs, diagrams, etc.).
2. Extracting structured JSON (question, options, visuals) using **Gemini** with a layout-aware zero-shot prompt.
3. Performing answer selection using **DeepSeek-R1-Distill-LLaMA** via a strict, reasoning-free prompt.
4. Outputting results in a `pred.json` file for evaluation.

---

## 🏆 Results (CLEF Leaderboards)

> Our approach placed in the top-3 in several tracks — read more in the [CLEF Working Notes](https://clef2025.clef-initiative.eu/).

