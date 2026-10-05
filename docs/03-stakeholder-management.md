# Project Leadership & Stakeholder Management — 6-Hour Project-Ready Course

**A field manual for leading real projects with real people.** One project runs through it all: the **Enterprise Analytics Transformation Project** — replacing manual Excel reporting with Databricks + SQL + Python + Power BI, 16 weeks, fixed deadline/budget, twelve stakeholder groups, an external vendor, and (by Week 10) everything on fire. You know the *technology*; the challenge is the *people*.

> Taught in this chain: analogy → simple explanation → visual → business example → project example → template → role-play → common mistakes → application → cheat sheet.

---
# PART A — FOUNDATIONS

**A1. Core philosophy.** `PROJECT LEADERSHIP ≠ TASK MANAGEMENT`; `PROJECT SUCCESS ≠ JUST DELIVERING ON TIME`. A task manager reads the recipe; a leader is the head chef on a Saturday night when the supplier's late and service is in 40 minutes. `BUSINESS OUTCOME + SCOPE + TIME + COST + QUALITY + PEOPLE + STAKEHOLDERS + RISK + COMMUNICATION = SUCCESS`. **Delivery is not value.**

**A2. Master model (the spine):**
```
BUSINESS OBJECTIVE → PROJECT OUTCOME → SCOPE → STAKEHOLDERS → PEOPLE → PLAN
→ EXECUTION → RISKS/ISSUES/CHANGES → COMMUNICATION → DECISIONS → DELIVERY → BUSINESS VALUE
```

**A3. Task → deliverable → milestone → outcome → benefit.** (Build the dashboard → published dashboard → approved → management monitors in near-real-time → reporting effort down 60%.) Always climb the ladder: "...so that what outcome? ...which delivers what benefit?"

**A4. Manager vs Leader.** Manager: plans, schedules, tracks, documents, follows process. Leader: influences, decides under ambiguity, negotiates trade-offs, resolves conflict, anticipates, motivates, drives the *outcome* — bending process when needed.

**A5. Ownership mindset.** Delete "that's not my responsibility" / "they didn't tell me." Ownership = the outcome stops with you: every gap has an owner, every blocker a path.

**A6. The 5 Questions:** What happened? (facts) · Why? (root cause, not blame) · Impact? · Options? (>1) · Decision/action? (owner, by when). A junior stops at #1; a leader arrives with #1–4 done and #5 as a recommendation.

---
# HOUR 1 — FUNDAMENTALS

**Success constraints (6 levers):** Scope · Time · Cost · Quality · Risk · Resources. **Golden rule:** you cannot optimize everything; fix one, move another, a third must give. Weak leaders say "we'll try"; strong leaders name the trade-off and offer a choice.

**Business vs project objective:** "Reduce monthly reporting effort by 60%" (WHY/money) vs "Implement automated reporting by June 30" (WHAT/WHEN). If the project drifts from the business objective, say so.

**Success criteria — make "done" measurable:** deployed; refresh automated; ≥95% accuracy vs source; users trained & signed off; monthly effort reduced ≥60% (measured 1 month post-launch).

**Scope in vs out.** Out-of-scope is your single most powerful defense against creep (HR analytics, real-time streaming, data >2yrs, custom security). **An undefined boundary is an invitation.**

**Scope creep** = death by a thousand "quick favors." Early signs: verbal hallway requirements, "while you're in there…", features described as if always included, team quietly saying yes. Route every change through a **front door**: `CHANGE REQUEST → IMPACT ANALYSIS (time/cost/resource/risk) → BUSINESS VALUE → DECISION`. Making the cost visible to the requester is the best scope-control tool that exists.

**Charter** (constitution; sponsor = exec who wants the outcome & holds budget; owner/lead = you runs it day-to-day). A project without an engaged sponsor has no air cover.

**Role-play (Week 0 IT Director: "skip the charter, just build"):** acknowledge speed, reframe charter as *protecting* speed, keep it one page, ask for a 90-minute slot. **Mistakes:** building before scope/criteria agreed; no sponsor; charter filed not aligned-on; in-scope defined but not out; accepting "we'll try"; optimizing the project objective over the business objective.

---
# HOUR 2 — STAKEHOLDER MANAGEMENT

A stakeholder can **influence**, is **affected**, or **cares**. Beginner error: treating "the client" as one stakeholder — each box (CEO, CFO, CIO, Security, Ops, users, vendor…) has different fears, success definitions, and power. See all of them, including the quiet ones who sink you late.

**Power/Interest matrix:** Manage Closely (high/high — engage constantly, bring decisions) · Keep Satisfied (high power/low interest — e.g. Security can veto; surface early) · Keep Informed (low power/high interest — users/analysts; champions or saboteurs of adoption) · Monitor. Positions move; re-map every few weeks.

**Register:** Name · Role · Dept · Power · Interest · Influence · Expectations · Concerns · Current Position · Desired Position · Comms Preference · Frequency · Owner · Risk · Strategy. (Example: Security Lead, high power/med interest, can block go-live, currently Resistant → desired Supporter → engage now, co-design controls.)

**Emotional map:** SUPPORTER → NEUTRAL → UNCERTAIN → RESISTANT → OPPOSED. Spend influence where position × power is highest.

**Expectation management:** the quiet killer. `WHAT THEY THINK WE'LL DELIVER — GAP — WHAT WE AGREED`. Close it: say the boundary out loud, early, in writing; read it back; re-confirm on change.

**Stakeholder interview (9 questions):** What does success look like? What problem are we solving? Time/cost/scope/quality priority? Concerns? **What would make this a failure?** (gold — reveals fears = your risk register) Decisions you'll need & when? Info & form? Update cadence? Non-negotiables?

**Communication:** Who? What? Why? When? How? Who delivers? **What action is required?** (most bad comms fail the last). Matrix: CEO monthly 1-page; Sponsor weekly; Team daily standup; Business weekly workshop; Vendor weekly review; Security at each gate. **Not information dumping:** "3 things you need to know · 2 risks · 1 decision I need."

**Executive status format:** Overall 🟢🟠🔴 · what went well · what's at risk · business impact · decisions needed · next steps. Execs want Status · Risk · Impact · Decision · Action — compress so you carry the detail and they carry the decision.

**Role-play (Business Head: "no weekly meetings, just tell me when it's done"):** offer a Friday five-line written update + pull them in only for decisions that are theirs, in return for fast answers on the critical path.

---
# HOUR 3 — PLANNING & EXECUTION

**Planning hierarchy:** PROJECT → PHASES → DELIVERABLES → WORKSTREAMS → TASKS → SUBTASKS (top-down). **WBS** decomposes *what are all the pieces?* before *when?* Break down until each item is estimable and single-owned.

**Milestones** (zero-duration events): Requirements approved → Data pipeline → Dashboards for UAT → UAT sign-off → Production → Business sign-off. Each needs an objective "done" test.

**Dependencies** (internal/external/technical/business/vendor/resource/approval/data) — approval & vendor are most underestimated; manage by starting early and escalating the moment they slip. **Critical path** = longest dependent chain = earliest finish; amateurs treat every delay as equal, leaders triage by the critical path.

**RACI:** R does, A owns (exactly one), C consulted (two-way), I informed. The most valuable thing it does is force "who is the one accountable person?"

**RAID:** Risks (might) · Assumptions (believe, validate) · Issues (have) · Dependencies (waiting-ons).

**Risk vs Issue:** risk → mitigation + contingency; issue → immediate root cause/options/owner/deadline. **Risk register:** Risk · Probability · Impact · Score · Owner · Mitigation · Contingency · Trigger · Status. **Matrix:** prioritize by P×I. **Responses:** Avoid · Mitigate · Transfer (vendor SLA/penalty) · Accept — the key word is *consciously* (with a contingency). **Issue flow:** ISSUE → IMPACT → ROOT CAUSE → OPTIONS → OWNER → DEADLINE → (escalate) → RESOLVE (root cause before options).

**Role-play (BI lead blocked by a moving data model):** make it a *controlled* dependency — freeze the Sales model by end of week, changes via CR; build in parallel against the frozen model meanwhile.

---
# HOUR 4 — DIFFICULT STAKEHOLDERS, CONFLICT & NEGOTIATION

*The most practical hour — difficult people ARE the job.*

**Ten difficult types:** micromanager · angry client · unresponsive · constant changer · unrealistic exec · passive-aggressive · meeting dominator · technical blocker · over-your-head escalator · "I never agreed to this."

**Framework:** DON'T REACT → UNDERSTAND → identify INTEREST → FEAR → POWER → CONSTRAINT → choose response. Difficult behavior is almost always a symptom (the micromanager fears being blindsided; the angry client fears looking bad to *their* boss). Treat the cause, not the symptom.

**Interest vs position (master key):** "I need this dashboard by Friday" → the interest could be a Monday board meeting, fear of embarrassment, a personal commitment, or a regulatory deadline — each points to a *different* solution. You can rarely satisfy a position under constraint; you can often satisfy the interest. Ask *why*, gently, more than once.

**Motivations:** money, time, career, recognition, control, risk-avoidance, fear, compliance, customer impact, political influence, convenience, reputation. Name the driver; frame requests to it.

**Five conflict modes:** Avoid (trivial/too hot) · Accommodate (you're wrong / relationship > point) · Compete (safety/ethics/fast call) · Compromise (equal power, time-pressed) · Collaborate (high stakes, time, ongoing relationship — the ideal). Consciously choose; compete spends relationship capital.

**Conflict resolution:** FACTS → IMPACT → INTERESTS → OPTIONS → AGREEMENT → ACTION. **Difficult conversation:** "I want to make sure we're aligned." → AGREED → CHANGED → IMPACT → OPTIONS → RECOMMENDATION → AGREEMENT.

**Saying no:** convert to a conditional yes with a visible trade-off ("Yes, and here's what it affects…"; "To hold the date we'd drop X — which matters more?"; "Here are three options"). People rarely stay angry at someone who gave them options.

**Negotiation:** POSITION → INTEREST → CONSTRAINT → OPTIONS → TRADE-OFF → AGREEMENT. Honesty about constraints builds negotiating power.

**The 3-option move:** (A) keep scope → move date; (B) keep date → reduce scope/MVP; (C) keep both → add resources/budget (+risk). Stops the argument, respects their authority, makes *them* own the trade-off. The most reusable pattern in the course.

**Escalation (responsible leadership):** Issue · Impact · What you've tried · Options · Recommendation · Decision needed · Deadline · Owner. Don't whine ("they won't cooperate"). **When not to escalate:** within your authority, first-time hiccups, things you haven't tried to solve. Escalating everything burns credibility as fast as escalating nothing.

**Role-play (CFO: "3 extra reports, non-negotiable"):** discover the interest, then 3 options — (A) hold the date + add the 2 that support the board review, defer the 3rd; (B) add all three, move go-live 2 weeks; (C) all three on the date with one more BI dev. Recommend A.

---
# HOUR 5 — LEADERSHIP IN ACTION

**Leadership verbs:** create CLARITY · assign ACCOUNTABILITY · earn TRUST · make DECISIONS · drive COMMUNICATION · close FOLLOW-THROUGH. A set of repeated actions, not a personality.

**Leading without authority:** you're responsible for delivery but don't manage the people (data, BI, IT, Security, vendor). Influence model: CREDIBILITY + RELATIONSHIP + CLARITY + DATA + TRUST + CONSISTENCY. (Your technical background = credibility — use it.)

**Trust:** do what you say; say what you know; admit what you don't; raise risks early; don't hide bad news; give credit; protect the team; follow through. Built in drops, lost in buckets.

**Bad news:** Bad news + Early warning + Impact + Options + Recommendation = leadership. First to raise it, with a plan, looks *more* in control.

**Team:** burnout/overload (you own it — renegotiate scope/date before breaking people), underperformers (private, specific, early; diagnose skill/clarity/capacity/motivation), high performers (growth/recognition or they leave), unclear ownership (RACI + "who owns this?"). **1:1s** catch burnout/blockers/risks before the status report — protect them.

**Meetings:** right type for the need; `PURPOSE · AGENDA · PARTICIPANTS · DECISIONS NEEDED · TIME LIMIT · OWNER · NEXT STEPS`. If you can't state the purpose and decision in one line, send an email. Facilitation: start on time, set context, control discussion, handle dominators, invite the quiet, summarize, assign owner+date, close on time.

**Decisions:** FACTS → CONSTRAINTS → OPTIONS → TRADE-OFFS → RISK → RECOMMENDATION → DECISION; record in a **decision log** (shared memory + "I never agreed" defense). **Assumptions:** validate the high-impact ones early; convert to confirmed facts or active risks.

**Change management (people side):** CURRENT → WHY → FUTURE → IMPACT → RESISTANCE → COMMS → TRAINING → ADOPTION. Taking away people's Excel reports is emotional, not just technical. **Reading resistance:** don't understand→clarify; don't agree→discuss reasoning; don't know how→train; don't want to→personal cost; don't trust→proof+involve; this hurts me→address the fear. **Adoption ladder:** AWARENESS → UNDERSTANDING → ACCEPTANCE → ADOPTION → SUSTAINABILITY. Delivery gets a tool; this ladder gets value.

**Recovery:** STOP → ASSESS → GET FACTS → CRITICAL PATH → PRIORITIZE → FREEZE SCOPE → RESOLVE DEPENDENCIES → REALLOCATE → RECOVERY PLAN → ALIGN → EXECUTE → MONITOR. First move = STOP and get facts; freeze scope early.

**Role-play (exhausted best engineer):** thank them, don't solve by pushing harder, walk through their week, cut/re-sequence, renegotiate scope rather than burn them out.

---
# HOUR 6 — COMPLETE SIMULATION

**Week 10, everything on fire:** requirements changed, data quality poor, vendor 2 wks late, users unhappy, BI overloaded, security pending, CEO wants the original date, CFO wants more, budget frozen.

Six confrontations, each with a leader's move:
- **CEO** ("why isn't it ready?") → ownership + facts + options + recommendation + confidence; lead with the outcome (the 10 dashboards), name the two threats in hand, offer Option 1 (go-live with Sales 80% + fast-follow Finance) or Option 2 (full scope +2wks), recommend 1, ask for one decision. No defensiveness, no jargon dump, no blind over-promise.
- **CFO** ("3 reports") → the 3-option move; discover which report truly matters first.
- **Tech team** ("requirements keep changing") → listen, validate, freeze scope today, CR for everything new, agree this week's top-two, protect them, communicate up.
- **Business user** ("useless") → investigate (requirement/expectation/comms/training gap), don't defend; come back with a fix by a date.
- **Vendor** ("2 more weeks") → interrogate specifically, demand a recovery plan (resource/parallelize/revised milestones), contractual lever if needed, in writing.
- **Executive escalation** → Status + Facts + Impact + Options + Trade-offs + Recommendation + Decision required. Bring a decision, teed up.

**Recovery sequence:** 1 Scope freeze (stop the bleeding) · 2 Critical-path review · 3 Dependency resolution · 4 Parallel workstreams · 5 Resource reallocation · 6 Risk escalation · 7 Daily recovery tracking · 8 Executive communication · 9 Prioritized MVP (80% value) · 10 Recovery milestone.

**RAG with objective criteria:** 🟢 on track ≤5% variance · 🟠 at risk, recovery plan in place, 5–15% · 🔴 off track, >15% or a blocking issue. **Never hide a red project behind green reporting** — watermelon projects always burst.

---
# PART C — TOOLKIT (25 templates)
Charter · Stakeholder Register · Power/Interest Matrix · Communication Matrix · RACI · WBS · Milestone Plan · Dependency Map · RAID · Risk Register · Issue Log · Decision Log · Change Request · Status Report · Steering Pack · Meeting Agenda · Minutes · Action Tracker · Escalation · Conflict Resolution · Negotiation · Executive Communication · Recovery Plan · Lessons Learned · Closure Checklist (measure the 60% effort cut!).

# PART D — CHEAT SHEETS & FORMULAS
- **Stakeholder kit:** Who · care · fear · power · expect · need-from-them · need-from-me · comms format · frequency · next step.
- **Difficult-stakeholder playbook:** angry (let vent, address fear), micromanager (proactive visibility), silent (draw out), unresponsive (make it easy + a deadline), unrealistic (3 options), constant changer (change-request front door), over-your-head escalator (brief your sponsor first), blamer (stay factual, decision log), political (understand interest, low-cost wins), technical blocker (find the real objection, co-own).
- **Conflict modes** · **Escalation** (Problem→Fact→Impact→Options→Recommendation→Decision→Deadline).
- **Leader language (say):** "Let's align on the objective." "Separate facts from assumptions." "What's the business impact?" "What decision do we need?" "Here are the options." "My recommendation is…" "Let's confirm ownership." "I want to raise this risk early."
- **Phrases to delete:** "I don't know." → "I'll find out by [time]." · "That's not my job." → "Let's find the owner." · "We'll try." → "Here's what's possible, and the trade-off." · "Hopefully." → "Here's the risk and how we're managing it." · "There's nothing we can do." → "Here are our options."
- **Formulas:** Bad news = Bad+Early+Facts+Impact+Options+Rec · Say no = Acknowledge+Constraint+Impact+Options+Rec · Exec update = Status→Change→Impact→Risk→Action→Decision · Crisis = Stop→Facts→Impact→Critical-path→Prioritize→Options→Align→Decide→Execute→Monitor→Communicate.
- **10 leadership principles** (bad news early, convert ambiguity to decisions, owner per action, reason per deadline, owner per risk, visible scope-change impact, interest per stakeholder, something-underneath per conflict, clarity per meeting, What/So-what/Now-what per exec update).

# PART E — CAPSTONE (20 weeks; Week-12 crisis)
8 tasks: stakeholder map · recovery plan · 5-min executive presentation · CFO difficult conversation · team conversation · vendor negotiation · steering committee · recovery dashboard with objective RAG criteria.

# PART F — INTERVIEW BANK (95 questions)
Project Management (15) · Stakeholder Management (15) · Leadership (15) · Conflict (10) · Risk (10) · Executive Communication (10) · Scenario-based (20). For each answer: Structure/Leadership/Stakeholder-awareness/Business-thinking/Communication/Practicality (each /10), plus what you did well, what you missed, a better answer, the Senior-PM answer, the Project-Director answer.

# PART G — READINESS SCORECARD (/100)
Project Planning · Stakeholder Management · Communication · Leadership · Risk Management · Decision Making · Conflict Management · Scope Management · Executive Management · Delivery Discipline (each /10). `0–40 Beginner · 41–60 Developing · 61–75 Contributor · 76–85 Lead Ready · 86–95 Strong PM · 96–100 Leadership Ready.`

# THE FINAL MENTAL MODEL
When someone says "we have a problem with the project," you automatically run: What happened? → Business impact? → What's at risk? → Who's affected? → Who owns the decision? → Options? → Trade-offs? → Recommendation? → Now what? → Owner? → By when? → How do we communicate? → How do we prevent recurrence? That reflex — not the terminology — is what makes you project-ready.
