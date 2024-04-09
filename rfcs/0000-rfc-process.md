# Introduce an RFC process

- Authors: Your Name [@your-github-handle], ...
- Created: YYYY-MM-DD
- Last updated: YYYY-MM-DD
- Approvers:
- Approved date:
- RFC PR:
- Tracked by:

## Status

PROPOSED

## Summary

Introduce a Request for Comments (RFC) process as a mechanism for reaching consensus on decisions that will impact the outcomes of IT delivery, such as changes to the design of our IT systems, our technical standards, and our ways of working.

## Impact

MEDIUM

RFCs are primarily of interest to technical stakeholders, rather than business stakeholders. The intention is for RFCs to be an internal tool for the IT teams to continuously improve their technical standards and ways of working, and to manage the evolution of the design of the computer systems under their guardianship.

## Motivation

We would benefit from a more formalized way of communicating ideas and reaching consensus on major changes to our software systems, as well as changes to the standards and processes we follow to develop and maintain those systems.

## Context

Changes in functionality are driven by the business, but we are lacking a formal mechanism for making technical and process changes.

## Solution

By convention, this first RFC is to propose that we implement an RFC process!

This proposal is for a lightweight RFC process based on those for open source projects such as [Ember](https://github.com/emberjs/rfcs), [ESLint](https://github.com/eslint/rfcs), [React](https://github.com/reactjs/rfcs), [Rust](https://github.com/rust-lang/rfcs), [Vue](https://github.com/vuejs/rfcs) and [Yarn](https://github.com/yarnpkg/rfcs). RFCs would be managed via a single centralized code repository, hosted on GitHub and using built-in tools including the PR and discussions systems.

The proposed process is extensively documented in this repository's [README](../README.md).

It is suggested that we trial the RFC process for a few months, iterate the design of the process based on experience, and then make a final decision on the relative costs and benefits of RFCs, once we have settled on an optimum process for our needs.

## Tradeoffs

While RFCs are a valuable software development method, they do have some potential disadvantages. In particular, RFCs can be time-consuming to write and to review, and they can complicate and slow down the software development life cycle if not used judiciously.

The balance between the benefits and costs of RFCs must be carefully considered and well understood by all stakeholders. For example, getting the right level of details in RFCs is important for them to be effective, and there is a critical balance to be found in the amount of friction that is introduced to the software development process by adding RFCs as a practice.

## Alternatives

Alternatives to RFCs include Architectural Decision Records (ADRs) and Product Requirement Documents (PRDs). However, these all generally serve the same or similar purposes, and they are not mutually exclusive. RFCs can fulfill the role of ADRs and PRDs, and vice versa.

It is worth noting that, as a continuous improvement method, RFCs are complementary to Sprint Retrospectives and other such practices.

## Consequences

The consequences of implementing an RFC process are that we will have a more formalized way of communicating ideas and reaching consensus on major changes to our software systems, as well as changes to the standards and processes we follow to develop and maintain those systems.

The consequences of _not_ implementing an RFC process are that we will continue to make technical decisions in an ad-hoc manner, and those decisions will not be properly recorded, and therefore will not be communicated effectively to all project stakeholders, especially future stakeholders.

## Questions

Outstanding questions include:

* Who will own the RFC process? Who will be responsible for ensuring that RFCs are written, reviewed, approved and implemented? Who will be responsible for ensuring that RFCs are kept up-to-date as the IT systems and the development and operations teams change?

* Who will be responsible for reviewing and approving RFCs? What guidelines do we need to put in place to ensure that RFCs are reviewed and approved by the appropriate stakeholders. When will it be appropriate to design-by-committee, and when will it be appropriate to have a single decision-maker? Do we require a "benevolent dictator"? When will it be necessary to escalate an RFC for review by a higher authority?

* How will we manage the backlog of RFCs? How will we ensure that RFCs are implemented in a timely manner? What happens if an RFC is approved but not implemented, due to other priorities and constraints such as available resources? How much time should pass before an RFC is considered to be stale and in need of re-approval?

## References

* [A thorough team guide to RFCs](https://medium.com/juans-and-zeroes/a-thorough-team-guide-to-rfcs-8aa14f8e757c) — Juan Pablo Buriticá (2023)
* [The power of "yes, if": iterating our RFC process](https://engineering.squarespace.com/blog/2019/the-power-of-yes-if) — Tanya Reilly, Squarespace Engineering blog (2019)
* [Communicating and documenting architectural decisions (video)](https://www.youtube.com/watch?v=rwfXkSjFhzc) — David Ayers (2019)
* [Docmenting architecture decisions](https://cognitect.com/blog/2011/11/15/documenting-architecture-decisions) — Michael Nygard (2011)
* [Documenting software architectures: views and beyond](https://resources.sei.cmu.edu/library/asset-view.cfm?assetID=30386) — Clements _et al_ (2010)
* [Why write ADRs?](https://github.blog/2020-08-13-why-write-adrs/) — Eli Perkins, GitHub Blog (2020)
* [Lightweight Architecture Decision Records](https://www.thoughtworks.com/radar/techniques/lightweight-architecture-decision-records), Thoughtworks Technology Radar
