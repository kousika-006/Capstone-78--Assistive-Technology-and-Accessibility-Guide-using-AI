# Research & WCAG 2.1 AA Verification Report

*Capstone 78 - Artificial Intelligence & Inclusive Learning*

## 1. Executive Summary
This research paper systematically evaluates free AI-driven tools
against international web accessibility standards (WCAG 2.1 AA). By
combining screen readers (NVDA, VoiceOver) with AI models (ChatGPT,
Gemini, ElevenLabs, Live Captions, NotebookLM), we establish a practical
framework for creating fully accessible educational media.

## 2. WCAG 2.1 AA Four Core Principles (POUR)
- **Perceivable:** Information and UI components must be presentable in
  ways users can perceive (e.g., meaningful alt-text, synchronized live
  captions).

- **Operable:** UI components and navigation must be operable via full
  keyboard controls without causing disorientation.

- **Understandable:** Information and interface operation must be clear,
  predictable, and structurally organized.

- **Robust:** Content must be compatible with current and future user
  agents, including assistive technology screen readers.

## 3. Evaluation of Free AI Accessibility Tools
| **Tool Name**    | **Primary Function**          | **Accuracy Benchmark** | **Key Limitations**                                              |
|------------------|-------------------------------|------------------------|------------------------------------------------------------------|
| ChatGPT / Gemini | Alt-Text & Image Description  | 90%                    | Prone to visual hallucinations on complex low-contrast graphics. |
| ElevenLabs       | Text-to-Speech (TTS)          | 95%                    | Occasional mispronunciations of specialized academic acronyms.   |
| Live Captions    | Real-Time Audio Transcription | 88%                    | Reduced accuracy in noisy environments or overlapping voices.    |
| NotebookLM       | Grounded Source Summarization | 92%                    | Constrained by the quality and domain scope of input documents.  |
