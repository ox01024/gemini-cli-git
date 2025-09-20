# Gemini CLI Git Extension

[简体中文](./README_zh.md)

This is a Gemini CLI extension that provides convenient Git commands to streamline your development workflow.

## Features

- **AI-powered commit messages**: Leverages Gemini's capabilities to generate conventional commit messages based on your staged changes.
- **Streamlined branching**: Quickly commit your changes to a new branch.
- **Integrated with Gemini CLI**: Seamlessly integrates into the Gemini CLI environment.

## Commands

This extension provides the following commands:

- `/git:review`: Review staged changes.
- `/git:commit`: Analyzes your staged Git changes and generates a descriptive commit message following the Conventional Commits specification.
- `/git:ctnb`: Commit staged changes to a new branch.

## Installation

Install the Git extension by running the following command from your terminal *(requires Gemini CLI)*:

```bash
gemini extensions install <URL_to_this_repository>
```

## Usage

You can invoke the commands directly from the Gemini CLI prompt:

To review staged changes:
```
/git:review
```

To generate a commit message for your currently staged changes:

```
/git:commit
```

To commit staged changes to a new branch:

```
/git:ctnb
```

## Legal

- License: Apache License 2.0