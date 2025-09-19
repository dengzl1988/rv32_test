# RTL Source Directory

Place synthesizable SystemVerilog or Verilog modules for the RV32 design in this directory. Organize submodules into subfolders as needed (e.g., `core/`, `memory/`, `peripherals/`).

## Guidelines

- Keep module interfaces documented using comments or separate markdown files.
- Provide default parameter values and describe configuration options.
- Include assertions or cover properties to help detect protocol violations early.

Remember to update `docs/architecture.md` when significant RTL changes are introduced.
