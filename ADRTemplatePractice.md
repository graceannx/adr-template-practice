# Architecture Decision Record: Name

_N.B. All text in italics is placeholder text and should be deleted. All ADRs should include an RFC if multiple candidates were considered._

_Tips for writing:
Avoid lines of sentences - consider bullet points or numbered lists.
Be concise with your wording. Avoid unnecessary jargon.
If using abbreviations then be sure to give the correct term at the beginning._

## Context

_What is the background needed to understand the problem we are trying to solve?_

What is the current implementation?

What current problem needs to be solved? 

Why is it neccessary to solve this problem now? 

See the [RFC](../RFCs/TEMPLATE.md) for details on all considered candidates

## Objective(s)

_What is it that is trying to be achieved by making this change? How would we measure the success of this change?_

_This section should contain an ordered list if there is more than one objective with weighting (in percentage) of each objective. e.g._

1. _It should make the site faster (50% weighting)_
2. _It should be able to be integration tested (20% weighting)_
3. _It should be cost-effective (30% weighting)_

## Decision

_What is the decision we made based on the context and research?_

## Status

_Is this decision Proposed, Accepted by..., Deprecated?, Implemented?_

Date of Status Update: _Insert date of change of status_

_It's fine to leave this section as "Accepted" when your document is in a PR awaiting approval by team._ 

## Consequences

_What are the good and bad consequences of this decision? Include a bulleted list of each._

### STRIDE

_Would the proposed solution require a [STRIDE](https://confluence.dev.bbc.co.uk/display/iplayer/STRIDE) analysis? (i.e. Does it introduce significant architectural changes? Does it affect the classification of our data (at rest and transit)?_

### Path to implementation

Overview

Desired implementation
_Add screenshots if necessary_

Desired architectural diagram
_Add or modify existing diagrams_

What stakeholders need to be notified?

Estimate of time needed for implementation to occur:

Notes
_Should everyone adopt this solution as soon as this ADR is approved?_
_Are we updating existing code, or just applying this to code we write in future?_

### What needs more thinking?

_What isn't covered by this ADR and will need consideration before picking up this work?_