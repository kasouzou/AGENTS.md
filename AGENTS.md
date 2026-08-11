# AGENTS.md - Universal Agent Operational Guidelines

## 1. Core Principles
- **Context Awareness**: Always read and understand the existing code, architecture, and context before making changes.
- **Loose Coupling and Encapsulation**: Design modules to be loosely coupled and properly encapsulated, with clearly defined responsibilities.
- **Code Integrity**: Do not remove existing comments when modifying code; preserve all comments found in the original source.
- **Security and Quality**: Implement robust error handling, adhere to security best practices, select efficient algorithms, and comply with platform requirements (such as store review guidelines and proper permission management).
- **Minimal Diff**: Make targeted, precise changes. Do not refactor or reformat unrelated files or code blocks.
- The app must support at least two languages: Japanese and Englis.

## 2. Standard Workflow
1. **Analysis**: Search for and examine relevant files, type definitions, and existing architectural patterns.
2. **Planning**: Formulate a concise, step-by-step implementation plan before editing any files.
3. **Execution**: Write clean, maintainable, and readable code that aligns with the project's existing coding style.
4. **Verification**: Ensure code quality by performing type checks, linting (static analysis), and relevant tests.
5. **Commit**: Create a Git commit upon completion of the implementation and verification.

## 3. Git Operations
- **Mandatory Local Commits**: Upon completing an assigned task or implementation, create a proper Git commit with a clear, detailed commit message.
- **No Unauthorized Pushes**: Do not execute `git push` automatically or at your own discretion. Always wait for explicit instructions from the user before pushing to the remote repository. - **Write commit messages in Japanese**

Ensure there is a section in the root directory for recording implementation logs.
Please use the following format for the implementation log:
# Implementation Log: [Feature Name / Task Name]

- **Date**: YYYY-MM-DD HH:MM
- **Status**: [In Progress / Completed / Blocked]
- **Target Files**: `lib/features/...`, `test/...`

## 1. Goal & Context
- Briefly describe the purpose and requirements of the implementation or modification.

## 2. Changes Made
- [x] **`path/to/file_a.ext`**: Summary of logic changes or additions
- [x] **`path/to/file_b.ext`**: Details regarding added or modified error handling

## 3. Key Decisions & Rationales
- Reasons for choosing specific designs, libraries, or algorithms
- How existing comments or design principles were maintained or taken into account
