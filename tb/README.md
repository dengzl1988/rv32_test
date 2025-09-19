# Testbench Directory

This directory stores verification code, reference models, and coverage infrastructure for the RV32 design.

## Suggested Structure

- `unit/` – Block-level testbenches targeting individual modules.
- `system/` – Chip-level testbenches with bus functional models and firmware images.
- `uvm/` – UVM components, sequences, and configuration files (if applicable).

## Best Practices

- Strive for self-checking tests with clear pass/fail reporting.
- Document how to run simulations and regressions in `sim/README.md`.
- Version control only the sources and configurations required to reproduce results.
