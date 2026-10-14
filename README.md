# gate-probe

Probe repository for the platform behaviour that a merge-gate RFC depends on.
It holds no product code. Each probe and its observations are recorded outside this repository.

Branches:

- `main`: default branch. Holds doorbell workflows and stub files only.
- `github-gate`: holds the trusted gate workflow definitions.
- `integration/alpha`: a track branch protected by a merge queue.
