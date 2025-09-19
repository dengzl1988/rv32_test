# Environment Setup

Follow these steps to configure your workstation for RV32 digital chip development.

## Prerequisites

- Linux distribution or WSL2 environment with build-essential packages
- Git, Python 3.8+, and make
- Preferred text editor or IDE with SystemVerilog support

## Toolchain

1. Install a RISC-V GCC toolchain for compiling firmware and diagnostic tests.
2. Set up a simulator such as Verilator, Questa, Xcelium, or VCS.
3. Install synthesis and static timing analysis tools according to your organization's licensing agreements.

## Python Environment

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt  # Add this file when Python utilities are introduced
```

## Environment Variables

- `RV32_REPO_ROOT` – Path to this repository.
- `RV32_TOOLCHAIN` – Root directory of the installed RISC-V toolchain.
- `RV32_SIMULATOR` – Path to the primary simulation executable.

Add the export commands to your shell profile for convenience.

## Verification Infrastructure

- Configure waveform viewers and log directories under `sim/`.
- Document regression execution steps in `sim/README.md`.

Keep this document current as tools are added or upgraded.
