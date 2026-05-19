# Proof Standard

A finding must show:

- reachable path
- attacker benefit
- broken rule or invariant
- before → break → after
- missing or weak guard
- clear fix

## Minimum Proof Standards

### Repetition

First call succeeds → second call succeeds → extra value/control/outcome gained

### Authority

Wrong caller calls → function succeeds → protected state/control changes

### Order / Control

State should become safe first → value/control leaves too early → old unsafe state can be reused

### Data

Bad/stale/manipulated data enters → system trusts it → value/control/outcome changes wrongly
