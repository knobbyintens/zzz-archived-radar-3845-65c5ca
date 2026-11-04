# harbor-sql - overview

## Purpose

This project packages a narrow slice of engineering plumbing that several teams kept
re-implementing. The goal is to make the common path obvious and the uncommon path
explicit.

## Design notes

1. Configuration is declarative and validated at start-up.
2. Failures are surfaced with a stable error vocabulary.
3. Every public entry point has a matching test.
