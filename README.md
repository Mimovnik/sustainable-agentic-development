# Sustainable Agentic Development Manifesto

We use AI agents to build software better, not just faster.

Real-world software, unlike prototypes or proofs of concept, is not a static artifact.
It is a living, evolving system.
Every change affects future changes, future developers, future users, and future failures.

This manifesto aims to help developers use AI agents with care and responsibility
while *growing* software that remains useful as it changes.

## 1. Build for Change

“Change is the only constant.” -- Heraclitus

This applies to software as well.
Real software evolves with users, requirements, bugs, teams, constraints, and time.

Do not optimize only for the first version, the next feature, or the next bug fix.
Build so the system can be understood, changed, repaired, and improved later.

The goal is not just to make it work today.
The goal is to guide its growth in the right direction.

## 2. Own the Software

The agent may write code, but we own the result.

Treat generated code as a draft, not as truth.

Do not merge code you cannot explain.
Do not ship behavior you do not understand.
Do not let the agent become the only one who knows how the system works.

## 3. Start from the User

Before asking “how do we build this?”, ask:

Who is the user?
What problem are they actually trying to solve?
What should this software deliberately not do?

Good software has a point of view. It is not a pile of features.

## 4. Short-Term Speed Is Not Long-Term Quality

Vibe coding accelerates short-term goals while often ignoring long-term ones.

It can quickly produce something that works today,
but real software must survive tomorrow: new requirements, bugs, users, teammates, refactors, incidents, and production constraints.

Speed is valuable only when it does not restrict our ability to change the system later.

## 5. Think Before Generating

Avoid both extremes: heavy planning that pretends to know everything, and vibe coding that thinks about nothing.

Use the lightest tool that clarifies the work: a sketch, use case, sequence diagram, acceptance criteria, test case, prototype, or conversation.

The goal is not bureaucracy.
The goal is understanding before code generation.

## 6. Prefer Learning Over Speed

Using an agent should make us better developers, not more passive ones.

Ask why.
Read the diff.
Understand the tradeoffs.
Use the agent as a teacher, reviewer, sparring partner, and assistant — not as a replacement for thinking.

## 7. Taste Matters

Quality is not only correctness.
More code is not more progress.

Names matter.
Boundaries matter.
Simplicity matters.
Consistency matters.
Meaningful tests matters.
Deleting unnecessary code matters.
Knowing what not to build matters.

Agents can imitate the shape of good code. Taste judges the substance.

## 8. Keep Feedback Loops Fast

Good teams learn quickly.

Run tests often.
Ship small changes.
Review small diffs.
Listen to users often.
Make failures visible.

Fast feedback is what makes agility real.

## 9. Tooling Raises the Floor, Not the Ceiling

Use strong tooling: type systems, tests, linters, formatters, CI, static analysis, security checks, logs, metrics, and profilers.

But tools are not enough.

A green CI pipeline does not mean the product is good.
Passing tests do not prove the tests are meaningful.
Formatted code does not mean maintainable code.

Tools support judgment. They do not replace it.

## 10. Care About Quality, Not Perfection

Do the work with care.

Do not confuse quality with perfection.
Real software is never finished; it is shaped, tested, used, changed, and improved.

Ship when the system is honest, useful, understandable.

Pour your heart into it <3

