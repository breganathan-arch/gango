# gango

A starting point for organizing an existing project and tracking its development on GitHub.

## Status

This repository currently contains documentation and project placeholders. Its intended purpose, programming language, and application requirements have not yet been confirmed. There is no runnable application, dependency setup, or automated test suite yet.

## Project layout

```text
gango/
├── README.md
├── .gitignore
├── CONTRIBUTING.md
├── docs/
│   ├── project-brief.md
│   └── getting-started.md
├── src/
│   └── README.md
├── tests/
│   └── README.md
└── .github/
    ├── ISSUE_TEMPLATE/
    │   ├── bug_report.md
    │   └── improvement.md
    └── pull_request_template.md
```

The folders are starting points. Preserve your existing code's layout when importing it; a framework may require files at the repository root.

## Next steps

1. Fill in [the project brief](docs/project-brief.md) with the goal, intended users, and existing code to bring in.
2. Follow [the setup and import guide](docs/getting-started.md) to add your code.
3. Replace this README's status with verified installation, configuration, run, and test instructions.
4. Open an [issue](https://github.com/breganathan-arch/gango/issues/new/choose) for each improvement, including a clear completion condition.
5. Use a branch and pull request for each change. See [CONTRIBUTING.md](CONTRIBUTING.md).

## Configuration and licensing

Keep passwords, API keys, and private data out of this public repository. The starter ignore file excludes common local environment files and generated files; review it against your actual project before importing code. An ignore file does not remove files already tracked by Git.

A license has not been chosen. Confirm ownership and third-party requirements before adding a license or distributing imported code.
