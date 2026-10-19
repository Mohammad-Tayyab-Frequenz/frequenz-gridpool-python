# Frequenz Gridpool Library Release Notes

## Summary

<!-- Here goes a general summary of what this release is about -->

## Upgrading

- Requires `frequenz-microgrid-component-graph` 0.6, which stops clamping the consumer
  and producer formulas. `ComponentGraph.consumer_formula()` and
  `ComponentGraph.producer_formula()` can now return values previously pinned
  to zero: a negative consumer total, or a positive producer total.

## New Features

- Resolve the `AC_ENERGY_ACTIVE`, `AC_ENERGY_ACTIVE_CONSUMED`, and
  `AC_ENERGY_ACTIVE_DELIVERED` formulas to `AC_POWER_ACTIVE` when no explicit
  energy formula is configured. This avoids duplicating topology formulas in
  generated microgrid configuration.

## Bug Fixes

<!-- Here goes notable bug fixes that are worth a special mention or explanation -->
