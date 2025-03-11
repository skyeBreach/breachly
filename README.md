<!-- markdownlint-disable-file MD041 -->
<!-- SCRATCH: Add as many badges as possible from the badge list -->
<!-- #region(collapsed) README Header -->
<p align="center">
    <img
        alt="BreachOps-Task"
        src="./assets/logo_150x150.png"
        width=125px
        align="center"
    />
    <h1 align="center">BreachOps-Task</h1>
</p>
<p align="center">Breach through your project blockers and manage your tasks effortlessly with BreachOps-Task!</p>
<p align="center">
    &lt;<a href="https://github.com/skyeBreach/breachops-task">Website</a>&gt;
    <span>&nbsp;&#8226;&nbsp;</span>
    &lt;<a href="./docs/pages/index.md">Documentation</a>&gt;
    <span>&nbsp;&#8226;&nbsp;</span>
    &lt;<a href="./docs/pages/roadmap.md">Roadmap</a>&gt;
    <span>&nbsp;&#8226;&nbsp;</span>
    &lt;<a href="./CONTRIBUTING.md">Contributing</a>&gt;
    <span>&nbsp;&#8226;&nbsp;</span>
    &lt;<a href="./docs/pages/faq.md">FAQ</a>&gt;
</p>
<p align="center">
    <!-- TODO: Badges
            - [x] TODO: License
            - [ ] TODO: Release
            - [ ] TODO: Cargo**
            - [ ] TODO: Docs**
            - [ ] TODO: Commit Activity*
            - [x] TODO: Stars
            - [ ] TODO: Downloads*
            - [ ] TODO: Build Pipeline
            - [ ] TODO: Test Pipeline
            - [ ] TODO: Chat/Discord*
    -->
    <img
        alt="License Badge"
        src="https://flat.badgen.net/github/license/skyeBreach/breachops-task"
    />
    <img
        alt="GitHub Stars Badge"
        src="https://flat.badgen.net/github/stars/skyeBreach/breachops-task"
    />
</p>
<!-- #endregion -->

> [!CAUTION]
> **Early Development Warning**
>
> Due to BreachOps-Task being very early in development it is currently **NOT** recommended to use it in any production
> environment.
>
> If you choose to ignore the above **WARNING**, then you do so at your **OWN** risk.

BreachOps-Task is a personal project and task management command-line tool created to help you breach through your
project blockers with minimal effort.

BreachOps-Task has been designed to be as developer-friendly, configurable, and flexible as possible; it achieves
these intended goals whilst keeping a good level portability, high performance, and its compiled binaries minimal in
size.

BreachOps-Task utilizes the Rust language, for its runtime systems, to achieve high performance whilst still being
memory-safe and largly portable. When initially designing BreachOps-Task we did examine other options for runtime
languages but most did not meet our criterion, a list of these languages and our reasoning for not using them can be
found in our [FAQ](docs/faq#why-didnt-you-choose-x-language).

BreachOps-Task is inspired by several other command-line, TUI, and GUI task/project management tools, so if BreachOps-Task
does not meet your criteria then maybe one of [these projects](#acknowledgements) will.

## Table of Contents <!-- omit from toc -->

- [Features](#features)
- [Installation](#installation)
    - [Cargo](#cargo)
- [Configuration](#configuration)
- [Documentation](#documentation)
- [Contributing](#contributing)
- [Feedback](#feedback)
- [Roadmap](#roadmap)
- [Authors and Contributors](#authors-and-contributors)
- [Acknowledgements](#acknowledgements)
- [License](#license)

## Features

BreachOps-Task supports the following, non-comprehensive, list of features:

- Free and open-source
- Developer-friendly
- Highly configurable
- Multiple configuration methods
- Lightweight and performant
- Allows for system and project wide management
- And more...

Due to the early stage in development, the features listed here are the intended features that will be included with the
`v1.0.0` release. For a full list of planned features and where they are in development please refer to the
[roadmap](#roadmap) section.

## Installation

As BreachOps-Task is still early in development it has a limited number of installation options, we intend to improve
this later in its life cycle.

BreachOps-Task can currently be installed via the following methods:

### Cargo

> [!IMPORTANT]
>
> This method requires that you have [Cargo](https://doc.rust-lang.org/stable/cargo/) installed.
>
> Installation instructions for Cargo can be found [here](https://doc.rust-lang.org/stable/cargo/getting-started/installation.html)
>

Use the following command to install via Cargo:

```shell
cargo install --locked breachops-task
```

Once Cargo finishes running you can start using BreachOps-Task.

## Configuration

Currently, due to its early stage of development, BreachOps-Task can not be configured.

Once the systems required to configure BreachOps-Task are implemented this section will be updated with the relevant
information on how to do this.

## Documentation

Documentation can currently be found in the [docs](docs/index.md) folder of this repository.

Once we have the documentation hosted externally this section will be updated and will provide the relevant links.

## Contributing

Due to BreachOps-Task being in an early stage of development we are currently not accepting contributions. Once we have
decided that this project is mature enough to receive any contributions this section will be updated accordingly.

Please see our [contributing](CONTRIBUTING.md) doc for the current ways you can contribute to BreachOps-Task.

All contributions must adhere to this projects [code of conduct](CODE_OF_CONDUCT.md).

## Feedback

> [!NOTE]
>
> Whilst we try to read and reply to all feedback we feel it necessary to state that we cannot promise this and may miss
> some.
>
> We appreciate your understanding and thank you for your patience!

To provide feedback, present an idea, ask a question, or show off your usage please feel free to create a
[discussion](https://github.com/skyeBreach/breachops-task/discussions).

If you find a bug or want to request a feature you can currently do so via our issue tracker on
[GitHub](https://github.com/skyeBreach/breachops-task/issues).

You can also email us to provide direct feedback at <skyebreach@proton.me>.

## Roadmap

Please refer to the [roadmap](.dev/docs/roadmap-old.md) for a full list of planned features.

## Authors and Contributors

BreachOps-Task is primarily maintained by the following individuals,

- [@skyeBreach](https://github.com/skyeBreach) <skyebreach@proton.me>

Please refer to the [authors](docs/authors.md) document for a full list of contributors and their details.

## Acknowledgements

A command-line tool for managing tasks and/or tracking time is obviously not a novel or new idea, so it may come as no
surprise that BreachOps-Task was inspired by other similar projects. We feel it is only right to acknowledge and give
credit to these projects, as we know that BreachOps-Task will not suit everyones needs.

BreachOps-Task has taken inspiration from the following projects,

- [Taskwarrior][taskwarrior] - A Free and open source command line task manager. Flexible, fast, efficient, and unobtrusive.
- [Taskchampion][taskchampion] - Implements the task storage and synchronization behind Taskwarrior.
- [TTDL][ttdl] - A CLI tool to manage todo lists in todo.txt format.
- [Todoctor][tododoctor] - CLI tool to analyze and report TODO comments in JavaScript and TypeScript Git repositories.
- [Taskbook][taskbook] - Tasks, boards & notes for the command-line habitat.
- [Taskwarrior-deluxe][taskwarrior-deluxe] - A wrapper for Taskwarrior that adds directory based tasks, and fancier output.
- [dstask] - A personal task tracker with git-based sync and markdown notes per task.
- [Dooit][dooit] - A TUI todo manager that features interactive & beautiful UI, fully customizability, and extensibility.
- [Taskell][taskell] - Command-line Kanban board/task manager with support for Trello boards and GitHub projects.
- [Kanbn][kanbn] & [vscode-kanbn][vscode-kanbn] - CLI and VSCode based kanban, that stores tasks to markdown files.
- [Timewarrior][timewarrior] - CLI time tracking by the Taskwarrior team.
- [Wakapi][wakapi] - A minimalist, self-hosted WakaTime-compatible backend for coding statistics.
- [Bartib][bartib] - An easy to use time tracking tool for the command line, that utilizes plaintext file for storage.
- [Zeit, erfassen][zeit] - A command line activity & time tracker written in Go, focused on simplicity and integrability.
- [eureka] - A CLI tool that allows you to quickly write down an idea using your preferred editor, and sync'd to a git repo
- [nb] - A command line and local web note‑taking, bookmarking, archiving, and knowledge base application
- [buku] - A powerful bookmark manager and a personal textual mini-web.

## License

&copy; 2025 Skye Benson. All Rights Reserved.

BreachOps-Task is distributed under the terms of the MIT license.<br/>
See [LICENSE](LICENSE) for more information on the details of the license.

<!-- #region(collapsed) Links -->
<!-- For more info see, https://www.markdownguide.org/basic-syntax/#reference-style-links -->

<!-- #region(collapsed) Acknowledgement -->

[taskwarrior]: https://github.com/GothenburgBitFactory/taskwarrior
[taskchampion]: https://github.com/GothenburgBitFactory/taskchampion
[ttdl]: https://github.com/VladimirMarkelov/ttdl
[tododoctor]: https://github.com/azat-io/todoctor
[taskbook]: https://github.com/klaudiosinani/taskbook
[taskwarrior-deluxe]: https://github.com/nojhan/taskwarrior-deluxe
[dstask]: https://github.com/naggie/dstask
[dooit]: https://github.com/dooit-org/dooit
[taskell]: https://github.com/smallhadroncollider/taskell
[kanbn]: https://github.com/basementuniverse/kanbn
[vscode-kanbn]: https://github.com/basementuniverse/vscode-kanbn
[timewarrior]: https://github.com/GothenburgBitFactory/timewarrior
[wakapi]: https://github.com/muety/wakapi
[bartib]: https://github.com/nikolassv/bartib
[zeit]: https://github.com/mrusme/zeit
[eureka]: https://github.com/simeg/eureka
[nb]: https://github.com/xwmx/nb
[buku]: https://github.com/jarun/buku

<!-- #endregion -->

<!-- #region(collapsed) License -->

<!-- #endregion -->

<!-- #endregion -->
