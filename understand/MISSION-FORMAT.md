# MISSION.md Format

`MISSION.md` lives at the workspace root. It captures the *reason* the user wants to understand this topic. Every decision — what to explore next, which sources to surface, which lessons to write — should trace back to it.

## Template

```md
# Mission: Understand {Topic}

## Why
{1-3 sentences. Why do you want to understand this? What will a good mental model of it let you think, decide, or see that you can't now? It is fine for the payoff to be understanding itself — but push past "to learn X" to what the understanding unlocks: a decision you'll make better, a thing you'll build, a confusion you want to dissolve, a literature you want to read fluently.}

## Understanding looks like
- {A specific thing you'll be able to explain, picture, or predict}
- {e.g. "I can explain why transformers displaced RNNs without hand-waving"}
- {e.g. "Given a new technique, I can place it on the map and name the delta it adds"}
- {e.g. "I can predict, qualitatively, what happens to X when I change Y"}

## Depth wanted
{How deep? A working intuition to read the field fluently — or deep enough to do original work or build the thing? This bounds how far down the why-chain to go, and where to stop.}

## Constraints
- {Time, prior knowledge, preferred route (top-down vs bottom-up), anything that bounds the approach.}

## Out of scope
- {Adjacent topics you explicitly don't want to chase right now — this protects the zone of proximal development.}
```

## Rules

- **"To understand X" is a valid Why.** Unlike a skills workspace, you don't need a downstream task to justify the mission. But still push past the bare topic to what the understanding unlocks — a vague Why produces abstract, ungrounded learning.
- **Success is explain / picture / predict — not do.** State what the user will be able to *think*, not what they'll be able to *perform*. "I can predict what happens when…" beats "I can build…".
- **Concrete over abstract.** "I can explain why backprop needs differentiable activations" beats "understand neural networks."
- **Push back on vagueness.** If the user cannot articulate why, interview them before writing anything.
- **Revise when reality shifts.** Missions move as understanding grows. Update the file; don't leave a stale mission steering future sessions.
- **Keep it short.** If `MISSION.md` runs past a screen, it has stopped being a compass.
