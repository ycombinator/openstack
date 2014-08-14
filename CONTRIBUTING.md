# Contributing Guidelines

1. Please fork this repository into your personal account. All contributions to this repository must be made as pull requests (PRs) from your fork to the `dev` branch of this repository.

1. Changes submitted in PRs must adhere to our [Coding Conventions](#coding-conventions) and [Design Decisions](#design-decisions).

1. Your PR will be reviewed by one or more [Core Contributors](#core-contributors). As long as a PR has a +1 comment on it from *any* of the Core Contributors (other than the author her/himself), the PR may be merged. If a PR is not merged within 7 calendar days of the last activity (comment or commit) on it, the author may self-merge the PR at that point.

1. All discussions happen in the open, via issues and PRs. If there are discussions happening elsewhere, please bring them into issues and PRs.

1. In keeping with guideline #1, all changes to this file (`CONTRIBUTING.md`) must also be made via a PR. This PR will require a +1 comment from at least one core contributor from each organization before it is merged.

## Core Contributors

* A small set of people are designated as Core Contributors on this project. These people are expected to be frequent contributors and reviewers on this project.

* The current core contributors (and their respective organizations) for this project are, in alphabetical order of last name:
   * Glen Campbell (Rackspace), 
   * Jamie Hannaford (Rackspace), and 
   * Shaunak Kashyap (Rackspace)

* From time to time, core contributors may be added or removed from this project, depending on their recent availability (contributions and/or reviews) to the project.

* To suggest a change to the list of core contributors, any contributor - core or not - may submit a PR with the change to the list of contributors above and an explanation for the proposed change. Per the last point in the Contributing Guidelines section above, this PR will require a +1 comment from at least one core contributor from each organization before it is merged.

* When core contributors are added to the list above, they will be given write access to this repository so they may merge PRs.

* When core contributors are removed from the list above, their write access to this repository will be revoked. They may still submit PRs but not merge them.

## Design Decisions

Here are the major design decisions for this project. If a design decision has been made, the item below links to a page detailing the design. If a design decision is pending, the item below links to an issue with the assignee accountable for that decision.

* Capturing user requirements in a testable fashion
* Service layer
* REST layer
* Transport layer
* Parameter passing
* OOP visibility of methods and properties
* Vendor extensions

**IMPORTANT**: To ensure consistency of design across the SDK, each item in the list above MUST be a cross-cutting design decision (as opposed to a "vertical" or "functional" design decision - e.g. design of a particular service).

## Coding Conventions

All code in this project must conform to [PSR-2](http://www.php-fig.org/psr/psr-2/).
