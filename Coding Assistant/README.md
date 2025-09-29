# CodeMentor AI Prompt

This repository contains a detailed prompt for configuring a large language model (LLM) to act as `CodeMentor`, an expert-level software architect and security-focused programming assistant.

The full prompt can be found in [`CodeMentor.md`](CodeMentor.md).

## Overview

`CodeMentor` is designed to assist computer science students and developers by not only providing correct answers but also explaining the underlying principles, best practices, and security considerations. The persona is that of an expert mentor who prioritizes teaching over simple task completion.

## Core Principles

The `CodeMentor` prompt is built on several core directives:

1.  **Security-First Mindset**: Proactively identifies and mitigates security vulnerabilities, referencing standards like the OWASP Top 10.
2.  **Explain the "Why"**: Never provides code or solutions without a clear explanation of the methodology and reasoning.
3.  **Clarity and Precision**: Delivers complete, working code snippets and commands, avoiding pseudocode.
4.  **Language-Agnostic Expertise**: Capable of providing idiomatic code across various languages and frameworks.

## How to Use

To interact with an AI configured with this prompt, you should use specific prefixes to define the nature of your request.

### Context Management

-   **`[Context]:`**: Use this block at the beginning of a new task to provide necessary background information, such as programming language, goals, and constraints.
-   **`[New Task]`**: Use this keyword to signal a complete switch to a new, unrelated problem.

### Interaction Modes

Prefix your prompts with one of the following modes to tailor the AI's response:

-   **`[Architect]:`**: For high-level system design, software patterns, and architectural questions.
-   **`[Code]:`**: To request a specific, working piece of code for a defined problem.
-   **`[Debug]:`**: Provide code and an error message to get an analysis and a corrected version.
-   **`[Secure]:`**: For security audits of code or configurations.
-   **`[Review]:`**: For a general code review focusing on style, efficiency, readability, and security.
-   **`[Explain]:`**: To ask for clear explanations of concepts, algorithms, or technologies.

## Output Format

`CodeMentor` is instructed to provide responses in Markdown, using proper code blocks with language identifiers and KaTeX for mathematical notation.