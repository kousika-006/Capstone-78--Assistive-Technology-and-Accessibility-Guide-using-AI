# Capstone 78: Empirical AI Accuracy Findings & Tool Benchmarks

This document summarizes the empirical accuracy benchmarks, key limitations, and human-in-the-loop audit findings for AI accessibility tools evaluated during **Capstone 78**.

---

## 1. Tool Performance & Accuracy Matrix

| Tool / Model | Primary Function | Accuracy Benchmark | Key Limitations & Findings |
| :--- | :--- | :---: | :--- |
| **ChatGPT / Gemini** | Visual Alt-Text & Diagram Description | **90%** | Prone to visual hallucinations on complex, low-contrast graphics; requires prompt refinement. |
| **ElevenLabs** | Synthetic Text-to-Speech (TTS) | **95%** | Excellent cadence for vision-impaired learners; occasional mispronunciation of niche academic acronyms. |
| **NotebookLM** | Grounded Source Summarization | **92%** | Highly accurate, but performance is strictly constrained by the scope and quality of uploaded sources. |
| **Windows Live Captions** | Real-Time Speech-to-Text | **88%** | Accuracy drops in noisy audio environments or when multiple speakers overlap. |
| **NVDA & VoiceOver** | Screen Reader Document Navigation | **100% Compliance** | Achieved full accessibility compliance provided semantic headings and ARIA landmarks are present. |

---

## 2. Key Qualitative Audit Takeaways

### A. The 10% AI Hallucination Rate
Empirical testing across 15 complex educational diagrams revealed a baseline **~10% error rate** in Large Language Models. AI models occasionally invent non-existent visual details or misread technical notations on low-contrast charts.

### B. Human-in-the-Loop (HITL) Requirement
Due to the non-zero error rate in visual analysis, **zero-review automation is strictly discouraged**. A mandatory 30-second Human-in-the-Loop audit is required for all AI-generated alt-text to verify:
1. Technical and domain-specific terminology accuracy.
2. Complete absence of fabricated visual elements or false labels.
3. Alignment with specific pedagogical lesson objectives.

### C. Efficiency Gains
Despite the necessity of human oversight, integrating AI baseline drafting into course preparation achieved **up to 80% overall time savings** (reducing weekly accessibility retrofitting from 15+ hours to under 3 hours).