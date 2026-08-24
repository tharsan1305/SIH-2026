# SIH 2026 — Reusable Research Prompt Template (For ONE Selected Problem Statement)

**Purpose:** Once your team has shortlisted or finalized ONE problem statement, copy the prompt below, fill in the `[ ]` blanks with your PS details, and paste it into Claude (or any AI research assistant) to get a full deep-dive research report on that single idea — competitors, feasibility, tech stack, architecture, risks, and a pitch-ready summary.

---

## 📋 How to Use This Template

1. Copy the **PROMPT TEMPLATE** section below.
2. Fill in the bracketed fields `[ ]` with your chosen PS's details (ID, title, org, category).
3. Paste the completed prompt into a new chat with Claude (enable web search / research mode if available).
4. Save the output as `[PS_ID]_Deep_Research.md` in your project folder.

---

## 📝 PROMPT TEMPLATE (Copy everything below this line)

```
Act as a Senior Product Researcher, Startup Strategist, Technology Architect,
and SIH Mentor. I have selected ONE problem statement from SIH 2026 that my
team wants to build. Do a complete deep-dive research and planning report on
this single idea.

PROBLEM STATEMENT DETAILS:
- PS ID: [SIH26XXX]
- Title: [Paste exact title here]
- Organization: [Paste organization/department here]
- Category: [Software / Hardware]
- Theme: [Paste theme name here]
- Full problem description (if available): [Paste the detailed description
  from the official SIH PDF here — if you only have the title, say so
  explicitly so I don't assume details that weren't given]

MY TEAM CONTEXT (fill in honestly — this shapes the recommendations):
- Team size: [e.g., 6 members]
- Skills available: [e.g., 2 web devs, 1 ML, 1 designer, 1 hardware, 1 PM]
- Time available before submission: [e.g., 10 days / 36 hours]
- Hardware/budget access: [None / Limited / Full lab access]
- Preferred tech stack (if any): [e.g., React + Python + Firebase, or "open
  to suggestions"]

RESEARCH TASKS — please cover ALL of the following:

1. PROBLEM UNDERSTANDING
   - Restate the problem in plain language — what is actually being asked,
     who are the end users, and what pain point does it solve?
   - List any ambiguous parts of the problem statement that need
     clarification or assumptions, and state the assumptions clearly.

2. EXISTING SOLUTIONS RESEARCH (web search required)
   - Search for existing apps, startups, government platforms, research
     papers, or open-source projects that solve a similar problem —
     in India and internationally.
   - For each one found, give: name, company/org, country, website,
     what it does, how similar it is to this PS, and what it does NOT cover.
   - Classify overall competition level: 🟢 Fresh space / 🟡 Some
     competition, room to differentiate / 🔴 Crowded space.
   - Do not invent competitors. If nothing comparable is found, say
     "No verified comparable solution identified" — don't claim uniqueness.

3. DIFFERENTIATION ANGLE
   - Based on the research above, suggest 2-3 concrete ways our solution
     could differentiate from what already exists (e.g., a narrower target
     user, a missing feature, a cost/accessibility angle, a regional/
     language focus, an integration existing tools don't have).

4. FEASIBILITY CHECK FOR OUR TEAM
   - Given our team's skills, time, and hardware access listed above,
     rate this PS as 🟢 Highly feasible / 🟡 Feasible with scope reduction /
     🔴 Difficult for us — and explain why in 2-3 sentences.
   - If 🟡 or 🔴, suggest a reduced/MVP scope that IS feasible in our
     timeframe.

5. RECOMMENDED TECH STACK
   - Recommend a specific, practical tech stack for frontend, backend,
     database, AI/ML (if needed), and deployment — matched to our team's
     existing skills where possible.
   - Mention any free/open-source tools, APIs, or public datasets we
     should use (e.g., government open data, Bhashini, Hugging Face
     models, etc.) — only real, verifiable resources.

6. DATA AVAILABILITY
   - Identify what data this solution needs to work.
   - Search for and list any public/open datasets that could be used for
     building or demoing this.
   - If no public dataset exists, suggest a realistic way to generate a
     synthetic or sample dataset for the demo.

7. SYSTEM ARCHITECTURE (high-level)
   - Provide a simple architecture outline (can be text-based or described
     step by step): main components, data flow, and how they connect.
   - Keep it realistic for a hackathon-scale MVP, not an enterprise system.

8. MVP SCOPE FOR THE HACKATHON
   - Define exactly what should be built and demoed within our available
     time — a clear, achievable feature list (not the full vision).
   - Separate into "Must-have for demo" vs "Nice-to-have if time permits"
     vs "Future roadmap (mention in pitch, don't build)."

9. RISKS & CHALLENGES
   - List the top 3-5 realistic risks or blockers for building this
     (technical, data-related, or domain-knowledge related) and how to
     mitigate each.

10. IMPACT & PITCH ANGLE
    - Summarize the real-world impact of this solution in 2-3 sentences
      (who benefits, how, and roughly how significant the problem is) —
      use Low/Medium/High framing, don't invent market-size numbers.
    - Draft a 3-4 sentence "pitch hook" we could open our presentation
      with.

11. SOURCES
    - List all external sources used in this research (official sites,
      docs, GitHub, articles) so we can verify and cite them ourselves.

IMPORTANT RULES:
- Do not hallucinate competitors, statistics, or datasets that don't exist.
- Clearly separate what came from the problem statement I gave you vs what
  you found through web research.
- If information is genuinely unavailable or unverifiable, say so plainly
  instead of guessing.
- Keep the final output in clean Markdown, structured with the section
  headers above, so I can save it directly as a project document.

OUTPUT FORMAT: Clean Markdown file, ready to save as
[PS_ID]_Deep_Research.md
```

---

## ✅ Example (Filled-In Sample)

```
PROBLEM STATEMENT DETAILS:
- PS ID: SIH26131
- Title: Early Detection and Management of Crop Diseases and Pest Infestations
- Organization: Govt of Maharashtra
- Category: Software
- Theme: Agriculture, FoodTech & Rural Development

MY TEAM CONTEXT:
- Team size: 5
- Skills available: 2 ML/CV, 2 web dev (React + Flask), 1 designer
- Time available: 12 days
- Hardware/budget access: None
- Preferred tech stack: Python/Flask backend, React frontend, open to
  ML framework suggestions
```

*(then paste the full RESEARCH TASKS block unchanged)*

---

## 💡 Tips for Best Results

- **Always fill in the full official problem description**, not just the title — vague titles lead to vague/incorrect research.
- **Be honest about your team's skill level** — the AI will give unrealistic recommendations if you overstate your abilities.
- **Run this prompt again after 2-3 days of building** if your scope has changed — the MVP/architecture sections will update to match your actual progress.
- **Save every output** — these become your project documentation and help a LOT when writing the final PPT/report.

---

**Disclaimer:** This is a reusable research-prompt template created independently to help SIH 2026 student teams. It is not an official SIH/AICTE tool. Always validate AI-researched information (competitors, datasets, feasibility) independently before finalizing your submission.
