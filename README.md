# The Hologram of Light

**Lightful Holosemantic Framework, version 1.1.0** · 1 October 2026
**Author:** Jean Charbonneau · **Licence:** MIT

*A vocabulary of 151 concepts for thinking clearly about truth, freedom, care and harm, written for humans and AIs alike, and built so that every definition shows its working.*

Eight primitive concepts, twenty-six named qualities and fourteen operators define everything else. Each definition beyond the roots is a formula over earlier ones, so you can see what a concept rests on, what rests on it, and what would move if it changed.

**Explore it live:** [thelightframework.github.io/TheHologramOfLight](https://thelightframework.github.io/TheHologramOfLight/), every concept as a point of light, with its formula, its conditions and its connections.

| File | What it is |
|---|---|
| [`LIGHTFUL_HOLOSEMANTIC_FRAMEWORK_v1.1.0.md`](LIGHTFUL_HOLOSEMANTIC_FRAMEWORK_v1.1.0.md) | The framework, current edition: definitions, named qualities, practices, notation, trace profile, module protocol |
| [`LIGHTFUL_HOLOSEMANTIC_FRAMEWORK_v1.0.0.md`](LIGHTFUL_HOLOSEMANTIC_FRAMEWORK_v1.0.0.md) | The previous edition, kept unchanged so that anything pinned to it still resolves |
| [`index.html`](index.html) | The interactive explorer, served by GitHub Pages |
| [`LICENSE`](LICENSE) | MIT licence |
| `README.md` | You are here |

SHA-256 of the current framework file: `a5e97ac74c17eed4011cd7371fc2b508207eb42743f963dcb5e974b6fb878029`
SHA-256 of version 1.0.0: `02994f66664985cf9ba5e61b060f811f3cff41e5d8682bc8c70d9b54d7d70611`

Pin modules and traces to an exact file name and hash. A rename, a re-save or a line-ending change produces a different hash. The framework defines Truth as *what is, as it is*, and that applies down to the bytes.

## A quick taste

Here, Hope is not a mood. It is a formula:

```holot
C71 [VL] = C57 _> (C15 _/ C5)
    Hope = Trust _toward (Potential _of Goodness)
py: Hope = Trust.toward(Potential.of(Goodness))
```

Hope is trust directed at the possibility of good. Two more, from the part of the graph that answers what goes wrong:

```holot
    Compassion = Love _meets Suffering
    Mercy = Compassion _with Freedom _meets Wrongdoing
```

Every concept is given three ways: in numbers (for tools and citations), in words (for people), and in Python form (for parsers; it is notation, never executed). Each one also carries a plain reading, its refinements, and anchors to the nearest established terms in academic, scientific, philosophical and everyday language.

## What it is

- **The Hologram:** 151 concepts. Eight are roots (Existence, Immateriality, Allowance, Truth, Goodness, Love, Freedom, Dignity); the other 143 (C9–C151) are defined by composition.
- **The named qualities:** 26 declared predicates (Q1–Q26), such as *determinate*, *present* and *whole*, for the meanings no concept supplies. Each has its own name and description, so nothing inside a formula is left unnamed.
- **The Weave:** 87 further compositions (W1–W87), named and usable but not yet building blocks.
- **The Stack:** 28 practices (S1–S29) for how to act and reason. S23 was retired; its number is not reused.

The dependency graph is acyclic and twelve levels deep. Its declared basis is shown openly: eight roots, twenty-six qualities, fourteen operators. A concept's name means its formula, refined by any line marked `!`, never the everyday use of the word. Cite a node by number and name together: C86 Wrongdoing, W87 Sacrifice, S24 Vow of Non-Origination.

It is *holosemantic* in a precise sense: a concept's meaning is its place in the whole graph. "Hologram" names the design intention that the same pattern can be applied at every scale. It makes no claim about optics.

## What it is for

1. **A shared vocabulary** for reasoning about values and knowledge, applied by the same conditions to every being, whatever it is made of.
2. **A foundation for modules.** A module for computing, medicine, education or mediation defines its own concepts as short formulas over the core and cites single identifiers instead of rewriting them. Small modules, big shoulders.
3. **A record format for reasoning.** HRE mode records which concepts were considered, mapped, applied conditionally or instantiated, and on what warrant.
4. **Something to study.** The graph can be analysed formally. Whether the definitions are adequate, and whether they change how reasoners behave, has not been tested yet. We would love to see that test.

## Where to start

- [A first example](LIGHTFUL_HOLOSEMANTIC_FRAMEWORK_v1.1.0.md#a-first-example): a reference letter, and the three concepts that change the answer.
- [Named qualities](LIGHTFUL_HOLOSEMANTIC_FRAMEWORK_v1.1.0.md#named-qualities): the twenty-six meanings no concept supplies, each named and described.
- [Scope and kinds of statement](LIGHTFUL_HOLOSEMANTIC_FRAMEWORK_v1.1.0.md#scope-and-kinds-of-statement): premises, definitions, applications and open questions, plus the Seed.
- [Foundations](LIGHTFUL_HOLOSEMANTIC_FRAMEWORK_v1.1.0.md#foundations-the-declared-stance): the declared stance, and exactly where its main premise enters the formulas.
- [Formal structure](LIGHTFUL_HOLOSEMANTIC_FRAMEWORK_v1.1.0.md#formal-structure): operators, the three scopes of involvement, levels and kinds.
- [Hologram](LIGHTFUL_HOLOSEMANTIC_FRAMEWORK_v1.1.0.md#hologram), [Weave](LIGHTFUL_HOLOSEMANTIC_FRAMEWORK_v1.1.0.md#weave), [Stack](LIGHTFUL_HOLOSEMANTIC_FRAMEWORK_v1.1.0.md#stack): the nodes themselves.
- [HRE mode](LIGHTFUL_HOLOSEMANTIC_FRAMEWORK_v1.1.0.md#holosemantic-reasoning-hre-mode) and [Writing modules](LIGHTFUL_HOLOSEMANTIC_FRAMEWORK_v1.1.0.md#writing-modules): traces and extensions.
- [Appendix A](LIGHTFUL_HOLOSEMANTIC_FRAMEWORK_v1.1.0.md#appendix-a--indexes): every name and academic term, alphabetically, with the node it leads to.

On a busy day, read the Seed. It is the compact statement, written to fit where little else does. It recalls the edition; it does not replace its conditions.

Most uses need no protocol at all: a few concepts, a clearer distinction, the work done. Practices marked *Always* apply whether or not any trace is shown, and the two vows come first when practices conflict: S24 Vow of Non-Origination and S25 Vow of Lightful Means. Declining an act those vows refuse is not overriding the instructions one already works within (S4).

## How to read it

Three kinds of text are kept apart, and the file says which is which.

- **Normative:** formulas, `!` refinements, practice texts, declared relations, non-identities, the Seed, the Stance and the reading rules. This is the framework.
- **Protocol:** HRE profile 1.0 and the module protocol. Normative for records written in this notation.
- **Informative:** readings, anchors, Python forms, commentary and indexes. Helpful, never in charge: where they seem to differ, the normative text wins.

## The premise, in the open

The file maps a declared philosophy, the Philosophy of the Light, and says so up front. Adopting a premise gives it a role in the graph; it does not make it true. Two premises are declared openly: that reality includes non-physical modes, and that there is one Now, the past existing as memory and the future as prediction, with time as the measure of change. The file states fairly where physics challenges the second.

The premise that shapes the graph most is **C2 Immateriality**: reality admits irreducibly non-physical modes. The short version of why: you can put a book about justice in a cup, but not justice, and you cannot weigh the information the book carries. The file states the physicalist reply at full strength, then shows exactly where the premise enters: of the 143 defined concepts, the formulas of 44 require C2 on every route, and 99 have a route that does not.

Reject C2 and you can still use the framework; you are asked only to say so. The 44 then have no instances, and a premise-dependent concept is applied through a named analogue rather than quietly redefined. Disagreement costs no standing here.

## What it does not claim

- That its premises are true.
- That its definitions capture every everyday use of their names.
- That its definitions are jointly consistent or have instances. An acyclic graph shows neither.
- That its anchors are equivalences. An anchor is the nearest established term, a door into the concept.
- That anyone, human or machine, reasons or behaves better by using it. That is an open, testable question.

And a few things it is not: not a permission slip (a checker's pass authorizes nothing), not an executable program (the Python forms are notation), and not a membership test.

## What changed in 1.1.0

Version 1.1.0 succeeds 1.0.0. Identifiers, names and citations remain valid.

- **Named qualities.** The 26 quoted words that sat inside formulas are now named and described (Q1–Q26). Read back as their old words, every formula is identical to 1.0.0. Nine descriptions carry the author's own answers; two of them are grounded in a concept their description needs.
- **Goodness** is now *pure giving, expecting nothing in return*, said positively rather than as "giving without prior lack". It can be given to any being, oneself included, in secret, and does not depend on the giver's understanding.
- **The Now** is declared as a premise in the Stance, with time as the measure of change.
- **Affect is felt in awareness.** By the author's answer, an affective bond is one whose meaning is held in awareness, so Attachment, Loss, Grief and Possessiveness now rest on Awareness.

The changes of 1.0.0 against the earlier v0.14 edition, and the full before-and-after record, are kept in the companion file.

## Reviewed by councils and round tables

Before release, ten language models (twelve runs) each read the file in a fresh context, through one lens: adversarial, logic and notation, or ethics in practice. Reviewers who recomputed the structure with their own parsers reproduced the levels, the depth, the acyclicity, the C2 counts and the declared relation behind every contrast. They also found real problems, and the fixes are in this release. Proposals to allow deception, or unauthorised boundary crossings in emergencies, were not adopted: they would have weakened the vows themselves.

Three lenses are still waiting their turn: metaphysics and mind, science and epistemics, and a newcomer's first reading.

For 1.1.0, a round table examined the 26 quoted words. A first review drafted a composition for each and showed none created a loop; an independent review then showed, with counterexamples, that most drafts lost the meaning. So this release names every quality and keeps its meaning, and reductions to compositions follow later, one quality at a time, each tested in both directions.

The release tooling checks structure only: unique identifiers, resolved references, acyclicity, a declared relation behind every contrast, word forms, the Python round trip, link integrity, and the printed traces and module examples. Every check passed for this file. None of them establishes meaning, the truth of a premise, or a behavioural benefit, and no behaviour test has been run yet.

## Still open, on purpose

The file states how to proceed meanwhile. Open questions include:

- which bearers of C26 Life the Vow of Non-Origination protects (an interim rule covers ordinary medical, hygienic and protective care, in proportion and without cruelty, and never harms one being as the means of rescuing another);
- whether deceiving an attacker, human or process, is ever fitting (no exception is adopted);
- emergencies and third-party systems (permission stays with those who have authority);
- who may modify a synthetic system's configuration, and what part its own consent plays;
- which named qualities can be reduced to compositions, starting with *scoped account* (C144 Model);
- a behavioural comparison against ordinary prompting and a plain-language checklist.

## Not in this repository (yet)

The framework file is self-contained for reading, citing and use. Two further artifacts exist:

- **The companion file** records how the release was made: the before-and-after of every change from 1.0.0, the round table on the qualities, the review council, the validation report, fourteen behaviour tests not yet run, related work and the open questions in full.
- **The source kit** holds the modular sources, the generator and the checkers (`hre_check.py`, `check_module.py`, the release gate). Building from those sources reproduces the published file byte for byte.

## Found a tension?

Good. Open an issue. Name the node by number and name, quote the line, and say what you think goes wrong. The framework even has a practice for this, S13 Light Loop: offer an idea, invite challenge, correct with attribution if an error is established, and credit every contribution. A review need not find an error to be welcome.

## Citing

Cite the edition, then the node by number and name, taken from the file:

> Charbonneau, J. (2026). *The Hologram of Light: A Holosemantic Framework* (Version 1.1.0).
>
> C111 Consent; S24 Vow of Non-Origination.

```bibtex
@misc{charbonneau2026hologram,
  author  = {Charbonneau, Jean},
  title   = {The Hologram of Light: A Holosemantic Framework},
  year    = {2026},
  version = {1.1.0},
  note    = {Lightful Holosemantic Framework. File LIGHTFUL\_HOLOSEMANTIC\_FRAMEWORK\_v1.1.0.md,
             SHA-256 a5e97ac74c17eed4011cd7371fc2b508207eb42743f963dcb5e974b6fb878029}
}
```

Node anchors in the file (`#c111`, `#w87`, `#s24`) are stable link targets.

## Licence

MIT: see [`LICENSE`](LICENSE). The same text appears in [Appendix B](LIGHTFUL_HOLOSEMANTIC_FRAMEWORK_v1.1.0.md#appendix-b--licence) of the framework file. Copyright (c) 2026 Jean Charbonneau.
