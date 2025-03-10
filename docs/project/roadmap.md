---
id: docs-roadmap
title: Product Plan and Roadmap
---

# Product Plan and Roadmap <!-- omit from toc -->

This document details BreachOps-Task' overall goals, the current implementation/release status, and
it's long-term plans.

> [!NOTE]
>
> In the future it is likely that this file will fall out of practice, once we finalize our project management systems.
> Once it does fall out of practice we will make sure to keep it here for historical sake, and convert this notice into
> a warning or caution.
>
> However even with this stated, it is unlikely to happen until we are close to, or past the v1.0 release, so for now we
> will act like this doc will out live us.
>

## Table of Contents <!-- omit from toc -->

- [Overview](#overview)
    - [Key Objectives](#key-objectives)
        - [Transparency](#transparency)
        - [Planning](#planning)
        - [Communication](#communication)
    - [How This Document Works](#how-this-document-works)
        - [Usage of the `Release and Build Status` Section and Table](#usage-of-the-release-and-build-status-section-and-table)
        - [Using the `Roadmap` Section](#using-the-roadmap-section)
- [Release and Build Status](#release-and-build-status)
    - [Status Table](#status-table)
- [Roadmap](#roadmap)
    - [v0.1 Release](#v01-release)
    - [v0.2 Release](#v02-release)
- [Contributing](#contributing)

---

## Overview

This document serves as the central reference for BreachOps-Task' development progress, goals, and future plans. It is
intended for internal developers, contributors, users, and stakeholders who want to understand the project's direction
and track its milestones.

To view a complete list of tasks that need to be completed for a given version, or generic tag (type, scope, etc),
please refer to the [task board](./task-board.md) document in the [project)](./_index.md) management directory. This
directory and more specifically document are used internally to keep track of any tasks, and their completion status,
that BreachOps-Task must complete and for a given release, aswell as tracking any ideas we have for the project.

### Key Objectives

This roadmap has been designed to achieve three distinct primary goals, which have been set to ensure that the
development of BreachOps-Task remains highly transparent, meticulously well-planned, and effectively communicated.

The following sections specify (in an in-depth manner) what we mean by each goal, why we feel the goal is important,
how we intend to accomplish the goal, and any requirements we have imposed to facilitate the achievement of the goal.

#### Transparency

We aim to maintain a high level of transparency with regards to the state of development for BreachOps-Task. To achieve
the this level of transparency we will provide:

- **Progress Updates:**         A clear high-level overview of the current status and future plans for the project.
- **Challenges and Blockers:**  Insight into any challenges we face, and any blockers that impede our progress.
- **Release Breakdowns:**       In-Depth breakdowns on any intended features or bug fixes included by a versioned
                                release.

By providing this information we hope to foster trust and align the goals of all interested parties, which will enable
the rapid and collaborative development of BreachOps-Task. We also hope that the type of development this level
of transparency foster's, is one that suites all interested parties and not just the project owners/stakeholders.

#### Planning

This roadmap will serve as a high-level guide/overview on both short-term and long-term plans that inform the
direction of our development efforts.

We intend for this high-level guide/overview to,

- **Guide Development:**    Provide a well defined direction for the internal team's design and implementation efforts.
- **Inform Community:**     Offer clarity for the community on the project's direction of development, i.e. the
                            end-users, external open-source contributors, internal development team, and stakeholders.
- **Align Member Goals:**   Ensure that the internal development team's objectives, long and short term, align with the
                            expectation of the community, and in general any interested party.

By taking this approach we hope to,

- Avoid feature creep, and maintain focus on important work packages.
- Minimize confusion among internal team members and open-source collaborators.
- Enable rapid, smooth, and efficient design/development of new features and bug fixes.
- Reduce any administrative overhead to allow our decision-making process to be maximally streamlined.

#### Communication

It is intended for this document to act as a single source of truth for the state of this project.

This document should present a high-level overview of how the development of the project has progressed, containing
information on,

- **Past Progress:**    How the project has evolved over time, from the initial to the most recent commit.
- **Current State:**    The present status of the projects design, development, and implementation.
- **Future Plans:**     The intended direction and goals for any upcoming release.

To provide this clear communication we will impose a set of requirements for this document. These requirements can be
summed up by the following principals,

- **Document Everything:**  Record and document all high-level design, development, and implementation processes.
- **Preserve Information:** Information must not be removed or intentionally obscured[^keep-info-except] once shared.
- **Frequent Updating:**    Information contained by the roadmap must be kept current in relation to latest development
                            status and future plans.

By upholding these requirements we will ensure seamless collaboration and coordination between all contributors, no
matter if they are a part of the internal development team or external open-source collaborators.

### How This Document Works

To help in navigating and using this roadmap, we provide the following high-level breakdown of its structure. This
breakdown should allow any interested party to easily decipher the document, and integrate it with their own tooling
systems.

This section should provide a clear guide on the usage of this document, in relation to the tracking and understanding
of this project's development processes.

#### Usage of the `Release and Build Status` Section and Table

The [`Release and Build Status`](#release-and-build-status) section provides a snapshot of the current state for each
supported, or immenent future release. Each release includes information on,

- **Release:**          The version number of the release (e.g. v0.1 or v0.1.1), the patch number should only included
                        for the `Stable` branch.
- **Branch:**           The release branch associated with the release version (e.g. N/A, Stable, Canary, Nightly).
- **Build Status:**     A markdown badge that displays the current success status for the release's build pipeline
                        (Unknown, Success, Failed), where unknown is used for a non-existent pipeline.
- **Testing Status:**   A markdown badge that displays the current success status for the release's automated testing
                        pipeline (Unknown, Success, Failed), where unknown is used for a non-existent pipeline.
- **Design Status:**    A text based  status for the design of any relevant features, and bug fixes to the version (Not
                        Started, In Progress, Completed).
- **Docs Status:**      A text based status of any relevant documentation updates for the release (Not Started, In
                        Progress, Completed).

This table is used to quickly reference and assess the status/progress of a specific supported build. Primarily this
table is used to identify any issues or areas that require attention.

#### Using the `Roadmap` Section

The primary and most important section for this document is the [Roadmap](#roadmap) section, which outlines planned
features, upcoming bug fixes, and provides context for a specific release.

Each release roadmap is further split up into the following sections,

- **Status:** Completion status for this release, which is defined by one of the following,
    - Backlog
    - Planned
    - In Design
    - In Progress
    - In Testing
    - In Review
    - Completed
- **Themes:** List of high-level focus areas for the release.
- **Overview:** Semi-detailed high-level overview/description for what this feature entails, and why its needed.
- **Goals:** All goals that this release intends to achieve.
- **Non-Goals:** Any needed clarification on what is considered out of scope for this release.
- **Features:** Full list of features that this release will include, and their current status.
- **Fixes:** Comprehensive list of bugs that either have been fixed, or are intended to be fixed by this release.

By using this structure we hope to ensure that most, if not all, readers can easily understand what is being worked on,
what they can look forward, and what a specific previous/current/upcoming release includes.

---

## Release and Build Status

This section specifies a build status for the most up-to date release(s), aswell as any status of the pipelines the
build utilizes (e.g. testing, documentation, etc).

> [!NOTE]
>
> Due to the early development stage that this project exists in, this table may not be up to date, or show any majorly
> useful information.
>
> This table has largely been included to act as a placeholder, until releases have occurred. Once we have successfully
> released a versioned build, we will update this table to contain accurate data asssocitated with that build.

### Status Table

The following table is used to specify the build status' for all currently supported builds, and any upcoming release's
that may be still in development. Each release is summarized within the table, by its number, branch build status,
design status, etc; The relevant pipelines for each release has been included as a markdown badge, that displays the
current pipeline status.

| Release  | Branch  | Build Status | Design Status  | Documentation Status | Testing Status |
| -------- | ------- | ------------ | -------------- | -------------------- | -------------- |
| v0.1.0   | N/A     | Unknown      | In Progress    | Not Started          | Not Started    |
| v0.2.0   | N/A     | Unknown      | Not Started    | Not Started          | Not Started    |

---

## Roadmap

This section outlines the intended features and fixes for each release. Changes listed here are not guaranteed and may
shift based on scope, resources, or unforeseen challenges.

### v0.1 Release

This subsection details the goals, themes, and planned features for the `v0.1` release. It explains what the team aims
to achieve in this release and what readers can expect.

**Status:** In Progress

**Themes:**

- Core Functionality
- Implementation of Foundational Systems
- Baseline Design and Documentation

**Goals:**

- Establish a basic project structure
- Create a base set of docs, that should be used to define the project
- Implement basic project management systems
- Implement rudimentary logging, and error management
- Implement a toy command-line parsing application

**Non-Goals:**

- Indepth CLI Features (e.g. subcommands, interactivity)
- Well defined project, Collaboration, and development documentation
- Build and Release Tooling
- Working Task Management CLI
- Efficient and Performant Data Storage
- Useful Logging and Error Management

**Features:**

- Basic Application Flow
- Initial Project Documentation
- Skeleton for the CLI
- Implement a basic logging object
- Implement rudimentary error management

**Fixes:**

- N/A: This is the initial version, so there are no bugs from prior versions.

### v0.2 Release

This subsection details the goals, themes, and planned features for the `v0.2` release. It explains what the team aims
to achieve in this release and what readers can expect.

**Status:** Planned

**Themes:**

- Project Tooling and Utility Scripts
- Build and Deployment Systems
- Code Quality
- Community Collaboration

**Goals:**

- Improve the development workflow by introducing utility scripts for project setup, maintenance, and automation.
- Establish robust build and deployment pipelines to ensure consistent and reliable releases.
- Enhance code quality through the implementation of linting, formatting, and testing tools.
- Foster community collaboration by providing clear contribution guidelines and documentation.

**Non-Goals:**

- Adding user-facing features or advanced task management capabilities.
- Implementing configuration options for end-users.
- Integrating with external tools or services.

**Features:**

- Automated build and testing pipelines using CI/CD tools (e.g., GitHub Actions).
- Utility scripts for tasks such as dependency management, code formatting, and project setup.
- Integration of linting and formatting tools (e.g., clippy, rustfmt) to enforce code quality standards.
- Basic contribution guidelines and templates for issues and pull requests.

**Fixes:**

- N/A: This release focuses on tooling and infrastructure improvements rather than bug fixes.

---

## Contributing

This section explains how contributors can get involved in the development of BreachTaskOps. It provides links to
resources and guidelines for contributing, making it easy for new contributors to get started.

We welcome contributions from the community! If you'd like to help with BreachTaskOps, here's how you can get started:
- **Good First Issues**: Check out the [task board](/docs/dev/pm/task-board.md) for beginner-friendly tasks.
- **Feature Requests**: Open an issue to suggest new features or improvements.
- **Code Contributions**: Follow our [contribution guidelines](/docs/dev/contributing.md) to submit pull requests.

---

> [!TIP]
>
> To view the latest updates, head over to the [task board](./pm/task-board.md) doc or checkout our community.
>

[^keep-info-except]:    An exception to this principal is when information has been provided in error, such as a
                        spelling error, or accidental inclusion of non-public information.
