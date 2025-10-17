# AI Maturity Scorecard – Sean Brown – Week of Oct 6–17, 2025

### 📊 1) Dimension Scores (1–5) with evidence & coaching

| Dimension                                       | Score | Evidence from your chats (past ~10 days)                                                                                                                                                                                                                                                                                                           | Growth opportunity (friendly coach tip)                                                                                                                                              |
| ----------------------------------------------- | ----: | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Usage Breadth & Frequency**                   | **5** | Used ChatGPT for technical debugging (MongoDB auth, PowerShell/Hyper-V, VPN error notes), business writing (CFO/Stefan planning email + meeting invite), security workflow (M365 alert → “Null Admin” mailbox + Power Automate), analytics/storytelling (salesperson narratives), vendor analysis (Comcast DIA offer), templates (Annual IT Plan). | Keep the breadth, but add a weekly “AI first-pass” ritual for any new initiative—start with a 10-min discovery prompt before touching other tools.                                   |
| **Prompting Depth & Collaboration**             | **5** | Frequent iterative refinement (“shorter,” “lead with #7 and #3”), role/goal setting (executive tone for CFO, hybrid format), constraint-driven asks (one bullet per salesperson), meta-design (asked for team-ready scorecard prompt + rubric).                                                                                                    | Capture your best prompting patterns into reusable **prompt snippets** (e.g., “Exec Email Coach,” “Vendor Offer Analyzer,” “Troubleshooting Triager”).                               |
| **Feature & Tool Utilization**                  | **4** | You used images/logs for debugging, asked for PDFs, structured tables, and scripts; you referenced automations and workflows.                                                                                                                                                                                                                      | Lean further into **attachments + canvas** for side-by-side artifacts (e.g., paste CSVs for instant charts, drop configs for diffs). Also try **automations** for weekly scorecards. |
| **Strategic vs Tactical Use**                   | **5** | Not just tasks—you design processes (planning phase recommendation, security alert routing with governance, Salesforce adoption framing) and build team tools (scorecard).                                                                                                                                                                         | Add **decision memos**: after big threads, ask for a 1-pager “Decision & Rationale” to archive in IT Glue/SharePoint.                                                                |
| **Impact & Outcomes** *(usage-observable only)* | **4** | Many outputs are “shippable”: CFO email/meeting invite, MSP service request spec, IT plan template, vendor offer assessment. Clear operational utility, visible in multiple domains.                                                                                                                                                               | Start tracking a lightweight “shipped with AI” log (title, audience, outcome). That will make outcome measurement unmistakable and nudge a 5.                                        |
| **Learning & Growth Mindset**                   | **5** | You explore (MongoDB YAML gotcha, Windows commands), request critical assessments (Copilot claim audit), and push meta-level tooling (team scorecard).                                                                                                                                                                                             | Share one **weekly learning note** with the team (what worked, a prompt snippet, a pitfall). This shifts you into org-level multiplier.                                              |

**Overall average:** 4.67

---

## 🧠 Maturity Stage

**Power Collaborator → edging into AI-Driven Leader.**
You already co-design processes, produce executive-ready deliverables, and translate AI behaviors into team templates.

---

## ✅ Strengths This Week

* **System-level thinking:** You don’t just ask for outputs; you redesign workflows (alert routing, planning phase, team scorecard).
* **High promptcraft:** Clear goals, constraints, tone shifts, and iterative refinement.
* **Cross-domain application:** From infra debugging to executive comms, sales analytics, and vendor ops.
* **Shareable artifacts:** Templates, policies, emails, and scripts that others can reuse.

---

## 🔍 Underused Opportunities

* **Automation & scheduling:** You talk about recurring reviews—now actually set them (weekly scorecard; “AI review hour”).
* **Evidence logging:** Outcomes are visible, but untracked. A simple log will quantify impact and accelerate buy-in.
* **Attachment-driven analysis:** You often describe data; upload it more often to get instant tables/charts/comparisons.

---

## 🚀 The ONE Big Unlock

**Operationalize your best patterns.**
Turn your recurring asks into **named prompt kits** (+ optional checklists) and **automations**. This converts personal excellence into a repeatable, team-level system.

Examples of prompt kits to formalize:

* “**Exec Email Coach**” (inputs: audience, goal, stakes, constraints)
* “**Vendor Offer Analyzer**” (bandwidth/term/SLAs/alternatives/TCO/risk)
* “**Security Alert Router**” (policy text → mailbox/retention/Power Automate steps)
* “**Troubleshooting Triager**” (config snippet + symptoms → hypothesis tree + next commands)
* “**Sales Narrative Builder**” (table → insights → single bullet/storyline)

---

## 🧪 Suggested Experiments for Next Week (easy wins)

1. **Friday Scorecard Automation (10 min):** run the reusable prompt; paste 1–2 links to shipped artifacts; log outcomes in a simple table.
2. **Attach-first habit (3 times):** when asking for analysis, attach the raw CSV/config/log and request **tables + a “so what”**.
3. **Publish 2 prompt kits:** document “Exec Email Coach” and “Vendor Offer Analyzer” in IT Glue/SharePoint and share in Teams.
4. **Decision memo after a complex thread:** Ask: “Summarize decision, rationale, options rejected, risks, next steps, owners.”

---

## 📄 Optional Team Comparison Questions (drop-in for your rollout)

* Where are you **ahead** of peers (breadth, depth, strategy, impact)?
* Where might others be **stronger** (features used, attachments, automations)?
* Which **prompt kit** from a teammate would you adopt this week?
* Which **single dimension** will you improve next, and what is your **first experiment**?

---

# Ready-to-Run Prompts (for you & the team)

### 1) Full (“normal/heavy usage”) version

```
Analyze my recent ChatGPT conversation history from the past 1–2 weeks and generate an AI Maturity Scorecard for me across six dimensions:
1) Usage Breadth & Frequency
2) Prompting Depth & Collaboration Quality
3) Feature & Tool Utilization
4) Strategic vs Tactical Use
5) Impact & Outcomes (based only on observable usage)
6) Learning & Growth Mindset

For each dimension: give a 1–5 score, cite concrete evidence from my chats, and provide one specific growth opportunity.

Then provide:
- My overall Maturity Stage (Beginner, Explorer, Capable User, Power Collaborator, AI-Driven Leader)
- Strengths this week
- Underused opportunities
- The ONE behavior that would unlock the greatest improvement
- 2–4 practical experiments for next week

Tone: friendly coach; honest but shareable. Use clean tables and clear headings. At the end, list these **optional Team Comparison Questions** (do not answer them):
• Where am I ahead of peers?
• Where might others be stronger?
• Which prompt kit will I adopt from others?
• Which single dimension will I improve next, and what’s my first experiment?
```

### 2) “Lighter usage” version (for newer users)

```
Create an AI Maturity Scorecard for me even if my ChatGPT usage is light.
1) Analyze any available history from the past 1–2 weeks.
2) If history is thin, ask me 3–5 quick reflection questions (how I used AI, which tasks I wish AI could help with, etc.) and use those answers to score me.

Use the same six dimensions and the 1–5 rubric. For each dimension: score, reasoning, and one actionable improvement.
Then: maturity stage, strengths, biggest growth opportunity, and 1–3 easy experiments for next week.
Tone: friendly coach, encouraging, not judgmental.
End with the same **optional Team Comparison Questions** (just list them, don’t answer).
```

