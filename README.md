# RV32 Digital Chip Design Repository

This repository provides a clean starting point for RV32-class digital chip design projects. It organizes the typical assets required for RTL development, verification, and documentation so that new projects can begin with a clear structure.

## Repository Layout

- `rtl/` – Synthesizable RTL implementations of the core and peripheral blocks.
- `tb/` – Testbenches, verification components, and stimulus generators.
- `sim/` – Simulation configuration files, wave scripts, and regression setups.
- `constraints/` – Timing, floorplanning, and synthesis constraint files.
- `ip/` – External or third-party IP blocks integrated into the design.
- `scripts/` – Utility scripts for build, lint, synthesis, and verification flows.
- `docs/` – Project documentation, specifications, and onboarding material.

## Getting Started

1. Review `docs/environment_setup.md` for tool installation and environment configuration instructions.
2. Populate the `rtl/` and `tb/` directories with your design sources and verification code.
3. Capture project-specific processes, coding guidelines, and architecture notes under `docs/`.
4. Track changes with Git and keep documentation up to date as the design evolves.

## Contribution Guidelines

See `CONTRIBUTING.md` for coding style conventions, commit message format, and review expectations.

## License

Add your preferred open-source or proprietary license in a `LICENSE` file before distributing the project.
