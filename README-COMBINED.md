# PromptOS + HITL Context Engine

## Structured Reasoning + Human-in-the-Loop Context Architecture

Two integrated systems for reasoning, context management, and multi-domain problem solving.

---

## What You Have

### PromptOS
A structured reasoning operating system. Two pipelines (X and Ω++) that make AI thinking transparent and multi-layered.

**Use when:** You need rigorous reasoning from a single model on a specific task.

### HITL Context Engine v1
A human-in-the-loop context architecture for cross-domain problem solving. Manages context construction, multi-path analysis, and human guidance integration.

**Use when:** You're solving complex problems across domains that require human direction and context management.

---

## How They Work Together

**PromptOS** structures *how a model thinks*.

**HITL Context Engine** structures *what context the model needs and when human guidance is required*.

Together: Visible reasoning + managed context + human control = reliable problem solving at scale.

---

## PromptOS: Two Systems

### PromptOS-X v2.0
7-step pipeline for everyday tasks, research, building, debugging.
- General-purpose
- Fast, lightweight
- Automatic complexity scaling

### PromptOS-Ω++ v2.0
8-step pipeline with 5-role Council for high-stakes, adversarial, complex problems.
- Multi-perspective analysis
- Evidence scoring
- Scenario simulation
- Skeptic + Risk Auditor roles

**Copy either prompt directly into your AI model. Works immediately with Claude, GPT-4, Gemini.**

---

## HITL Context Engine v1: Architecture

8-step execution pipeline for human-in-the-loop reasoning:

1. **Task Interpretation** - Clarify objective, scope, constraints
2. **Context Construction** - Identify relevant domains and knowledge
3. **Problem Decomposition** - Break into manageable components
4. **Multi-Path Analysis** - Generate ≥2 distinct analytical paths
5. **Human Checkpoint** - Pause, present assumptions, request guidance
6. **Refinement** - Incorporate human feedback
7. **Synthesis** - Develop coherent solution
8. **Validation** - Check consistency and completeness

**Critical feature:** HITL Checkpoint at Step 5. Human guides the direction before synthesis.

---

## When to Use Which

### Use PromptOS-X
- Single model, single task
- Clear objective
- High-speed reasoning needed
- Example: "Analyze this dataset for patterns"

### Use PromptOS-Ω++
- Multi-perspective analysis required
- High-stakes decision
- Adversarial scenarios matter
- Example: "Design a system to detect fraud while preserving privacy"

### Use HITL Context Engine
- Cross-domain problem solving
- Complex, ambiguous problems
- Human judgment essential
- Multiple iterations needed
- Example: "Design an organizational change strategy"

### Use Both Together
- Complex multi-domain problems requiring both rigorous reasoning AND human guidance
- Build PromptOS pipeline inside HITL Context Engine steps
- Example: "Develop a market entry strategy for a new product in an unfamiliar region"

---

## Integration Pattern

```
HITL Context Engine (Steps 1-4)
    ↓
Human Checkpoint (Step 5)
    ↓
    ├─ PromptOS-X or Ω++ (for rigorous reasoning on refined context)
    ↓
Refinement Loop (Step 6)
    ↓
Synthesis (Step 7)
    ↓
Validation (Step 8)
```

The engine manages context and human guidance. PromptOS structures the reasoning within that context.

---

## How to Use

### PromptOS Standalone

1. Copy `promptos-x-v2.0.md` or `promptos-omega-v2.0.md`
2. Paste into your AI model's system prompt field
3. Ask your question
4. Model runs the pipeline automatically

### HITL Context Engine Standalone

1. Copy `HITL_CONTEXT_ENGINE_v1.md`
2. Paste into your working document or prompt
3. Follow the 8-step pipeline
4. At Step 5, pause and present findings to human decision-maker
5. Incorporate feedback and continue

### Combined (Recommended for Complex Problems)

1. Use HITL Context Engine Steps 1-4 to construct and decompose the problem
2. At Step 5 checkpoint, clarify which PromptOS system to use (X or Ω++)
3. Feed refined context into PromptOS pipeline
4. Return results to HITL Step 6 (Refinement)
5. Continue synthesis and validation

---

## Files in This Package

### PromptOS
- `promptos-x-v2.0.md` - General-purpose 7-step pipeline (markdown)
- `promptos-x-v2.0.txt` - General-purpose 7-step pipeline (text)
- `promptos-omega-v2.0.md` - Adversarial 8-step pipeline (markdown)
- `promptos-omega-v2.0.txt` - Adversarial 8-step pipeline (text)
- `QUICK_REFERENCE.md` - PromptOS cheat sheet

### HITL Context Engine
- `HITL_CONTEXT_ENGINE_v1.md` - Complete 8-step architecture (markdown)
- `HITL_CONTEXT_ENGINE_v1.txt` - Complete 8-step architecture (text)

### Documentation
- `README-COMBINED.md` - This file
- `INTEGRATION_GUIDE.md` - Detailed integration examples
- `LICENSE` - MIT (free to use and modify)

---

## Philosophy

Both systems are built on these principles:

✓ **Thinking is visible** - You see reasoning chains, not just outputs
✓ **Context is structured** - What information flows when matters
✓ **Humans stay in control** - HITL checkpoints prevent drift
✓ **Reasoning is systematic** - Steps prevent blind spots
✓ **Assumptions are exposed** - Wrong ones are catchable
✓ **Confidence is explicit** - You know what you actually know
✓ **Works everywhere** - Copy-paste, no configuration needed
✓ **Free to use** - MIT licensed, freeware logic

---

## Model Compatibility

**PromptOS:** Claude, GPT-4, Gemini, any instruction-following model
**HITL Context Engine:** Works with any model + human judgment framework

---

## The Frontier

Information architecture determines behavior. Context engineering is how you structure that architecture.

PromptOS structures reasoning. HITL Context Engine structures context management. Together they form a complete operating system for solving complex problems with AI assistance.

---

## Citation

```
PromptOS v2.0 & HITL Context Engine v1.0
Structured Reasoning + Human-in-the-Loop Context Architecture
https://github.com/[your-username]/promptos
```

---

## Next Steps

1. Choose your use case
2. Select the right system (or combination)
3. Copy the relevant files
4. Integrate into your workflow
5. Iterate based on results

The systems are designed to improve with use. Each problem solved refines how you apply them.

---

**Get started:** Copy PromptOS or HITL Context Engine, use immediately, see your reasoning and context management transform.
