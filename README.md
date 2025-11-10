## 🐛 `unconfig` Bug Reproduction

### Description

After updating `unconfig` to version **7.4.0**, `taze` cannot load certain configs, specifically those that export both default and named exports simultaneously.

### Steps to Reproduce

1. Execute `pnpm upd` to update dependencies with `taze`.
2. Look at the `taze` output.
