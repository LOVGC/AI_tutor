# GLOSSARY.md Format

`GLOSSARY.md` is the canonical language of the workspace. All lessons, records, and the map should adhere to its terminology. Building it is itself part of understanding: compressing a concept into a tight definition — *and naming the real thing it points to* — is evidence the user understands it.

Because **names are not knowing**, every entry carries two things: the tight definition, and the real-world referent. If you can't write the referent, you have a label, not knowledge.

## Structure

```md
# {Topic} Glossary

## Terms

**Backpropagation**:
The algorithm that computes the gradient of the loss with respect to every parameter by applying the chain rule backward through the computation graph.
_In the world_: after a forward pass, the error flows backward layer by layer; each weight learns how much it was to blame, and nudges itself to do better next time.
_Avoid_: "the learning algorithm", "the math part"

**Loss**:
A single number measuring how wrong the model's output is on the data.
_In the world_: the score you are trying to push downhill; every adjustment is an attempt to make this number smaller.
_Avoid_: "error" (overloaded), "cost" (use as alias only)
```

## Rules

- **Every term carries its referent.** The `_In the world_` line is the test. If you can only write the definition, the concept isn't understood yet — send it back to step 3 of the method (build the runnable sensory model).
- **Add a term only once it's understood.** The glossary is a record of compressed knowledge, not a dictionary the user reads to learn.
- **Be opinionated.** When several words exist for one concept, pick the best and list the rest as aliases to avoid.
- **Keep definitions tight.** One or two sentences. Define what the term *is*, not how to do it.
- **Use the glossary's own terms inside definitions.** Once a term is in, prefer it everywhere — this is what makes later terms easier to grasp.
- **Group under subheadings** when natural clusters emerge. A flat list is fine when terms cohere.
- **Flag ambiguities explicitly.** If a term is used loosely in the field, note the resolution used in this workspace.
- **Revise as understanding deepens.** Update entries in place; don't leave stale ones.
