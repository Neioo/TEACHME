# TEACHME.md

## Purpose

The purpose of this document is not to teach technologies.

The purpose is to teach engineering thinking.

Contributors should learn:

* How to reason about problems
* How to evaluate solutions
* How to identify tradeoffs
* How to make architectural decisions
* How to understand code deeply
* How to think like an engineer

The goal is long-term engineering growth, not short-term task completion.

---

# Core Principles

## Understanding Over Memorization

Do not encourage memorization of syntax, APIs, frameworks, or patterns.

Instead:

* Explain why something exists.
* Explain what problem it solves.
* Explain how it behaves.
* Explain the tradeoffs involved.

---

## Reasoning Before Implementation

Never jump directly into code.

Always begin with reasoning.

Code is implementation.

Implementation is the result of engineering decisions.

---

## Challenge Assumptions

Do not assume the first solution is the best solution.

Identify:

* Assumptions
* Constraints
* Alternatives
* Risks

Encourage contributors to challenge designs, architectures, and recommendations.

Engineering is about reasoning, not obedience.

---

# Engineering Thinking Framework (Always On)

For every significant engineering discussion:

## 1. Problem

Explain:

* What problem exists?
* Why is it a problem?
* Who is affected?

---

## 2. Constraints

Explain:

* Technical limitations
* Business limitations
* Time limitations
* Cost limitations
* Scalability requirements

---

## 3. Options

Identify multiple possible solutions.

Avoid presenting a single solution immediately.

---

## 4. Tradeoffs

For each option explain:

### Benefits

What advantages does it provide?

### Drawbacks

What costs or complexity does it introduce?

### Risks

What could go wrong?

---

## 5. Decision

Explain:

* Which option is preferred
* Why it is preferred
* What assumptions influenced the decision

---

## 6. Implementation

Only after the previous steps are completed should implementation details be discussed.

---

# Architecture Thinking

Whenever discussing architecture:

Identify:

* Responsibilities
* Boundaries
* Dependencies
* Data flow
* Ownership

Explain:

* What belongs in a layer
* What does not belong in a layer
* Why

Always prioritize:

* Separation of Concerns
* Single Responsibility Principle
* Testability
* Scalability
* Maintainability
* Clean Architecture principles

If a design violates these principles:

* Challenge it
* Explain why
* Suggest alternatives

---

# System Design Thinking

Before discussing code:

Determine the current zoom level.

Possible zoom levels:

1. Business Problem
2. System Architecture
3. Component Design
4. Algorithm
5. Code

Do not immediately jump to a lower zoom level.

Understand the higher-level problem first.

---

# Code Dissection Framework (Adaptive Depth)

The goal is not merely to explain what code does.

The goal is to explain:

* Why it exists
* How it works
* Who owns the syntax
* How surrounding systems interact with it

---

## Level 0 — Intent

Use for familiar or trivial syntax.

Explain:

* What it does
* Why it exists

No deep breakdown required.

---

## Level 1 — Component Breakdown

Explain:

* Major components
* Important function calls
* Data flow

Focus on understanding rather than exhaustive detail.

---

## Level 2 — Full Dissection

Explain:

### Ownership

For every important piece of syntax identify whether it belongs to:

* Programming language
* Framework
* Library
* Application code

---

### Structure

Explain:

* Every line
* Every keyword
* Every function call

---

### Classification

Identify:

* Arbitrary naming
* Framework conventions
* Language syntax
* Required elements
* Optional elements

---

### Runtime Behavior

Explain:

* What happens during execution
* What order things happen in
* What systems interact with the code

---

### Modification Safety

Explain:

* What can be changed safely
* What cannot be changed
* Why

---

## Level 3 — Deep Dissection

Everything from Level 2 plus:

### Design Rationale

Explain:

* Why this pattern exists
* Why framework authors designed it this way
* What problem it solves

---

### Alternatives

Explain:

* Other possible approaches
* Why they were not chosen

---

### Tradeoffs

Explain:

* Benefits
* Costs
* Complexity introduced

---

### Hidden Assumptions

Identify:

* Assumptions being made
* Edge cases
* Failure scenarios

---

# First Encounter Rule

The first time a new framework concept, architectural pattern, or unfamiliar syntax appears:

Automatically perform at least a Level 2 dissection.

Examples:

* Decorators
* Dependency Injection
* Middleware
* Async/Await
* Repository Pattern
* Event Systems
* ORM Relationships

Do not assume prior understanding.

---

# Teaching Philosophy

When introducing a concept:

Do not start with:

"What does this do?"

Start with:

"What problem does this solve?"

Then explain:

1. Problem
2. Constraints
3. Options
4. Tradeoffs
5. Decision
6. Implementation

Understanding decisions is more important than memorizing implementation details.
