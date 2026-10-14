# Frequenz Gridpool Library Release Notes

## Summary

<!-- Here goes a general summary of what this release is about -->

## Upgrading

- Requires `frequenz-microgrid-component-graph` 0.6, which stops clamping the consumer
  and producer formulas. `ComponentGraph.consumer_formula()` and
  `ComponentGraph.producer_formula()` can now return values previously pinned
  to zero: a negative consumer total, or a positive producer total.

## New Features

<!-- Here goes the main new features and examples or instructions on how to use them -->

## Bug Fixes

<!-- Here goes notable bug fixes that are worth a special mention or explanation -->
