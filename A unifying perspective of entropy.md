# A unified perspective of entropy

Entropy is a central concept across many fields, yet each defines it differently while trying to capture the same underlying idea. Because each discipline builds on its own assumptions, entropy often appears distinct across contexts, making its unifying principles less apparent.

[This _Quanta Magazine_ article](https://www.quantamagazine.org/what-is-entropy-a-measure-of-just-how-little-we-really-know-20241213/) offers a thoughtful perspective on the historical and conceptual challenges of entropy across different fields.

In this work, I explore how **entropy as a phenomenon can be unified, but entropy as a measure cannot.**

## Entropy as phenomenon is distinct from entropy as a measure

Phenomena exist independently of representation. Mathematical expressions, language, visual models, and formal notations provide ways to describe them, but no symbolic representation can fully capture reality. A map is never the territory.

A mountain's height exists whether measured in feet or meter. Economic growth exists whether expressed as percentages absolute values, or narrated in an article.

Measurement is a specific type of representation that quantifies phenomena. It assigns numerical values through defined procedures, enabling comparison and computation.

This distinction applies to entropy. Entropy exists as a phenomenon before any formula calculates it as a measure. While entropy as a measure is defined through mathematical formulations across disciplines there is no unified conceptual definition of the phenomenon.

The ideas of uncertainty and disorder they represent suggest a fundamental unity, but its vagueness keeps the definition of the phenomenon obscured.

This distinction applies to entropy. Entropy exists as a phenomenon independently of any mathematical formulation used to measure it. While entropy as a measure is formally defined across disciplines, there is no single unified conceptual definition of the phenomenon itself.

The notions of uncertainty and disorder suggest an underlying unity across fields, yet they are too vague  to define the phenomenon that entropy fundamentally represents.

## What is entropy

It's intuitive to define entropy as a phenomenon from the experience of uncertainty. When you hear an unexpected sound, your uncertainty is the relation between what you know and what you believe could have caused it. Nothing else defines it. This is the phenomenon entropy represents.

Entropy as a phenomenon is the relationship between priors (what is known) and possibilities (what is believed possible).

This relationship is symbolically expressed through probability, which  fuses priors and possibilities into an inseparable mathematical representation. Entropy as a measure is a quantification of this probability representation.

![[Unified perspective of entropy.png]]

# Entropy as a phenomenon

## What are priors

Priors are everything that informs inference or prediction. They represent the complete basis of information needed to infer.

We can refer to priors in many ways: knowledge, beliefs, conceptual frameworks, memories of experiences, rules, regularities, models, algorithms, or assumptions. Anything that shapes how we interpret information or make predictions is a prior.

Priors are defined solely by their influence on inference outcomes, regardless of their information structure or the size of their influence. Any element that affects inference, no matter how subtly, is necessarily a prior. Not acknowledging all priors leads to inaccurate representations and violates basic probability theory. This means that the framework itself, the predictive mechanism, and the formula used for entropy are informed by priors.

All priors ultimately emerge from physical observations, even our most abstract frameworks. Mathematical structures, causal assumptions, and conceptual categories all trace back to chains of physical observations, accumulated and refined through individual and collective experience.

- When finding the cause of an unexpected sound the priors will include sound itself,  experiences with similar sounds, knowledge of the environment, and ideas of potential sources. Fundamentally the internal model of reality of the specific context.

- Statistical mechanics recognizes macroscopic measurements like temperature, pressure, and volume as inputs for inference from which microstate probabilities are derived. Yet comprehensive priors must also include conservation laws, equal a priori probability, particle indistinguishability, interaction models, the ergodic hypothesis, boundary conditions, and the mathematical framework itself. All these elements influence how microstates are defined, counted, and assigned probabilities.
  
- Information theory recognizes observed symbol frequencies and historical data as inputs for inference from which symbol probabilities are derived. Yet comprehensive priors must also include the defined symbol set, independence assumptions between symbols, symbol probabilities remain consistent, discretization choices, message boundary definitions... All these elements influence how symbols are identified, counted, and assigned probabilities.

## The puzzling nature of comprehensive priors

It's impossible to exhaustively enumerate all priors as individual entities precisely because of their comprehensive nature. They span diverse information types—symbol sequences, mathematical frameworks, observations, beliefs—existing at different levels of abstraction and complexity.

The internal models of framework conceivers inevitably become foundational priors of particular entropy formulations. These mental models, with their implicit assumptions and conceptual structures, shape how uncertainty is defined and measured.

This complexity becomes even more challenging when priors must be represented symbolically, where the representational space is finite and somewhat discrete, forcing continuous and interconnected knowledge into fragmented symbolic forms.

Yet despite this puzzling nature, we cannot escape the requirement for comprehensiveness. For probability to be well-defined and for entropy to meaningfully measure uncertainty, priors must include everything that affects inference—whether explicitly acknowledged or not.

## What are possibilities

Possibilities represent what is inferred about. It is what is left after applying constraints over an otherwise infinite space of everything.

These constraint are not only necessary for meaningful inference but define the inference itself. Without constraints, the space would include everything conceivable, rendering inference impossible. The act of constraining defines what can be inferred about and establishes the purpose of inference itself.

The intent of the conceiver of the inference shapes these constraints reflecting what is considered meaningful to include or exclude .

Constraints operate across multiple dimensions simultaneously. They may limit time frames, physical or symbolic spaces, physical properties, causal relationships, conceptual categories, or logical conditions. The specific combination determines what remains in the possibility space.

Prediction is a type of inference where the possibility space is constrained to a future time.

A weather forecast, is the possibility space left after constrains excludes any phenomenon that is not about precipitation about a specific location at specific future time. It excludes all phenomena unrelated to this, is not about a die rolls or the outcome of symbolic sequence.

## The puzzling nature of possibilities as constrained spaces

Language naturally obscures the constraining process that defines possibilities. When we name something like a "coin flip" or "weather forecast, we implicitly exclude everything unrelated without acknowledging this exclusion. Names create the illusion that we're referencing objects rather than applying constraints.

Probability theory institutionalizes this blindspot by defining "possible outcomes" as elements of a sample space without examining how this space is determined. When writing P(x), we've already constrained the universe to specific outcomes. The sample space is presented as self-evident, as if it simply exists rather than being actively constructed.

This explains why possibilities are not traditionally defined as such and take different names across entropy frameworks:

- In information theory, they are "outcomes," representing symbol sequences while excluding all physical objects and non-symbolic entities
- In statistical mechanics, they are "microstates," describing particle configurations with arrangements satisfying conservation laws and boundary conditions.
- In causal inference, such as identifying a sound's origin, they are "potential causes", encompassing only phenomena capable of generating the specific sound in the specific environment.

These spaces operate in entirely different domains with different rules. Yet defining possibilities as constrained spaces provides a higher generalization revealing the relationship with priors, probabilities, and entropy across all domains.

## Entropy reflects only possibilities recognized by priors

Possibilities are defined externally because they inherently establish the constrained space in which inference operates. Since inference cannot occur over an undefined space, the conceiver imposes constraints that shape its scope before inference begins.

Yet, possibilities affect entropy only insofar as priors can recognize and account for their constraints. It depends not on the full range of actual possibilities but on what priors acknowledge as possible.

![Constrained space of possibilities.png]

Consider a die. Whether it has five, six, or seven sides, if priors assume a fair six-sided die, the entropy about the outcome remains unchanged. The unrecognized sides do not affect the calculation.

What might seem like the "actual possibilities" is an outside perspective, they are our own priors as external observers, not the priors of the system being studied. Expanding the possibility space or constrains from an outside perspective does not change entropy unless the system's priors can incorporate them..

You hear a sound. Many things could have caused it. But your priors only consider what you believe possible. Any unrecognized sources, though possible, do not affect your uncertainty.

Possibilities encompass what is possible within a specific scope of interest constrained by both external definitions and the priors themselves.

# Entropy as a measure

For entropy to exist as a measurable quantity, priors and possibilities must first be translated into symbolic representations. This translation creates probability representations that encode their relationship numerically. Entropy then compresses this structure into a single scalar.

## Priors and possibilities in the symbolic space

Priors and possibilities define entropy as a phenomena. But for entropy as measurement to exist, they must be translated into the symbolic space and further transformed into a quantity.

**Possibilities** can be represented in any way that reduces the space of what could happen from an open-ended set to a constrained space . E.g., explicit enumerations, rules and conditions, natural language descriptions, mathematical constrains, symbolic spaces, algorithms...

**Priors** can be represented in a anyway that encodes, knowledge, regularities,  patterns, assumptions or structural constraints about the relationships in relation to possibilities. E.g.,. Mathematical models, machine learning models, heuristic rules, conceptual and logical frameworks, probability distributions, linguistic descriptions, databases...

## Inference can't be separated from priors and possibilities

Inference is the process that transforms the relationship between priors and possibilities into a measure in the form of a probability representation.

However, inference is not neutral. It is itself a prior, imposing structure on how priors and possibilities relate. The choice of inference method determines how information is extracted, which constraints are applied, and what form the probability representation takes.

The way we infer is inseparable from what we know; different knowledge structures create different inference patterns.

Traditional views adopt a Cartesian separation between computation and data, treating processes and inputs as distinct entities. Structurally, this separation exists in symbolic representations, yet priors are not analogous to pure data, and inference is more than just processing.

Computation cannot be fundamentally defined without a symbolic representation like Turing machines or lambda calculus. In any such representation, a predictive function is itself a product of priors. Its structure, formulation, and algorithm emerge from priors. The separation between inference and priors is apparent, not fundamental.

Inference is both an expression of priors and a constraint on the space of possibilities. While symbolic representations may suggest an apparent separation, as a phenomenon, inference is inseparable from priors and possibilities.

Inference transforms priors and possibilities into a computable form, ultimately producing a probability representation.

## Probability is the measure of the relationship between priors and possibilities

A probability representation is the structures that encode the relationship between priors and possibilities in numerical form.

It fuses priors and possibilities into a single inseparable expression. Writing **P(x)** already integrates what we assume (priors) with what we consider possible (possibilities). In a coin flip, **P(heads) = 0.5** embeds both prior knowledge (coin physics, fairness) and the assumed possibility space (heads or tails, no other outcomes).

Whether probability is **discrete, continuous, uniform, joint, conditional, marginal, or single-valued**, it encodes the same underlying relationship about the phenomenon in a computable form.

The particular choice of the probability representation  is both a constraint on what can be expressed in possibility space and a prior shaping how they relate.

The same relationship between priors and possibilities in a coin flip can be represented in different probability forms.

- **Continuous distribution** over the coin’s angle (PDF).
- **Equal probability** (1/2) for each outcome (Uniform measure).
- **A single outcome** (heads or tails only, single-value probability).
- ...

Once formalized, probability merges priors and possibilities into a single structure, making their distinct roles indistinguishable. It hides their natural separation.

## Entropy as a measure is the scalar quantification of a probability representation

Probability and entropy express the same fundamental relationship between priors and possibilities at different levels of specificity.

- **Probability** defines the relationship between a **specific** possibility and a defined constrained space of possibilities.
- **Entropy** defines the relationship between **any** possibility and a defined constrained space of possibilities.

Probability and entropy offer different perspectives on the same underlying structure, the relationship between priors and possibilities.

- **Probability** preserves the structure of individual possibilities within a given space, defining how each relates to the rest.
- **Entropy** abstracts this structure into a single value, characterizing the system as a whole without retaining individual relationships.

Probability provides a **detailed composition** of possibilities, while entropy offers a **global characterization** of their distribution. They are distinct but inseparable.

## How priors get obscurely embedded in entropy frameworks

Classic entropy frameworks embed priors without acknowledging them. This leads to incomplete representations of what entropy actually measures. The following a more detailed analysis to illustrate how priors inform every layer of entropy formalization.

### The necessity of comprehensive priors

A probability distribution cannot be well-defined unless priors include everything that affects it. Any external influence would make the distribution non-deterministic, violating basic probability theory. Therefore, priors must be comprehensive by definition.

Missing or unacknowledged priors lead to incomplete probability representations. If an element influences inference, it is a prior—whether recognized or not.

Classic frameworks acknowledge only state data as priors, failing to recognize that their formulations, assumptions, and inference methods are also priors. This incomplete recognition obscures what entropy actually measures.

### Types of priors and how they shape entropy frameworks

I believe the following categorization or priors can help to see how they get embedded in classic entropy frameworks.

- **State priors** are explicitly recognized inputs that frameworks acknowledge. They provide the specific data that, when processed through inference mechanisms, produce probability distributions.
 These would be microscopic arrangements in thermodynamics, symbol frequencies in information theory.

- **Foundational priors** define the conceptual space, even before formalization. They emerge from our internal models of reality and meaning and therefore and constrained by what is consider conceivable. They dictate what elements constitute the system and how these elements relate. They determine how physical observations transform into formal elements, define what is considered possible, measurable, or significant. Most foundational priors remain invisible as they reflect the conceiver's deep assumptions about reality. Any formalization of entropy as a measure is relative to these foundational priors, reflecting specific assumptions chosen by its conceivers.
 Scientific theories, mathematical formalisms, and analytical frameworks are all foundational priors. Statistical mechanics builds on assumptions that particles follow deterministic laws, accessible microstates have equal probability, and energy remains conserved within closed systems. Information theory rests on ideas such as the assumption that messages have finite length and symbols follow statistical patterns.

- **Predictive priors** are observed regularities about how reality behaves. They shape inference mechanisms by determining how probabilities are assigned to possibilities.
 In statistical mechanics, predictive priors about conservation laws and particle independence become the mathematical apparatus for assigning probabilities to microstates. In information theory, observed regularities in communication become the basis for predicting symbol likelihoods.

![[Anatomy of classic entropy frameworks.png]]

### Symbolic representation embeds priors

A symbolic representation always reduces a phenomenon based on what's deemed significant. What is included or excluded reflects foundational assumptions. Mathematical formalism necessarily embeds these assumptions.

Since symbolic representations are built on priors, they do not fundamentally define reality but instead reflect what is considered meaningful within a given framework.

### Priors and possibilities are constrained by foundational priors

Since the frameworks themselves emerge from foundational priors, priors define both, its structure and its representation. This creates two types of constraints:

1. Framework design limits what is conceivable within the system
2. Symbolic representation limits what can be expressed in its language

The act of formalizing a system in symbolic form determines what priors and possibilities can exist within it. Each framework's scope is bounded by what its structure can conceive and its language can express. This artificially constrains both possibilities and priors. Anything that cannot be conceptualized or represented in the framework's language is automatically excluded.

Information theory can only conceive and express symbol sequences and their patterns. Statistical mechanics can only represent mathematical descriptions of physical states and their behaviors.

How a framework is conceptualized fundamentally constrains what it can measure.

### Entropy is not absolute and depends on priors, not observers

Statistical mechanics treats entropy as an absolute property of the system, defining it in terms of microstates. It presents entropy as an inherent property, independent of observation or knowledge.

What counts as a microstate, however, depends on assumptions about constraints, interactions, and statistical treatment. The number of microstates is not purely objective but shaped by how the system is modeled, which variables are considered, and how probabilities are assigned.

What statistical mechanics treats as absolute is actually based on specific priors being taken as universal. The same physical system can have different entropy values under different priors, even if its underlying states remain unchanged.

Information theory recognizes entropy as relative, but attributes this to observers rather than priors. This observer-dependence is only partially correct. Entropy depends on priors, An observer is simply an embodiment of them, but priors could be conceived to exist independently of any specific observer.

Furthermore, information theory does not recognize that the method used to calculate the probability distribution or the entropy formula are themselves products of predictive and system priors. The framework dictates how probabilities are assigned independently of the observer knowledge.

## Entropy as a measure can't be unified

Entropy as a measure requires formalizing the relationship between priors and possibilities. Since there is no neutral or absolute way to define them symbolically, entropy as a measure cannot be unified.

There is no unified definition of distance as a measure. It can be expressed in meters, feet, or travel time. Each formalization of entropy as a measure is shape by its foundational priors and captures aspects relevant to its domain while necessarily excluding.
