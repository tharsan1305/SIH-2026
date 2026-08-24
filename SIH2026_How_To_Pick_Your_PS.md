# SIH 2026 — How to Pick Your Problem Statement (Decision Guide)

**Purpose:** A step-by-step decision framework to help your team choose the *right* SIH 2026 problem statement out of 226 — instead of picking randomly or copying what's "trending."

This guide walks through **6 filtering questions**. Answer them in order. Each question narrows your options. By the end, you'll have a shortlist of 5–10 PS that genuinely fit your team.

---

## 🧭 Step 0 — Before You Start: 3 Ground Rules

1. **Don't pick a PS just because it "sounds cool."** Cool titles (drones, quantum, blockchain) attract the most competition and the least realistic execution.
2. **Match the PS to your team's actual skills — not your aspirational skills.** If nobody knows embedded hardware, don't pick a hardware PS hoping to "learn it in 3 days."
3. **Feasibility beats ambition.** A working, well-scoped 🟢 Easy solution beats a half-built 🔴 Difficult one every time in evaluation.

---

## 🪜 Step 1 — What is your team's core skillset?

Pick the ONE that best describes your team's *strongest* combined skill (not everyone needs to know everything):

| Team Type | Look at PS in these categories |
|---|---|
| **Web/App Developers** (React, Node, Flutter, Django) | Software PS with dashboard/portal/marketplace patterns — see 🟢 Easy list |
| **ML/Data Science heavy** (Python, scikit-learn, TensorFlow) | MoES weather cluster, crop disease, forecasting, anomaly detection |
| **Cybersecurity/Networking** (security, forensics, crypto) | NTRO/MHA cybersecurity cluster (32 PS — see dedicated cyber file) |
| **Hardware/Embedded** (Arduino, sensors, PCB, IoT) | Hardware PS — Ministry of Coal, DRDO, MoES ocean/sonar, Qualcomm IoT |
| **Cloud/DevOps + Data Engineering** | Big-data platforms, data pipelines (MoES big-data, MoSPI monitoring platforms) |
| **Generalist / mixed skills, first hackathon** | Stick strictly to 🟢 Easy tier — standard CRUD/dashboard/chatbot builds |
| **AI/NLP/GenAI focused** | RAG assistants, chatbots, multilingual NLP (BIS assistant, IP-SAKTI, vernacular translation) |

👉 **Action:** Write down your team's top 2 skills right now. That eliminates ~70% of the 226 PS immediately.

---

## 🪜 Step 2 — How much time do you actually have?

| Time Available | Strategy |
|---|---|
| Only the 36–48 hr hackathon window | Pick 🟢 Easy only. No hardware fabrication, no niche research-level AI. |
| 1–2 weeks of prep before internal round | 🟢 Easy or 🟡 Medium — enough time to learn one new tool/library |
| 3–4+ weeks, dedicated team, mentor support | 🟡 Medium or 🔴 Difficult is realistic |
| You already have a working prototype/idea from before | Any tier — just make sure it maps cleanly to a real PS |

---

## 🪜 Step 3 — Do you have hardware access / budget?

- **No budget, no lab access** → Eliminate ALL Hardware-category PS. Stick to Software only (172 of 226 are software).
- **Some budget (₹2,000–10,000), basic electronics access** → Simple hardware PS okay (sensors, IoT kits) — avoid anything needing defense-grade fabrication, RF/antenna design, or precision lab equipment.
- **College lab / workshop access, real budget** → Full hardware PS open to you, including 🔴 Difficult tier.

---

## 🪜 Step 4 — Do you want a crowded space or a niche space?

This is a strategic choice, not a skill one:

| Choice | Pros | Cons | Example PS type |
|---|---|---|---|
| **Crowded space** (crop disease detection, chatbots, ANPR) | Tons of tutorials/reference implementations, easy to get *something* working fast | Judges have seen 20 versions of this before — differentiation is hard | SIH26131 (crop disease), SIH26127 (ANPR) |
| **Niche space** (ISRO imagery, NTRO signal analysis, MoES ocean data) | Fewer existing solutions, higher "wow factor," judges remember you | Less documentation/reference material, steeper learning curve | SIH26166 (Chandrayaan imagery), SIH26057 (side-scan sonar) |

👉 **Beginner teams:** crowded space with a genuinely differentiated angle (e.g., "onion grading — but hyperlocal for a specific mandi") often scores better than a half-finished niche attempt.

---

## 🪜 Step 5 — Check real-world data availability

**Before finalizing, always ask: "Can I actually get data to build/demo this?"**

✅ **Good data availability (build-friendly):**
- IMD/Mausam weather data — [mausam.imd.gov.in](https://mausam.imd.gov.in)
- ISRO Bhuvan/Bhoonidhi satellite imagery — [bhuvan.nrsc.gov.in](https://bhuvan.nrsc.gov.in)
- NASA FIRMS fire data — [firms.modaps.eosdis.nasa.gov](https://firms.modaps.eosdis.nasa.gov)
- eNAM agriculture market data
- PlantVillage / open crop-disease datasets
- Bhashini/AI4Bharat language models & datasets

⚠️ **Hard/restricted data (avoid unless you have institutional access):**
- Defense/DRDO classified data (SIH26050, 26055, 26098)
- NTRO signal-intelligence datasets (you'll have to simulate/synthesize data yourself)
- MHA crime/financial-crime datasets (use public proxies like known scam-report datasets instead)

👉 **Action:** For every PS on your shortlist, do a 10-minute search — "is there a public dataset for X?" If the answer is no and you can't simulate one convincingly, deprioritize it.

---

## 🪜 Step 6 — Final Shortlist Filter (Run this checklist per PS)

For each PS still on your shortlist, score Yes/No:

- [ ] Does at least one team member already know 70%+ of the required tech stack?
- [ ] Can you find or generate a usable dataset within 1 day?
- [ ] Can you build a demoable MVP (even a rough one) within your available time?
- [ ] Does the PS solve a real, explainable problem you can pitch in 2 minutes?
- [ ] Is there a clear way to differentiate from existing solutions (even a small one)?

**If a PS scores 4-5 Yes → shortlist it seriously.**  
**If it scores 2 or less → drop it, no matter how exciting it sounds.**

---

## 🎯 Worked Example

> **Team:** 3 web devs, 1 ML beginner, 1 designer. No hardware access. 10 days before internal round.

1. **Skillset →** Web/App + light ML → eliminates all Hardware PS
2. **Time →** 10 days → 🟢 Easy or 🟡 Medium only
3. **Hardware →** None → Software-only
4. **Space choice →** Team prefers a moderately crowded space with room to differentiate (safer for first attempt)
5. **Data check →** Needs public data
6. **Result shortlist:** SIH26131 (Crop Disease Detection — 🟢 Easy, public datasets, room to differentiate with "hyperlocal onion/crop advisory"), SIH26107/108 (BIS AI Assistant — 🟢 Easy, RAG pattern, well-documented), SIH26092 (Scheme Matching — 🟢 Easy, rule-based + simple NLP)

---

## 📌 Quick Reference: Filtering Cheat Sheet

| If you have... | Then look at... |
|---|---|
| No hardware, first hackathon | 🟢 Easy tier, Software only |
| ML/data science strength | MoES weather/climate cluster, crop/disease detection |
| Security/networking strength | NTRO/MHA cybersecurity cluster |
| Hardware + budget + lab | Any hardware PS matching your interest area |
| A truly original idea, no fixed PS fits | Pick any AICTE Student Innovation (⚪) slot in your best theme |
| Want highest "wow factor" and can handle research-level work | ISRO/NTRO niche software cluster (🔴 tier) |

---

## ⚠️ Common Mistakes to Avoid When Selecting

1. **Picking based on the org's prestige** (ISRO/DRDO) instead of actual fit — restricted data will sink you.
2. **Choosing a PS nobody on the team actually understands the domain of** — you'll struggle to even explain the problem to judges.
3. **Ignoring competition level** — picking something extremely crowded (e.g., generic chatbot) with zero differentiation angle.
4. **Not checking data availability first** — many teams pick a PS, then discover on Day 2 that no usable data exists.
5. **Overestimating hardware timelines** — hardware builds always take 2–3x longer than planned.

---

**Next steps after shortlisting:** Once you have your top 3 PS, cross-check them against:
- [SIH_2026_DIFFICULTY_LEVELS.md](file:///d:/Sih/SIH_2026_DIFFICULTY_LEVELS.md) (Easy/Medium/Difficult tags)
- [SIH_2026_RESEARCH_AND_ANALYSIS.md](file:///d:/Sih/SIH_2026_RESEARCH_AND_ANALYSIS.md) (competition/innovation scoring)
- [SIH_2026_CYBERSECURITY_CLOUD_DATA_SCIENCE.md](file:///d:/Sih/SIH_2026_CYBERSECURITY_CLOUD_DATA_SCIENCE.md) (if relevant to your domain)

Then move to problem-statement deep-dive: rewrite the PS in your own words, sketch a rough architecture, and validate feasibility with a 2-hour spike/prototype before committing fully.

---

**Disclaimer:** This is an independent, community-made decision framework to help students navigate SIH 2026 faster. It is not an official SIH/AICTE document. Always refer to the official problem statement PDF on the SIH portal for exact requirements before final submission.
