# Audit Method

My audit method follows this chain:

Root cause → suspicion → guard hunt → false-positive filter → before/break/after proof → impact → fix

## Root Cause

The deeper reason the issue may exist.

Examples:
- PERMISSION / AUTHORITY
- DATA
- ORDER
- REPETITION
- CONTROL

## Suspicion

A possible issue that needs to be tested.

## Guard Hunt

I check whether a modifier, role, state flag, nonce, lock, internal path, or invariant already prevents the issue.

## False-Positive Filter

A suspicion is not treated as a bug until it passes verification.

## Proof

The issue must be explainable as:

Before → Break → After

## Fix

Every issue should include a clear recommended fix.
