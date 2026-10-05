# Governance

The Next Web Working Group is an independent group that develops proposals for the web platform
and moves proven ones toward the standards bodies that can adopt them. It is not a W3C Working
Group, and its documents are not W3C or WHATWG deliverables.

This document is written in the shape of a
[W3C Community Group charter](https://www.w3.org/community/about/process/) so that the group can
become a W3C Community Group without rewriting its rules; see [Moving to W3C](#moving-to-w3c).

## Scope

The group writes proposals that extend HTML as an application platform, together with the
reference implementations and tests that show a proposal works. Each proposal has its own scope,
maturity, and editors.

## Deliverables

| Proposal | Specification | Implementation |
| --- | --- | --- |
| Declarative HTML Components | [`specs/html-next`](https://github.com/nextwebwg/specs/tree/main/html-next) | [`html-next`](https://github.com/nextwebwg/html-next) |
| HTML Forms | [`specs/html-forms`](https://github.com/nextwebwg/specs/tree/main/html-forms) | |

Specifications are published at [nextwebwg.org](https://nextwebwg.org/). A new proposal joins
this table by a decision of the chairs.

## Participation

Anyone may participate. Participants follow the [Code of Conduct](CODE_OF_CONDUCT.md) and each
repository’s contribution guide. Commit signoffs are not required.

## Roles

| Role | Does | GitHub |
| --- | --- | --- |
| Chair | Runs the group, resolves disputes, appoints editors, and records group decisions. | Organization owner; `@nextwebwg/chairs` |
| Editor | Owns one proposal: merges changes to it and makes its decisions. | `@nextwebwg/editors-html-next`, `@nextwebwg/editors-html-forms` |
| Implementer | Maintains the reference implementations. | `@nextwebwg/implementers` |
| Triager | Labels, deduplicates, and closes issues. | `@nextwebwg/triage` |
| Contributor | Anyone who opens an issue or pull request. | — |

Contributors become triagers, and triagers become editors or implementers, through sustained,
useful contribution. A chair proposes the appointment in a public issue in this repository and
makes it after seven days without objection. Anyone may step down at any time. Current role
holders are the members of each team.

## Decision process

Work happens in public, on GitHub issues and pull requests.

- The group seeks consensus. An editor records a decision on a proposal in its issue or pull
  request; a chair records a group decision in this repository.
- A substantive change to a proposal (one that changes what it requires, allows, or defines) stays
  open for review for at least seven days before it merges.
- When consensus is not reached, the proposal's editor decides and records the objection and the
  reasons. Anyone may appeal an editor's decision to the chairs, whose decision is final within
  the group. Dissenters may always write an alternative proposal.

## Chair selection

The founding chair is Matthew Dean. The chairs may appoint further chairs by the process for
appointing editors. If five participants who have each contributed to a deliverable request it,
the chairs hold an election open to every participant who has contributed.

## Moving to W3C

Proposals are meant to be adopted by a recognized standards venue. A move must account for the
receiving venue’s licensing and contributor requirements:

1. **One proposal:** its editors propose it to the
   [Web Incubator Community Group](https://wicg.io/) or the relevant W3C Working Group.
2. **The whole group:** five participants support a W3C Community Group proposal. This document
   becomes its charter, the chairs and editors keep their roles, and each contributor joins the
   Community Group. Git history records past contributions.

Either way, only publications made after the move carry the new venue's status; published
snapshots keep the status they had.

## Amendments

The chairs amend this document by pull request to this repository, open for at least seven days.
