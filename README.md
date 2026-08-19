<p align="center">
  <h1 align="center">Does Safety RL Work by Changing What Models Explore</h1>
  <p align="center"><strong>Separate exploration-shaping effects from other RL safety intervention mechanisms on small models.</strong></p>
</p>

---

## Overview

This repository implements experimental profiles for **Does Safety RL Work by Changing What Models Explore**. Config, caching, hooks, metrics, ablations, reporting, and CI support local pilots on small open-weight models.

Hypothesis (one line): Separate exploration-shaping effects from other RL safety intervention mechanisms on small models.

## Status

Shared infrastructure is in place; domain stages must pass harness validation before any measured claim.

| Command | Purpose |
|---|---|
| `make install-dev` | editable install + pinned requirements |
| `make test` | full unit suite |
| `make ci` | lint + test + typecheck |
| `make pilot` | end-to-end pilot profile |
