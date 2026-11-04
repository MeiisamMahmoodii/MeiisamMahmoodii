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

I am a **Computer Science PhD candidate** at **Adelaide University**, Australia, in the **Causal AI Group** (AIML), supervised by **Prof. Javen Qinfeng Shi**. I work on **interpretability of language models**: understanding what a model has learned inside its activations, and using that understanding to **control** it.

---

### 🔬 Research Area

**The big question.** A language model's hidden state mixes two kinds of information:

*   **What is said** — the content, the facts, the meaning.
*   **How it is said** — the wording, style, format or language.

*Example:* "a small red metal cube", "a little cube made of red metal" and `{"object": "cube", "colour": "red"}` all say the same thing. Inside the model, part of the representation should stay the same across all three (content) and part should change (wording). I study how to find and separate these two parts.

**Why it matters.** Tools like sparse autoencoders (SAEs) can find features that *detect* a concept, but editing those features often doesn't *control* the model cleanly. Ask for "blue" and the shape changes too, or nothing changes at all. If content and wording are separated, we can:

*   **Edit one fact** and leave everything else alone (red → blue, nothing else moves).
*   **Get the same answer however the question is phrased**, across paraphrases, styles and languages.
*   **Spot the same intent behind different surface forms**, e.g. a harmful request hidden behind unusual wording.

**How I approach it.**

1.  **Learn from paired views, not single examples.** Paraphrases, rewrites and translations show what should stay fixed; minimal edits ("red cube" vs "blue cube") show what a single fact change looks like. These pairs give a weak supervision signal without needing concept labels.
2.  **Sparse, concept-level dictionaries.** Methods built on SAEs and **Concept Component Analysis (ConCA)**, so that each concept lives in a small number of readable coordinates.
3.  **Causal tests, not just probes.** A feature counts only if changing it changes the model's behaviour in the expected way — and nothing else.

I am also starting to apply these ideas to **AI agents**: reading what goal an agent is actually pursuing from its internal state.

---

### 📚 Selected Work

*   **[Multi-View ConCA](https://github.com/MeiisamMahmoodii/MVConCA)** — splitting a concept dictionary into content and wording blocks, so a single coordinate can change one fact in the model's answer. *(in preparation)*
*   **SetConCA** — learning concept codes from *sets* of related views (e.g. paraphrases) instead of single sentences.
*   **Utilizing Large Language Models for DDoS Attack Detection** (2024) — *M. Mahmoodi*, OPJU International Technology Conference (OTCON).

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
