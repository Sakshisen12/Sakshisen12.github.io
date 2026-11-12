---
layout: single
title: "Projects"
permalink: /portfolio/
author_profile: true
---

## Resume AI — Intelligent Resume & Job Match Analyzer

**Tech Stack:** React 19, Vite, Tailwind CSS, Node.js, Express.js, MongoDB Atlas, Gemini 2.5 Flash, Vercel, Render

[GitHub](https://github.com/Sakshisen12/ai-resume-analyzer) | [Live Demo](https://ai-resume-analyzer-rust-phi.vercel.app/)

- Full-stack AI analyzer using Google Gemini 2.5 Flash for a 0–100 impact score, ATS compatibility %, skill-gap detection, and a job matcher with match % and keyword gaps for any job description
- Node.js/Express.js REST API with MongoDB Atlas, JWT auth, PDF parsing, analysis history, and a multi-model Gemini fallback chain
- React dashboard with a Recharts skill radar

---

## Bureaucracy Survival RPG — RAG-Powered Policy Game

**Tech Stack:** React 19, Vite, Tailwind CSS, FastAPI, LangChain, BM25, Groq API (Llama 3), Vercel, Render

[GitHub](https://github.com/Sakshisen12/bureaucracy-rpg-rag) | [Live Demo](https://bureaucracy-rpg-rag.vercel.app)

- Full-stack RAG web game: upload a policy PDF and an LLM Game Master judges in-game actions against its actual clauses, citing the section
- Retrieval pipeline with PyPDFLoader, recursive chunking, and BM25 search (top-3 chunks) feeding structured JSON output from Llama via the Groq API — no embeddings or GPU required
- Multi-turn memory, per-IP rate limiting (20 requests/hour), and automatic model detection; frontend on Vercel, REST backend on Render

---

## AI-Driven DevSecOps Pipeline

**Tech Stack:** Azure Pipelines, DevSecOps, Bandit, Trivy, Gemini API, Docker, Python

[GitHub](https://github.com/Sakshisen12/devsecops-ai-platform)

- Automated DevSecOps pipeline on Azure Pipelines integrating SAST analysis (Bandit), container vulnerability scanning (Trivy), and LLM-based code review using the Gemini API
- Severity-weighted security gates to automate vulnerability assessment, plus an audit dashboard for improved code security visibility
