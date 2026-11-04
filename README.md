<p align="center">
  <img src="assets/banner.jpeg" alt="Neural Network Banner" width="100%" />
</p>

<h1 align="center">Meisam Mahmoodi 🧠</h1>

<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=9F7AEA&center=true&vCenter=true&width=520&lines=PhD+Candidate+%40+Adelaide+University;Interpretability+of+Language+Models;Sparse+Concepts+%26+Causal+Representations;" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  INTERPRETABILITY • SPARSE CONCEPT LEARNING • CAUSAL REPRESENTATION LEARNING
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/meisam-mahmoodi">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://scholar.google.com/citations?hl=en&user=IOXPIqEAAAAJ">
    <img src="https://img.shields.io/badge/Google_Scholar-4285F4?style=for-the-badge&logo=google-scholar&logoColor=white" />
  </a>
  <a href="mailto:m.mahmoodi@outlook.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>

---

### 🧐 About Me

I am a **Computer Science PhD candidate** at **Adelaide University**, Australia, in the **Causal AI Group** (AIML), supervised by **Prof. Javen Qinfeng Shi**.

I study what language models represent inside their activations. My main question is simple: when the same meaning is written in different ways — a paraphrase, a simpler rewrite, another language — which part of the model's representation stays the same (**content**), and which part changes (**form / realization**)? I build sparse, concept-level methods (SAEs and **Concept Component Analysis, ConCA**) that separate these two parts and test them with causal interventions, not only with probes.

---

### 🚀 Current Project: [Multi-View ConCA](https://github.com/MeiisamMahmoodii/MVConCA)

**The problem.** Sparse autoencoders (SAEs) find features that *detect* things in a model's activations, but pushing one of those features often doesn't *control* the model cleanly. Ask for "blue" and the shape or material changes too, or nothing changes at all. One reason: an SAE rebuilds each activation on its own, so nothing tells it to keep **what is said** (the facts) apart from **how it is said** (the wording).

**What Multi-View ConCA does.** It extends Concept Component Analysis (ConCA) by splitting the learned code into two blocks:

*   **C — content**: the facts.
*   **S — style**: the wording.

It learns this split from two kinds of paired examples:

| Pair type | Example | What the training does |
|---|---|---|
| **Paraphrase** — same facts, new wording | "a small red metal cube" ↔ `{"object": "cube", "colour": "red", …}` | pull the two **C** codes together |
| **Minimal edit** — one fact changes, same wording | "a small **red** metal cube" ↔ "a small **blue** metal cube" | keep **S** fixed, so only **C** moves |

**The result.** Push a *single* content coordinate and the model's answer changes only the fact you targeted:

> "small red metal cube" → push the colour coordinate → "small **blue** metal cube" ✓ (shape, size and material unchanged)

On scenes and wording styles never seen in training, one-coordinate edits change the target answer while keeping all the other answers correct in **64.4%** of cases. The best SAE baseline gets **31.5%**, so this is about twice as good. The edits also steer free-form generation and work on models from different families. *Paper in preparation.*

---

### 📚 Earlier Work

*   **SetConCA** — set-conditioned sparse concept learning: extends pointwise SAEs by learning concept codes from *sets* of related views (paraphrases, multiple captioning models) instead of single sentences.
*   **Utilizing Large Language Models for DDoS Attack Detection** (2024) — *M. Mahmoodi*, OPJU International Technology Conference (OTCON). Turns network traffic features into natural-language descriptions so LLMs can detect DDoS attacks with zero-shot reasoning and parameter-efficient fine-tuning.

📄 Full list on [Google Scholar](https://scholar.google.com/citations?hl=en&user=IOXPIqEAAAAJ).

---

### 🛠️ Languages & Tools

<div align="center">
  <img src="https://skillicons.dev/icons?i=python,pytorch,tensorflow,git,vscode,latex,md&theme=dark" alt="Tools" />
  <br>
  <img src="https://skillicons.dev/icons?i=react,ts,js,expo,nodejs,html,css&theme=dark" alt="Tech" />
</div>

---

### 📊 GitHub Analytics

<div align="center">
  <a href="https://github.com/anuraghazra/github-readme-stats">
    <img height="180em" src="https://github-readme-stats-salesp07.vercel.app/api?username=meiisammahmoodii&show_icons=true&include_all_commits=true&count_private=true&rank_icon=github&cache_seconds=7200&theme=tokyonight&hide_border=true&bg_color=0D1117" alt="GitHub Stats" />
  </a>
  <a href="https://github.com/anuraghazra/github-readme-stats">
    <img height="180em" src="https://github-readme-stats-salesp07.vercel.app/api/top-langs/?username=meiisammahmoodii&layout=compact&langs_count=8&cache_seconds=7200&theme=tokyonight&hide_border=true&bg_color=0D1117" alt="Top Languages" />
  </a>
</div>
