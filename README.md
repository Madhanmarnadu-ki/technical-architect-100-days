# 100-Day Technical Architect Challenge

A structured 100-lesson learning journey to strengthen my technical-architecture skills using practical system-design scenarios and my existing Microsoft technology background.

This repository documents my daily lessons, exercises, architecture decisions, tests, corrections and progress toward becoming a Technical/Solution Architect.

## Goal

My goal is to move beyond feature-level development and develop the ability to:

* Convert business requirements into technical architecture
* Identify architecture drivers and quality attributes
* Find system and module boundaries
* Design maintainable .NET applications
* Evaluate architecture alternatives and trade-offs
* Design secure, scalable and reliable cloud systems
* Communicate architecture clearly to technical and business stakeholders
* Integrate AI/ML and Generative AI into enterprise applications

## Technical Background

The learning exercises are aligned with my experience in:

* C# and .NET 8
* ASP.NET Core Web API
* Entity Framework Core and Dapper
* SQL Server and PostgreSQL
* Angular
* Azure
* Redis
* Clean Architecture
* Domain-Driven Design
* CQRS and MediatR
* Microservices
* Docker
* Azure DevOps
* Application security
* AI/ML integration

## Challenge Structure

The challenge contains:

* 100 technical-architecture lessons
* One focused topic per lesson
* Approximately 15 minutes per lesson
* One test after every 10 completed lessons
* 10 tests in total
* Practical exercises using realistic applications
* Periodic revision based on test results

The sequence is:

```text
Days 1–10   → Test 1
Days 11–20  → Test 2
Days 21–30  → Test 3
Days 31–40  → Test 4
Days 41–50  → Test 5
Days 51–60  → Test 6
Days 61–70  → Test 7
Days 71–80  → Test 8
Days 81–90  → Test 9
Days 91–100 → Test 10
```

Tests are additional sessions and do not replace or renumber learning days.

## Daily Learning Format

Each lesson contains:

1. Seven-minute concept explanation
2. Five-minute practical exercise
3. Two-minute architect-thinking question
4. One-minute takeaway

Each lesson is documented using:

```text
Concept
→ Why it is needed
→ Real-world example
→ Architecture decision
→ Practical exercise
→ Questions and corrections
→ Summary
```

## Learning Roadmap

| Section                      | Topics                                                                  |
| ---------------------------- | ----------------------------------------------------------------------- |
| Architect Foundations        | Quality attributes, architecture drivers, system boundaries and C4      |
| Application Architecture     | Modular monoliths, Clean Architecture, DDD, CQRS and aggregates         |
| APIs and Distributed Systems | API design, messaging, queues, events and consistency                   |
| Data Architecture            | SQL, NoSQL, indexing, transactions and data ownership                   |
| Caching                      | Redis, cache-aside, invalidation and distributed caching                |
| Azure Architecture           | App Service, Functions, Service Bus, Storage, networking and identity   |
| Security                     | Authentication, authorization, secrets, encryption and threat modelling |
| DevOps and Observability     | CI/CD, logging, metrics, tracing and production diagnostics             |
| Scalability and Reliability  | Scaling, availability, resilience and failure handling                  |
| System Design                | End-to-end architecture exercises and trade-off analysis                |
| AI/ML Architecture           | Model integration, RAG, vector search, AI safety and observability      |
| Architecture Leadership      | ADRs, communication, governance, cost and technical strategy            |
| Capstone                     | Complete architecture designs and documentation                         |

## Repository Structure

```text
technical-architect-100-days/
├── README.md
├── progress.md
├── templates/
│   ├── lesson-template.md
│   ├── exercise-template.md
│   └── test-template.md
│
├── 01-architect-foundations/
│   ├── day-01-quality-attributes.md
│   ├── day-02-architecture-drivers.md
│   ├── day-03-system-boundary.md
│   ├── day-04-c4-model.md
│   ├── day-05-modular-monolith.md
│   ├── day-06-clean-architecture.md
│   ├── day-07-bounded-contexts.md
│   ├── day-08-module-communication.md
│   ├── day-09-cqrs.md
│   ├── day-10-aggregates.md
│   └── test-01-days-01-10.md
│
├── 02-dotnet-architecture/
├── 03-api-distributed-systems/
├── 04-database-caching/
├── 05-azure-cloud/
├── 06-security/
├── 07-devops-observability/
├── 08-scalability-system-design/
├── 09-ai-ml-genai/
└── 10-leadership-capstone/
```

## Current Progress

| Session | Topic                                      | Status            |
| ------- | ------------------------------------------ | ----------------- |
| Day 1   | Quality Attributes Drive Architecture      | Completed         |
| Day 2   | Identify Architecture Drivers              | Completed         |
| Day 3   | Define the System Boundary                 | Completed         |
| Day 4   | Communicate Architecture with C4           | Completed         |
| Day 5   | Start with a Modular Monolith              | Completed         |
| Day 6   | Clean Architecture Dependency Rule         | Completed         |
| Day 7   | Bounded Contexts and Module Boundaries     | Completed         |
| Day 8   | Synchronous and Asynchronous Communication | Completed         |
| Day 9   | CQRS                                       | Completed         |
| Day 10  | Aggregates and Aggregate Roots             | Completed         |
| Test 1  | Days 1–10                                  | Completed — 13/20 |

## Test 1 Review

### Strong areas

* Identifying bounded contexts
* Classifying commands and queries
* Clean Architecture dependency direction
* Selecting a modular monolith for a small team and MVP
* Converting business flows into operations

### Revision areas

* Writing measurable quality attributes
* Separating requirements from technology decisions
* Understanding aggregate-root responsibilities
* Selecting synchronous versus asynchronous communication
* Distinguishing owned entities from external references

## Practical Scenarios

Concepts are applied using realistic systems such as:

* Bus-ticket booking
* Online hospital appointments
* Food delivery
* Hotel booking
* Movie-ticket booking
* E-commerce
* Work-tracking systems
* Personal financial-assistant product

For every system, I follow this architecture sequence:

```text
Business flow
→ Operations
→ Operation groups
→ Bounded contexts
→ Domain model
→ Entities and value objects
→ Aggregates and rules
→ Commands and queries
→ Synchronous/asynchronous communication
→ Clean Architecture placement
→ Infrastructure decisions
→ Trade-offs
```

## Progress Rules

A lesson is marked completed only after:

* Reading and understanding the concept
* Completing the practical exercise
* Asking questions about unclear areas
* Writing a short summary in my own words
* Recording the result in `progress.md`

If a lesson is incomplete, the challenge holds that lesson instead of moving forward.

## Documentation Principles

* Write concepts in my own words
* Record why a pattern is needed
* Do not use patterns without a clear business reason
* Include realistic examples
* Record corrections and misunderstandings
* Keep diagrams and code focused
* Document trade-offs, not only the final decision
* Prefer simple architecture until complexity justifies expansion

## Long-Term Outcome

By completing this challenge, I expect to be able to:

* Analyse unfamiliar business requirements
* Find appropriate module boundaries
* Design clean and maintainable .NET systems
* Select suitable Azure services
* Explain architecture decisions and trade-offs
* Design scalable, secure and observable systems
* Review technical solutions from an architect’s perspective
* Produce architecture documentation suitable for interviews and projects

## Status

```text
Lessons completed: 10/100
Tests completed: 1/10
Current test score: 13/20
Next lesson: Day 11 — Domain Events
```
