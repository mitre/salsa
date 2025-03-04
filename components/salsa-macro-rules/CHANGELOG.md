# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.1.1](https://github.com/mitre/salsa/compare/salsa-macro-rules-v0.1.0...salsa-macro-rules-v0.1.1) - 2025-03-04

### Other

- Drop clone requirement for accumulated values
- Remove unnecessary `current_revision` call from `setup_interned_struct`
- Skip memo ingredient index mapping for non enum tracked functions
- Trade off a bit of memory for more speed in `MemoIngredientIndices`
- Introduce Salsa enums
- Track revisions for tracked fields only
- Fix bad-hash with in-place update
- Automatically clear the cancellation flag when cancellation completes
- Require mut Zalsa access for setting the lru limit
- Split off revision bumping from `zalsa_mut` access
