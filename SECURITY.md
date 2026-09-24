# Security Policy

## Reporting a Vulnerability

If you have found or suspect to have found a vulnerability in Neurobagel, please **do not** report it through **public** GitHub issues, discussions, or pull requests, to avoid putting users at risk before a fix is available.

Instead, please report it privately using one of the following methods:
1. **GitHub's private vulnerability reporting:** Navigate to the `Security and quality` tab of the affected repository, and click `Report a vulnerability`.
2. **Email:** If you are unable to use GitHub's reporting tool, please email your findings to [sebastian.urchs@gmail.com](mailto:sebastian.urchs@gmail.com).

Either method will send the report directly and privately to the Neurobagel maintainers – it is not visible publicly until we agree to disclose it.

To help us triage and fix the issue quickly, please include as many details as possible in your report, such as:

- The affected component (e.g., API endpoint, CLI command, UI element) or specific section of code if available, and the version/commit
- A description of the vulnerability and its potential impact
- Steps to reproduce the vulnerability
- Any relevant screenshots, request/response examples, or logs
- Suggested mitigation or fix, if you have one

Please avoid testing the vulnerability against production Neurobagel nodes you don’t own beyond what's needed to demonstrate the issue, and use a local [quickstart deployment ](https://neurobagel.org/user_guide/getting_started/#quickstart-recipe) for reproduction wherever possible.

## Supported Versions

Neurobagel repositories continually receive security updates. We recommend that users maintain a reasonable upgrade plan that follows current releases of tools.

Unless noted otherwise, only the **latest released version** (or `main` branch) of each repository is supported with security fixes. Older tagged releases and Docker image tags are generally not patched retroactively.

## What to Expect

- We aim to acknowledge new reports within **7-10 business days**.
- We'll keep you updated as we investigate and work on a fix.
- Timelines depend on severity and complexity, and Neurobagel is maintained by a small team, so we appreciate your patience!

## Scope

This policy covers vulnerabilities in code and configuration maintained in repositories under the [Neurobagel GitHub organization](https://github.com/neurobagel). Issues in third-party dependencies should generally be reported upstream, but let us know too if it affects Neurobagel users directly (e.g., a vulnerable pinned dependency version).

Please note, we do not operate a bug bounty program. However, we deeply appreciate any contributions that guide us towards building a better and safer project.

Thank you for helping keep Neurobagel and its users safe.
