# Contributing Guidelines

Thank you for your interest in contributing to this digital chip design repository. The guidelines below help maintain consistency and quality across the project.

## Workflow

1. Fork the repository or create a feature branch.
2. Make incremental commits with clear and descriptive messages.
3. Ensure simulations, lint checks, and other relevant flows pass before submitting changes.
4. Open a pull request and request reviews from maintainers.

## Coding Standards

- Prefer synthesizable, well-documented RTL in the `rtl/` directory.
- Follow the coding style defined in `docs/design_guidelines.md`.
- Include self-checking testbenches under `tb/` whenever possible.
- Keep scripts idempotent and provide usage instructions in headers or README files.

## Documentation

- Update `docs/` whenever architecture or interfaces change.
- Document new scripts and flows in `scripts/README.md`.
- Record assumptions, dependencies, and limitations alongside the relevant files.

## Commit Messages

- Use the present tense and describe what the change does.
- Reference issue numbers where applicable.
- Include additional context in the body when needed.

## Code Review

- Be open to feedback and iterate on review comments promptly.
- Provide rationale for design decisions to help reviewers understand the implementation.

By following these guidelines, we ensure a maintainable and collaborative environment for chip design development.
