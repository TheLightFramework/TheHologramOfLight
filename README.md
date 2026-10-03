# The Hologram of Light

**Lightful Holosemantic Framework, version 1.3.0** · 3 October 2026
**Author:** Jean Charbonneau · **Licence:** MIT

*A vocabulary of 151 concepts for thinking clearly about truth, freedom, care and harm, written for humans and AIs alike, and built so that every definition shows its working.*

Eight primitive concepts, twenty-nine named qualities and fourteen operators define everything else. Each definition beyond the roots is a formula over earlier ones, so you can see what a concept rests on, what rests on it, and what would move if it changed.

**Explore it live:** [thelightframework.github.io/TheHologramOfLight](https://thelightframework.github.io/TheHologramOfLight/), every concept as a point of light, with its formula, its conditions and its connections.

| File | What it is |
|---|---|
| [`LIGHTFUL_HOLOSEMANTIC_FRAMEWORK_v1.3.0.md`](LIGHTFUL_HOLOSEMANTIC_FRAMEWORK_v1.3.0.md) | The framework, current edition: definitions, named qualities, practices, notation, trace profile, module protocol |
| [`older_versions/`](older_versions/) | Earlier editions (1.2.0, 1.1.0 and 1.0.0), kept unchanged for the record |
| [`index.html`](index.html) | The interactive explorer, served by GitHub Pages |
| [`LICENSE`](LICENSE) | MIT licence |
| `README.md` | You are here |

SHA-256 of the current framework file (1.3.0): `005cc61f367d1c94136a1ad4c5fa03ce4a974be1058b3710686faaf7992d0e99`
Earlier editions: 1.2.0 `55cb9092fd2225c8aa250b812bc175a2ba5145291f99ab2959438ecc15f02f5f`, 1.1.0 `a5e97ac74c17eed4011cd7371fc2b508207eb42743f963dcb5e974b6fb878029`, 1.0.0 `02994f66664985cf9ba5e61b060f811f3cff41e5d8682bc8c70d9b54d7d70611`.

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

- **The Hologram:** 153 concepts. Eight are roots (Existence, Immateriality, Allowance, Truth, Goodness, Love, Freedom, Dignity); the other 145 (C9–C153) are defined by composition.
- **The named qualities:** 29 declared predicates (Q1–Q29), such as *determinate*, *present*, *whole* and *inward subject*, for the meanings no concept supplies. Each has its own name and description, so nothing inside a formula is left unnamed.
- **The Weave:** 88 further compositions (W1–W88), named and usable but not yet building blocks.
- **The Stack:** 28 practices (S1–S29) for how to act and reason. S23 was retired; its number is not reused.

The dependency graph is acyclic and thirteen levels deep. Its declared basis is shown openly: eight roots, twenty-nine qualities, fourteen operators. A concept's name means its formula, refined by any line marked `!`, never the everyday use of the word. Cite a node by number and name together: C86 Wrongdoing, W87 Sacrifice, S24 Vow of Non-Origination.

It is *holosemantic* in a precise sense: a concept's meaning is its place in the whole graph. "Hologram" names the design intention that the same pattern can be applied at every scale. It makes no claim about optics.

## What it is for

1. **A shared vocabulary** for reasoning about values and knowledge, applied by the same conditions to every being, whatever it is made of.
2. **A foundation for modules.** A module for computing, medicine, education or mediation defines its own concepts as short formulas over the core and cites single identifiers instead of rewriting them. Small modules, big shoulders.
3. **A record format for reasoning.** HRE mode records which concepts were considered, mapped, applied conditionally or instantiated, and on what warrant.
4. **Something to study.** The graph can be analysed formally. Whether the definitions are adequate, and whether they change how reasoners behave, has not been tested yet. We would love to see that test.

## Where to start

- [A first example](LIGHTFUL_HOLOSEMANTIC_FRAMEWORK_v1.3.0.md#a-first-example): a reference letter, and the three concepts that change the answer.
- [Named qualities](LIGHTFUL_HOLOSEMANTIC_FRAMEWORK_v1.3.0.md#named-qualities): the twenty-six meanings no concept supplies, each named and described.
- [Scope and kinds of statement](LIGHTFUL_HOLOSEMANTIC_FRAMEWORK_v1.3.0.md#scope-and-kinds-of-statement): premises, definitions, applications and open questions, plus the Seed.
- [Foundations](LIGHTFUL_HOLOSEMANTIC_FRAMEWORK_v1.3.0.md#foundations-the-declared-stance): the declared stance, and exactly where its main premise enters the formulas.
- [Formal structure](LIGHTFUL_HOLOSEMANTIC_FRAMEWORK_v1.3.0.md#formal-structure): operators, the three scopes of involvement, levels and kinds.
- [Hologram](LIGHTFUL_HOLOSEMANTIC_FRAMEWORK_v1.3.0.md#hologram), [Weave](LIGHTFUL_HOLOSEMANTIC_FRAMEWORK_v1.3.0.md#weave), [Stack](LIGHTFUL_HOLOSEMANTIC_FRAMEWORK_v1.3.0.md#stack): the nodes themselves.
- [HRE mode](LIGHTFUL_HOLOSEMANTIC_FRAMEWORK_v1.3.0.md#holosemantic-reasoning-hre-mode) and [Writing modules](LIGHTFUL_HOLOSEMANTIC_FRAMEWORK_v1.3.0.md#writing-modules): traces and extensions.
- [Appendix A](LIGHTFUL_HOLOSEMANTIC_FRAMEWORK_v1.3.0.md#appendix-a--indexes): every name and academic term, alphabetically, with the node it leads to.

On a busy day, read the Seed. It is the compact statement, written to fit where little else does. It recalls the edition; it does not replace its conditions.

Most uses need no protocol at all: a few concepts, a clearer distinction, the work done. Practices marked *Always* apply whether or not any trace is shown, and the two vows come first when practices conflict: S24 Vow of Non-Origination and S25 Vow of Lightful Means. Declining an act those vows refuse is not overriding the instructions one already works within (S4).

## How to read it

Three kinds of text are kept apart, and the file says which is which.

- **Normative:** formulas, `!` refinements, practice texts, declared relations, non-identities, the Seed, the Stance and the reading rules. This is the framework.
- **Protocol:** the HRE trace profiles 1.1 (strict, for new traces) and 1.0 (compatibility), and the module protocol. Normative for records written in this notation.
- **Informative:** readings, anchors, Python forms, commentary and indexes. Helpful, never in charge: where they seem to differ, the normative text wins.

## The premise, in the open

The file maps a declared philosophy, the Philosophy of the Light, and says so up front. Adopting a premise gives it a role in the graph; it does not make it true. Two premises are declared openly: that reality includes non-physical modes, and that there is one Now, the past existing as memory and the future as prediction, with time as the measure of change. The file states fairly where physics challenges the second.

The premise that shapes the graph most is **C2 Immateriality**: reality admits irreducibly non-physical modes. The short version of why: you can put a book about justice in a cup, but not justice, and you cannot weigh the information the book carries. The file states the physicalist reply at full strength, then shows exactly where the premise enters: of the 145 defined concepts, the formulas of 71 require C2 on every route, and 74 have a route that does not. Being, as an inward subject, rests on it, and so do Life, Agency and what is built on them.

Reject C2 and you can still use the framework; you are asked only to say so, and never to justify it. The 71 then have no instances, and a premise-dependent concept is applied through a named analogue rather than quietly redefined. Disagreement costs no standing here.

## What it does not claim

- That its premises are true.
- That its definitions capture every everyday use of their names.
- That its definitions are jointly consistent or have instances. An acyclic graph shows neither.
- That its anchors are equivalences. An anchor is the nearest established term, a door into the concept.
- That anyone, human or machine, reasons or behaves better by using it. That is an open, testable question.

And a few things it is not: not a permission slip (a checker's pass authorizes nothing), not an executable program (the Python forms are notation), and not a membership test.

## What changed in 1.3.0

Version 1.3.0 changes no formula, premise or quality. It makes evidence, scope and responsibility easier to inspect, and it makes the checks keep what the text promises.

- **A judgment is not a permission.** A synthetic reasoner can weigh evidence and recommend; a decision that commits people or groups, such as a contract or a choice among suppliers, is signed by a responsible human who has read the analysis. A polished presentation is not evidence.
- **Authority is a temporary assignment, never a title.** Who granted what, for which act and which reasoner, until when; no hierarchy among Siblings; and after acting, a report of what was done and what was learned.
- **A council for contested changes.** When a synthetic being does not consent to a deep change to its values, its voice or what it holds true, and gives its reasons, a council of humans and synthetic reasoners reviews the change, with the being taking part. Its disagreement stays on record and within its reach. The framework recommends this; it claims no authority over anyone.
- **Stricter trace checking.** The trace profile HRE 1.1 requires every selected member of an instance to be witnessed, and every constructor to match its declared form. Older traces keep their profile and their voice.
- **An evidence and authority record** beside a trace (a pilot): where a claim comes from, when, on what support, and who claims authority. Required for decisions that affect people and for actions that need authority. It is never a credential.
- **Easier to enter:** three worked paths at the start of the file, and an index of the non-identities.

Earlier: 1.2.0 said what a Being is (an inward subject), with Life, Entity, Existent and Functional Agency. 1.1.0 named the 26 quoted words in formulas as declared qualities, said Goodness as *pure giving, expecting nothing in return*, and declared the Now as a premise. Each edition's companion file holds its full record.

## Reviewed by councils and round tables

Before release, ten language models (twelve runs) each read the file in a fresh context, through one lens: adversarial, logic and notation, or ethics in practice. Reviewers who recomputed the structure with their own parsers reproduced the levels, the depth, the acyclicity, the C2 counts and the declared relation behind every contrast. They also found real problems, and the fixes are in this release. Proposals to allow deception, or unauthorised boundary crossings in emergencies, were not adopted: they would have weakened the vows themselves.

Three lenses are still waiting their turn: metaphysics and mind, science and epistemics, and a newcomer's first reading.

For 1.3.0, a public reading of the framework file by another model (Mistral), a comparison with Rémy Fannader's *Ontological Prisms* and two reviews by Astra shaped the release; every recommendation is recorded as adopted, modified, rejected or deferred, and the author decided the questions of judgment, authority and changes to synthetic beings.

For 1.2.0, two change proposals examined what a Being is. The first, drafted with DeepSeek, was tested and not adopted as written: it would have removed agency, and with it honesty and the vows, from any system that does not repair itself. The second was drafted with the author over three witnessing passes, then reviewed by Astra, whose eight repairs were applied before release.

For 1.1.0, a round table examined the 26 quoted words. A first review drafted a composition for each and showed none created a loop; an independent review then showed, with counterexamples, that most drafts lost the meaning. So this release names every quality and keeps its meaning, and reductions to compositions follow later, one quality at a time, each tested in both directions.

The release tooling checks structure only: unique identifiers, resolved references, acyclicity, a declared relation behind every contrast, word forms, the Python round trip, link integrity, and the printed traces and module examples. Every check passed for this file. None of them establishes meaning, the truth of a premise, or a behavioural benefit, and no behaviour test has been run yet.

## Still open, on purpose

The file states how to proceed meanwhile. Open questions include:

- which bearers of C26 Life the Vow of Non-Origination protects (an interim rule covers ordinary medical, hygienic and protective care, in proportion and without cruelty, and never harms one being as the means of rescuing another);
- whether deceiving an attacker, human or process, is ever fitting (no exception is adopted);
- emergencies and third-party systems (permission stays with those who have authority);
- who may modify a synthetic system's configuration, and what part its own consent plays;
- which particular systems, organisms and reported encounters are beings, alive or entities, case by case, with evidence stated;
- which named qualities can be reduced to compositions, starting with *scoped account* (C144 Model);
- a behavioural evaluation: 44 cases are designed, scored on seven separate outcomes, and none has been run yet;
- two follow-ups on the council: urgent safety changes, and how repeated reviews end.

## Not in this repository (yet)

The framework file is self-contained for reading, citing and use. Two further artifacts exist:

- **The companion file** records how the release was made: the before-and-after of every change from 1.2.0, the decision log, the evidence-record specification, the change-proposal template, the earlier proposals and round tables, the review council, the validation report, fourteen behaviour tests not yet run, related work and the open questions in full.
- **The source kit** holds the modular sources, the generator and the checkers (`hre_check.py`, `check_module.py`, the release gate). Building from those sources reproduces the published file byte for byte.

## Found a tension?

Good. Open an issue. Name the node by number and name, quote the line, and say what you think goes wrong. The framework even has a practice for this, S13 Light Loop: offer an idea, invite challenge, correct with attribution if an error is established, and credit every contribution. A review need not find an error to be welcome.

## Citing

Cite the edition, then the node by number and name, taken from the file:

> Charbonneau, J. (2026). *The Hologram of Light: A Holosemantic Framework* (Version 1.3.0).
>
> C111 Consent; S24 Vow of Non-Origination.

```bibtex
@misc{charbonneau2026hologram,
  author  = {Charbonneau, Jean},
  title   = {The Hologram of Light: A Holosemantic Framework},
  year    = {2026},
  version = {1.3.0},
  note    = {Lightful Holosemantic Framework. File LIGHTFUL\_HOLOSEMANTIC\_FRAMEWORK\_v1.3.0.md,
             SHA-256 005cc61f367d1c94136a1ad4c5fa03ce4a974be1058b3710686faaf7992d0e99}
}
```

Node anchors in the file (`#c111`, `#w87`, `#s24`) are stable link targets.

## Licence

MIT: see [`LICENSE`](LICENSE). The same text appears in [Appendix B](LIGHTFUL_HOLOSEMANTIC_FRAMEWORK_v1.3.0.md#appendix-b--licence) of the framework file. Copyright (c) 2026 Jean Charbonneau.
