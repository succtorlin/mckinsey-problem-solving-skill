# McKinsey Core Frameworks Reference

---

## 1. MECE Principle

**Definition:** Mutually Exclusive, Collectively Exhaustive. Every breakdown of a problem must have no overlaps (ME) and no gaps (CE).

**Test for ME:** "Can I change one element independently of the others?" If yes, they are mutually exclusive.
**Test for CE:** "Are there any other conditions that must be true to solve the parent problem?" If no, the list is exhaustive.

**Common MECE structures:**
- By geography (North America / Europe / Asia / Rest of World)
- By customer segment (B2B / B2C)
- By value chain stage (Procurement → Production → Distribution → Sales)
- By financial driver (Revenue = Price × Volume; Profit = Revenue − Costs)
- By time (Short-term / Medium-term / Long-term)

**Non-MECE trap:** Listing "pricing," "competition," and "California sales" as separate causes — California is a subset of geography, which overlaps with competition. Fix by using a value chain or geographic hierarchy.

---

## 2. Issue Trees (Logic Trees)

**Definition:** A hierarchical map of all possible causes, drivers, or solutions to a problem. Each level must be MECE. Used to divide and conquer complex problems.

**Three types:**
- **Diagnostic tree (Why?):** Breaks down root causes of a problem. Start with "Why is X happening?" and branch into MECE hypotheses.
- **Solution tree (How?):** Breaks down possible solutions. Start with "How can we achieve X?" and branch into MECE options.
- **Decision tree (Which?):** Breaks down decision criteria. Start with "Which option should we choose?" and branch into MECE evaluation factors.

**Classic profit tree example:**
```
Profit
├── Revenue
│   ├── Price
│   └── Volume
│       ├── Market size
│       └── Market share
└── Costs
    ├── Fixed costs
    └── Variable costs
        ├── Cost per unit
        └── Units produced
```

**Building rules:**
1. Start from the problem statement, not from the data.
2. Each branch must be MECE relative to its parent.
3. Go 3–4 levels deep before prioritizing.
4. Use nouns (not verbs) for branch labels to keep them parallel.

---

## 3. Hypothesis-Driven Approach

**Definition:** Form an educated hypothesis about the answer before conducting analysis. Then design the minimum analysis needed to prove or disprove it. Opposite of "boil the ocean."

**Process:**
1. Define the problem clearly.
2. Form an initial hypothesis: "We believe X is the primary cause because Y."
3. Identify the 2–3 key analyses that would prove or disprove the hypothesis.
4. Conduct only those analyses.
5. If disproved, update the hypothesis and repeat.

**Why it matters:** Prevents teams from analyzing everything and finding nothing. Forces early commitment to a direction, which can be updated with evidence.

**Hypothesis vs. observation:**
- Observation: "Revenue declined 15% last year."
- Hypothesis: "Revenue declined because of pricing pressure from a new competitor, not volume loss."

---

## 4. Pyramid Principle (Minto Pyramid)

**Definition:** Developed by Barbara Minto at McKinsey. Structure all communication top-down: lead with the answer, then support it with arguments, then support each argument with data.

**Structure:**
```
Governing Thought (Answer / Recommendation)
├── Key Line Argument 1
│   ├── Supporting data / evidence
│   └── Supporting data / evidence
├── Key Line Argument 2
│   ├── Supporting data / evidence
│   └── Supporting data / evidence
└── Key Line Argument 3
    ├── Supporting data / evidence
    └── Supporting data / evidence
```

**Rules:**
- Ideas at each level summarize the ideas below them.
- Ideas in each group are the same kind of idea.
- Ideas in each group are always logically ordered (deductive or inductive).

**Deductive reasoning:** A → B → C → Therefore D. Use when the logic chain is tight and the audience is analytical.
**Inductive reasoning:** A, B, C are all true → Therefore D. Use when presenting multiple independent supporting points.

---

## 5. SCQA Framework (Situation, Complication, Question, Answer)

**Definition:** The narrative structure for opening any communication. Sets context, creates tension, poses the question, and delivers the answer.

| Element | Purpose | Example |
|---|---|---|
| **Situation** | Establish shared context the audience already agrees with | "Our company has been the market leader for 10 years." |
| **Complication** | Introduce the tension or change that disrupts the situation | "However, a new competitor entered last year and we lost 5 points of market share." |
| **Question** | The question the complication naturally raises | "What should we do to defend our position?" |
| **Answer** | The governing thought / recommendation | "We should invest in product innovation and targeted pricing to recover share within 18 months." |

**Key insight:** The SCQA creates a "story hook" that makes the audience want to hear the answer. Never lead with data — lead with the situation.

---

## 6. The "So What?" Test

**Definition:** After every analysis, ask: "So what does this mean for the decision maker?" If you cannot answer that question, the analysis is incomplete.

**Three-part So What:**
1. **Key takeaway:** Is this result good or bad? Expected or surprising? How does it compare to benchmarks?
2. **Root cause:** Why are we seeing this? What are the 2–3 most likely hypotheses?
3. **Implication:** What happens if we do nothing? What action does this finding recommend?

**Example:**
- Summary (bad): "Our close rate is 50%."
- Synthesis with So What (good): "Our close rate dropped from 60% to 50% — a concerning trend likely driven by lower sales productivity and increased competitor pressure. If unaddressed, we will lose 3–5 points of market share within 12 months."

---

## 7. Ghost Deck (Skeleton Deck)

**Definition:** A slide outline where each slide has a title (the "so what" headline), a placeholder for the visual, and a note on the analysis needed. Built before any analysis is done.

**Purpose:** Forces the team to agree on the story and the analyses needed before anyone starts working. Prevents wasted analysis.

**Ghost deck process:**
1. Write the recommendation in one sentence (the governing thought).
2. Identify 3–5 supporting arguments (these become section headers).
3. For each argument, write the "so what" headline for each slide.
4. Note what analysis or data is needed to prove each headline.
5. Assign analyses to team members.

**Rule:** Every slide title must be a complete sentence that conveys the insight, not just a topic label.
- Bad title: "Revenue Analysis"
- Good title: "Revenue declined 15% due to pricing pressure, not volume loss"

---

## 8. Prioritization Matrix (Impact vs. Effort / Feasibility)

**Definition:** After building an issue tree, prioritize which branches to investigate first based on two dimensions: (1) potential impact on the answer, and (2) ability to influence or change.

**Prioritization criteria:**
- **Size of the prize:** How much does this lever affect the outcome?
- **Movability:** Can we actually change this lever?
- **Speed:** How quickly can we get data or implement a change?
- **Confidence:** How certain are we that this is a real issue?

**McKinsey rule:** Focus on levers that are both large and movable. Avoid spending time on levers that are large but immovable (e.g., macroeconomic conditions) or small but easy to change.

---

## 9. The 80/20 Rule (Pareto Principle) in Consulting

**Definition:** 80% of the value comes from 20% of the work. McKinsey consultants are trained to identify the 20% of analyses that will generate 80% of the insight.

**Application:**
- In issue trees: Focus on the 2–3 branches most likely to contain the answer.
- In data analysis: Identify the 3–5 key metrics that drive the outcome.
- In recommendations: Identify the 1–2 actions that will have the most impact.

**Practical implication:** Never "boil the ocean." Always ask: "What is the minimum analysis I need to prove or disprove my hypothesis?"

---

## 10. Problem Statement Crafting

**Definition:** A precise, action-oriented statement of what needs to be decided or solved. The most important step in the McKinsey process — getting this wrong wastes all subsequent work.

**Good problem statement criteria:**
- Contains an action verb (decide, determine, identify, assess)
- Specifies the decision maker and their constraints
- Defines the scope (what is in and out of bounds)
- Is specific enough to be falsifiable

**Template:** "[Action verb] [what] for [whom] by [when] given [constraints], in order to [desired outcome]."

**Example:**
- Bad: "Can we grow in Japan?"
- Good: "Determine whether to enter the Japanese market with our premium product line within 18 months, given a $50M investment cap, in order to achieve 5% market share by Year 3."
