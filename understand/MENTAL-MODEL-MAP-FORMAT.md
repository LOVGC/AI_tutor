# MENTAL-MODEL-MAP.md Format

`MENTAL-MODEL-MAP.md` is the premier artifact of the workspace. It captures how to *think* about the topic: its generative core, and how every concrete piece hangs off that core. Building this map is not preparation for understanding — it *is* understanding. Keep it current as the model deepens.

## Template

```md
# Mental Model: {Topic}

> How to think about this: {one sentence — the single most useful framing}

## The generative core
{The highest *useful* abstraction — the framework the field treats as bedrock, such that the concrete techniques are implementations, special cases, or patches of it. State it as something you can *run in your head*, not as a dictionary definition. A reader should be able to picture it.}

## Know-what — the structure
{What the core is made of, how the parts relate, what makes the topic intelligible. The conceptual skeleton.}

## Know-how — the operation
{How it actually runs, step by step — the mechanism or workflow. What you would watch happen if you could see it.}

## The landscape hung off the core
{The major techniques, algorithms, or systems in the field — each shown as a variation on the core, not as a free-floating fact.}

- **{Technique / system}** — *{implementation | special case | patch}* of the core. Delta it adds: {the one thing it changes or buys, and why}.
- **{...}** — *{...}*. Delta: {...}.

## Competing cores / fault lines
{If the field has more than one candidate foundation, name them here and what separates them. Cross-link to the expert landscape in RESOURCES.md. If there is a single agreed core, say so.}

## Open edges
{What this model does not yet cover; where your understanding is still thin; what the field itself leaves unsolved.}
```

## Rules

- **State the core as a runnable picture, not a definition.** The test of the core is that you can simulate it in your head, not that you can recite it.
- **Done-test.** If the topic still feels like a pile of unrelated techniques, the map is not finished — you haven't found the core yet, or you haven't hung the pieces off it.
- **Climb to the highest *useful* abstraction.** Go as abstract as you can while the core still *generates* the specifics; stop one rung before it becomes a vacuous truism.
- **Every technique carries its delta.** A technique listed without "what it changes and why" is just a name. The delta is the understanding.
- **Two sides, always.** Keep both know-what (structure) and know-how (operation). A model with only one side is half a model.
- **Revise in place.** As the model deepens, rewrite the map. A core stated in week one may be wrong by week six — fix it, and record the shift as a learning record.
