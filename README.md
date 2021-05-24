# Better unit tests for Invariant Risk Minimization

Compared to orginal [IRM paper](https://arxiv.org/abs/1907.02893v1), we add:
- Scale parameters and show that IRM particularly suffers from very mild changes
- We added a simple ERM implementation based on sgd and verifies that ERM doesn't suffer these mild changes.

