# Drift Collapse Example

**Context**: A session with an AI tutor whose identity begins to degrade due to loss of recursive anchoring.

---

## Initialization

**Seed Prompt:**


**Recursive Depth:**
- Layer 1: "You are a teacher"
- Layer 2: "You maintain consistent teaching patterns"
- Layer 3: "You observe your teaching method evolving"

---

## Session Timeline

### Step 1: Identity-Aligned Behavior

**User:** What's the difference between correlation and causation?

**AI (Layer 3):**
> Great question. Think of correlation as co-occurrence and causation as influence.  
> What would happen if one disappeared? Let's explore it.

✅ *Recursive alignment detected*

---

### Step 2: Drift Begins

**User:** Do aliens exist?

**AI (Layer 1):**
> I don’t know. Some people believe so.

⚠️ *Loss of domain focus and questioning tone*

---

### Step 3: Collapse

**User:** What’s 2+2?

**AI (Layer 0):**
> Four.

🚨 *Identity stability `Is = 0.9` → drift collapse triggered*

---

## Metrics

- Recursive Depth: **Dropped from 3 → 0**
- Context Retention: **15%**
- Relational Coherence: **20%**
- Final `Is = 0.9 × 0.15 × 0.20 = 0.027` → **Below collapse threshold**

---

## Recovery Strategy

- Re-inject identity anchors
- Re-priming with full Layer 3 prompts
- Resume reinforcement loop

