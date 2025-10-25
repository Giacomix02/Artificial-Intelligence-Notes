# Forms  of AI

## Description: Symbolic AI
`Symbolic AI` include all those **methodologies** for building AI systems which are based on:
- `manipulating formal symbolic representations` of the underlying problems to be tackled (affrontati) and solved by the target AI system
- and performing abstract reasoning over those symbols

`Symbols` in symbolic AI, and *AI systems* based on them, can be purely **formal** (meaningless) structures.


`In practice`, they are normally **interpreted** by the user in terms of some particular semantic content: verbal, numerical, visual, auditory, and so on.

`Symbols` correspond to **linguistic or logical expressions** aimed at representing the knowledge of the underlying AI system.

Symbols of symbolic AI are actually `human-readable` and AI systems based on them are `interpretable by design`.

`Atomic symbols` can be **combined** to create **complex symbols**, according to `specific formal rules` of symbol manipulation. 

When a symbolic `AI system is run` happens that symbols of various kinds, structured in various ways, are built, stored, retrieved, compared, and transformed.


## Examples

### Medical diagnosis

`Medical diagnosis systems` typically represents the knowledge about the medical domain through symbols that conceptually correspond to notions like “patient”, “doctor”, “disease”, “symptom”, “diagnosis”, “cure”, and so on.


**Diagnoses** are made based on `semantic rules` that
perform reasoning over the underlying symbolic
knowledge, for instance:

>“IF patient has a fever AND patient has a cough
AND patient has difficulty breathing THEN patient
may have pneumonia”.


### NPL: Neural Language Processing

In natural language processing (NLP), the subfield of AI concerned with `processing data encoded in natural
language`, symbolic AI systems use symbols to **represent grammar, syntax, language semantic rules, and so on**.

``Understanding and/or generating natural language`` is performed by **reasoning** over this symbolic knowledge


## Techniques, tools, systems

Symbolic AI is mainly **based** on `knowledge representation` (through formal symbols) and `reasoning` over such a knowledge.

>Logic programming is a predominant tool used in symbolic AI to perform knowledge representation and reasoning

#### An other technique
Another prominent technique of symbolic AI is problem solving through `search`:
-  Represent the `target` problem as a `tree` (or graph) depicting all the possible states of the problem
- `Select the best choice by searching` for the **“most favorable” state** within such a search tree (i.e., a state that makes the player win the game).

## Pros and Cons

`Pros`:
-  explicit knowledge representation in a formal and structured way
- reasoning based on formal tools and techniques
- transparency and interpretability
- flexibility in changes of rules and knowledge
- no need for vast amount of examples to derive knowledge or rules

`Cons`:
- incomplete knowledge
- difficulty with handling uncertain or ambiguous information (it relies on precise and unambiguous representations of knowledge)
- limited scalability
- limited ability to learn and adapt


---
Go to [INDEX](../README.md)