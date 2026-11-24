# Kunal Sharma

**Independent AI Safety Researcher · Red Teamer · Systems Builder**
*Statistically self-employed.*

`Python` · `JAX` · `Rust` · `C++/CUDA` · `PyTorch` · `Linux (Arch)` · `Docker`

I build open-source LLM evaluations, train transformers from scratch, and run adversarial simulations to see what models do when the pressure is real and the exits are fake.

Currently exploring whether Mamba mixes better with Transformers than Softmax mixes with my sanity. *(The chimera ablates fine. The sanity is still under review.)*

I spend my days estimating unknown functions just so I can put hats on variables — ŷ, f̂, the whole wardrobe.

> Nothing says "I tried" like a circumflex.

---

## 🔬 Evals, Safety & Research

**[MetaProbe](https://github.com/0xKunalsharma/MetaProbe)** — Open-source benchmark for metacognition and calibration in frontier LLMs: whether models know what they know, and whether their confidence tracks their accuracy. Live on Kaggle as a hosted leaderboard. Featured writeup in Kaggle's [Measuring AGI](https://www.kaggle.com/competitions/kaggle-measuring-agi/writeups/new-writeup-1775318374748) competition.

**[Taxlab](https://github.com/0xKunalsharma/Taxlab)** — Rust + Python multi-agent simulation testing LLM tax evasion under pressure. Full write-up on the EA Forum: *"73 credits is honest. 80 is a gamble."*

**[BAZT](https://github.com/AntGalasso/swarmlab)** — Budgeted agentic zero-trust enforcement against prompt contagion in LLM agent swarms. Built with team ZeroTrust Fund at Apart Research's Swarm Alignment Hackathon. Two-tier defense, budgeted audits, 2,400-episode sweeps. 
*Note on integrity:* A post-hoc audit (PR #7) found calibration and pairing bugs, so results are provisional pending recomputation; see the repo's status banner before citing numbers. The swarm voted 19–9 that I should take a break. I ignored the vote.

### AI × Epistemics (Apart Research, Nov 2026)

**[Fewer Recorded Vote Switches, No Net Gain in Correct Answers](https://apartresearch.com/sprints/projects/fewer-recorded-vote-switches-no-net-gain-in-correct-answers-4oqc50md21)** — Co-authored with Antonio Galasso, Ricardo Fitas, and Vittoria Lanzo. Compared early message blocking and warnings against final-vote filtering in 256 paired Qwen3.8-27B debates. Early intervention reduced recorded vote switches from 64 to 23, but the group moved from 40 correct answers to 39—fewer recorded switches, no net epistemic gain. Archived-debate audit with EpistemicGuard tied XG-Guard and improved on PREM by 4.14pp in matched held-out comparisons. **Reviewer caveat:** the live experiment's prompt loader omitted the text of answer choices, so the 40→39 comparison is a counting-artifact demonstration, not a clean measure of intervention effect; the archive scoring audit remains the paper's strongest contribution.

**[Question Sets and Answer Keys Reverse Language Model Comparisons](https://apartresearch.com/sprints/projects/question-sets-and-answer-keys-reverse-language-model-comparisons-dfxbn8lnii)** — Co-authored with Ricardo Fitas, Antonio Galasso, and Vittoria Lanzo. The ScienceQA leaderboard compares GPT-3's score over all 4,241 test questions with LaVIN-7B's score over only the 2,017 image questions. Matching question IDs and rescoring archived predictions flips GPT-3's apparent **0.06pp lead** into a **7.68pp deficit** for LaVIN-7B; 4 of 20 audited comparisons reverse and 1 ties. A WinoGrande adapter that omits the sentence hides at least **48.8pp** of the gain in answering both questions correctly. **Reviewer note:** the ScienceQA set was selected after the LaVIN entry was spotted, so prevalence across leaderboards remains an open question; the audit methodology is directly reusable.

---

## ⚙️ Systems & Engineering

**[jax-ml-scratch](https://github.com/0xKunalsharma/jax-ml-scratch)** — Transformers, tokenizers, and optimizers built entirely from raw JAX. No frameworks, no shortcuts, no mercy.

**[parameter-golf](https://github.com/0xKunalsharma/parameter-golf)** — A 9-layer GQA transformer compressed to 15.87 MB via int8 + zlib (OpenAI PR #1038). Because "it fits in an email" is the only compression metric my non-ML friends respect.

---

## 🏆 Competitions

**[Orbitwars](https://github.com/0xKunalsharma/Orbitwars)** — 957/4,729 (top 21%), Kaggle Orbit Wars. A pure-tensor planner that models orbital planet motion, projects garrison states over a rolling horizon, and emits sparse multi-wave launches like a general who thinks in tensors. Top 21% in Orbit Wars. Bottom 80% in any orbit resembling a normal sleep schedule.

Other Kaggle comps, all solo:
- [Student Health Risk](https://www.kaggle.com/competitions/playground-series-s6e7) — 595/3,355 (top 18%, quietly my best finish)
- [AI Agent Security - Multi-Step Tool Attacks](https://www.kaggle.com/competitions/ai-agent-security-multi-step-tool-attacks) — 2,677/4,186 (entered for the theme; the leaderboard had other plans)
- [Biohub Cell Tracking](https://www.kaggle.com/competitions/biohub-cell-tracking-during-development) — 1,717/3,947

---

**Find me:** [Kaggle](https://www.kaggle.com/kunalsharma0x) · [LinkedIn](https://www.linkedin.com/in/mlksh) · neo.kunal.s@proton.me

*Life is expensive... like softmax.*
*There exists some unknown relationship between me and sleep. I'm still trying to estimate f.*
