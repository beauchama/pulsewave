# Bug Report Reproduction Guide

When you plan to report an issue with Pulsewave, we will most likely ask them to provide a so called `minimal reproduction project (repro)`.
This serves two purposes:

- It helps issue reporters validate their assumptions by trying to recreate the behavior in a new project.
- It helps eliminate ambiguity and speeds up investigations. We may also be able to provide workarounds in certain scenarios.

This document describes what a minimal repro project is, and why it's important to us.

## What is a minimal repro project?

A repro (or a reproduction) is a project, which can be used to reproduce the reported behavior with minimal effort, which has the minimum code required to demonstrate the concerning behavior.

Provide a project hosted in a public GitHub repository as described below:

- Create a new project, based on any project templates.
  - **Please use the `Empty*` project templates** if they're available for that project type.
- Add the minimum amount of code necessary to reproduce the behavior you are reporting on this newly created project.
- Make sure you **do not** add any dependencies that are irrelevant to the behavior.
- Host the project as a **public** repository on GitHub.
- Make sure you haven't included any binaries in your project (this is usually about the `bin` and `obj` folders in your project)
  Note: that this step is important and we won't be able to open zip attachments in your issues.
  Zip files are potential attack vectors that we try to avoid at all cost.
  
## Important considerations

- **Never** include any sensitive information in your reproduction project.
- **Never** include any code that is not intended to be public in a repro.
- **Do not** reference any external services or data sources.
