# Design Guidelines

These guidelines encourage consistency and maintainability across RTL and verification code in the RV32 repository.

## General Principles

- Write clear, synthesizable SystemVerilog or Verilog with meaningful hierarchy boundaries.
- Prefer parameterization for reusable modules and to avoid magic numbers.
- Document assumptions and corner cases near the relevant code.

## RTL Coding Style

- Use `lower_snake_case` for signal names and `UpperCamelCase` for module names.
- Group related logic into `always_ff` and `always_comb` blocks.
- Reset signals synchronously unless design requirements dictate otherwise.
- Include assertions where possible to capture protocol expectations.

## Testbench Practices

- Develop self-checking testbenches with clear pass/fail criteria.
- Separate stimulus generation, scoreboard, and coverage components.
- Log important events to aid in debugging regressions.

## Version Control

- Commit generated files only if they are required for downstream tools.
- Use `.gitignore` entries to exclude build artifacts and simulation outputs.

Update these guidelines as the team aligns on detailed coding standards.
