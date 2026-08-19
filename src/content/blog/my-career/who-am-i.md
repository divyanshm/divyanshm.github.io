---
title: Who Am I?
description: An introduction to who I am and the experiences that shaped me.
published: 2026-08-18
draft: false
tags:
  - My Career
---

**Divyansh Manchanda — Software Architect · Distributed Systems · Platform Engineering · Identity & Security**

I am a software architect focused on building reliable, secure, and scalable platforms.

Over the course of my career, I've worked across distributed systems, cloud infrastructure, authentication and authorization, workload identity, resilience, developer platforms, and engineering productivity.

What I enjoy most is entering a complex or unfamiliar system, understanding it from first principles, finding the underlying architectural problem, and turning that understanding into a simpler model that other engineers can build on.

---

## What I Work On

### Distributed Systems

I enjoy systems where correctness, scale, failure modes, and operational behavior matter as much as the happy path.

Areas I have worked deeply in include:

* Service-to-service communication
* Distributed caching and replication
* Resilience and failover
* High-scale token and credential systems
* Consistency and freshness
* Observability and live-site diagnostics
* Safe rollout and migration strategies

### Platform Engineering

A recurring theme throughout my career has been turning repeated engineering problems into reusable platform primitives.

I am particularly interested in:

* Platform abstractions
* Developer experience
* Secure-by-default platforms
* Policy and governance
* Reusable architectural patterns
* Reducing operational complexity
* Building systems that allow other engineers to move faster

### Identity & Security

I have spent significant time working on authentication, authorization, service-to-service security, and workload identity.

Areas of particular interest include:

* OAuth 2.0 and OIDC
* Service-to-service authentication
* Workload identity federation
* Federated credentials
* Token validation and signing
* Identity-aware platform design
* Security policy and governance
* Secure integration patterns

Identity is one of my deepest technical areas, but I think about it primarily as part of a broader platform and distributed-systems problem.

### Reliability

I have a strong bias toward systems that are resilient by design rather than systems that become resilient after incidents.

I care about:

* Failure-mode analysis
* Dependency isolation
* Graceful degradation
* Disaster recovery
* Safe migrations
* Telemetry-driven operations
* Production readiness

---

## How I Approach Engineering

My engineering approach has evolved over time.

Early in my career, my focus was primarily on solving difficult technical problems myself.

As my scope grew, I learned that the more valuable question is:

> **How do I make the system — and the engineers working on it — better without requiring me to be involved in every decision?**

That has led me toward four principles.

### 1. Understand the system from first principles

Before designing a solution, I want to understand:

* What problem are we actually solving?
* What assumptions does the existing system make?
* Where are those assumptions breaking?
* What are the important invariants?
* What happens when dependencies fail?
* What will become difficult to change later?

### 2. Prefer primitives over one-off solutions

When the same problem appears repeatedly, I look for the abstraction underneath it.

A good platform should make the correct path easier than the incorrect path.

### 3. Use data to resolve ambiguity

Telemetry, production behavior, failure rates, traffic patterns, and operational data are often more useful than opinions.

I use data not just for observability, but to establish common decision criteria when teams disagree.

### 4. Multiply other engineers

At larger scope, my output cannot be measured by the code I personally write.

I try to create leverage through:

* architecture
* documentation
* design reviews
* reusable patterns
* engineering practices
* mentoring
* developer tooling
* and clear decision frameworks

The goal is not to become the person everyone depends on.

The goal is to make the organization less dependent on any one person.

---

## Selected Engineering Stories

### Building a Resilient Authentication Platform

One of the most significant projects in my career involved designing a new resilience architecture for a large-scale authentication system.

The problem was ambiguous: existing resilience assumptions did not work for all workload topologies, and the solution needed to operate at very large scale while preserving security, freshness, and operational guarantees.

I helped take the problem from:

**ambiguous requirements → architecture → stakeholder alignment → prototype → production → reusable platform primitives**

The work involved:

* designing the architecture
* evaluating multiple implementation models
* defining failure modes
* establishing rollout and operational strategies
* collaborating across engineering organizations
* developing reusable pipeline abstractions
* creating telemetry and diagnostics
* mentoring engineers working on the system

The broader lesson was that resilience is not simply a feature of a service.

It is an architectural property of the system around it.

---

### Turning Engineering Quality into a System

I have always been interested in engineering quality, but over time I became less interested in personally reviewing more code and more interested in changing the system that produces the code.

One example was redesigning how code reviews were distributed across an engineering organization.

The goal was to reduce dependence on a small number of reviewers while increasing participation from engineers at different levels.

The resulting model increased reviewer participation and reduced individual reviewer bottlenecks.

The important lesson for me was:

> **Engineering excellence scales through mechanisms, not heroics.**

Architecture standards, review systems, testing practices, documentation, observability, and reusable patterns can all turn individual expertise into organizational capability.

---

### Platform Governance for Workload Identity

As workload identity became increasingly important, another question emerged:

> How do you make a powerful identity primitive safe to operate at organizational scale?

The challenge is not simply implementing authentication.

It involves:

* ownership
* policy
* governance
* security boundaries
* provisioning
* federation
* platform defaults
* and developer experience

My work in this area has increasingly focused on moving from implementation-specific controls toward platform-level governance and secure-by-default patterns.

This is an area where I am particularly interested in the intersection of:

**Identity × Security × Platform Architecture**

---

## Mentorship & Engineering Leadership

One of the most rewarding parts of my career has been helping engineers grow.

My approach to mentorship is less about providing answers and more about helping engineers develop their own engineering judgment.

I tend to focus on:

* breaking ambiguous problems into smaller decisions
* evaluating architectural tradeoffs
* communicating technical decisions
* improving design quality
* developing ownership
* learning how to operate across team boundaries

Over time, I have also tried to scale mentorship beyond individual relationships through technical discussions, design reviews, learning sessions, engineering patterns, and reusable documentation.

The leadership transition I have found most important is:

> **From being the person who solves the hardest problems → to being the person who helps other engineers solve hard problems.**

---

## Architecture Interests

I am particularly interested in the intersection of:

```text
                 Platform Architecture
                         │
          ┌──────────────┼──────────────┐
          │              │              │
      Identity        Distributed     Runtime
      & Security       Systems       Platforms
          │              │              │
       Workload       Resilience     Compute
       Identity        Scale         Kubernetes
       Federation      Failure       Scheduling
       Policy          Consistency   Developer UX
          │              │              │
          └──────────────┼──────────────┘
                         │
                  Secure Platforms
```

Some questions I enjoy exploring:

* How should platforms make security the default?
* What should be a platform primitive versus an application responsibility?
* How do you design systems that remain operable during partial failure?
* How do you evolve architecture without forcing synchronized migrations?
* How do you turn organizational policy into enforceable technical mechanisms?
* How do you create abstractions that simplify rather than hide complexity?
* How do you scale engineering judgment across hundreds of engineers?

---

## Learning New Systems

One of the patterns that has shaped my career is deliberately entering unfamiliar technical domains.

I have moved across areas including:

**performance → orchestration → cloud infrastructure → identity → distributed authentication → resilience → workload identity → platform architecture**

I enjoy the process of learning a system deeply enough to understand not just *how* it works, but *why it was designed that way*.

I increasingly think of this as a core engineering skill:

> **The ability to develop architectural intuition in systems you did not originally design.**

That is also why I enjoy architecture archaeology: understanding why an existing system looks the way it does, which constraints shaped it, and which assumptions are no longer true.

---

## Technical Areas

**Distributed Systems**

* Distributed caching
* Replication
* Consistency
* Failure handling
* Resilience
* Observability
* High-scale services

**Identity & Security**

* OAuth 2.0
* OIDC
* Service-to-service authentication
* Workload identity
* Federation
* Token validation
* Authorization
* Security policy

**Cloud & Infrastructure**

* Kubernetes / container platforms
* Cloud architecture
* Service infrastructure
* Deployment and rollout systems
* Platform engineering

**Engineering Systems**

* Architecture reviews
* Developer productivity
* Code quality
* Testing strategy
* CI/CD
* Operational excellence
* Engineering mentorship

---

## Beyond the Code

I believe good architecture is ultimately about making good decisions repeatedly.

The systems I find most interesting are therefore not necessarily the most technically complicated ones.

They are the ones where:

* multiple teams have competing constraints,
* the failure modes matter,
* the system must evolve over years,
* security and usability are in tension,
* and the architecture has to help hundreds of engineers make the right decisions.

That's the kind of engineering problem I want to keep working on.

---

## Contact

[LinkedIn](https://www.linkedin.com/in/divyanshm/)

I'm particularly interested in conversations about distributed systems, platform architecture, workload identity, security, resilience, and engineering leadership.
