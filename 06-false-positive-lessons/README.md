# False-Positive Lessons

This folder contains examples of suspicious code paths that were checked and eliminated.

The goal is to show verification discipline.

A weak finding is not treated as a bug until it passes:
- reachability
- attacker benefit
- broken rule
- before → break → after
- missing or weak guard check

False positives are not wasted work. They show how weak findings are tested, killed, and turned into better audit judgment.
