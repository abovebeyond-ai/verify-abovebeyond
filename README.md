# Verify Above Beyond's agent evidence, on your own account

Above Beyond publishes what its agent Elixir did in clients' code as signed, chained, anchored
records, against the Advanced AI Society's Proof-of-Control draft. The standard asks, in row
8.1.5, for a verification run recorded by a party outside the operator, with public inputs
and no credential of theirs. This repository is that run, as a job anyone can own.

## Fork it, switch Actions on, done

1. Fork this repository.
2. In your fork, open Actions and enable workflows.
3. Run `verify` once by hand, or wait for the daily run.

From then on your account runs, on GitHub's machines, with nothing from Above Beyond:

- the evidence, from the public copy `abovebeyond-ai/control-evidence`;
- the checker, from `abovebeyond-ai/control` at a pinned release;
- the gateway's key, from the identity log at abovebeyond.ai, not from the evidence;
- the identity log read back from the public ledger, so there can be only one history.

Each run writes `verdicts/<date>.md` into your fork: the verdict, the run id, the release,
the commit of the evidence, the key, and the checker's own lines. That file, under your
account, is the record. Above Beyond cannot write to it.

## What `holds` means, and does not

Holds: no record was altered after the gateway wrote it; every action has its request,
effect and result; every working replays from the material beside it; the key that signed
was made inside the attested machine the chip's report names; the chain extends what was
pinned at DigiCert and on Hedera; and the identity log you see is the one first published,
version by version.

It does not mean any repair was correct, or that a pull request is safe to merge. It says
what the agent did, under which rule, and that nobody rewrote the account of it.

## When Above Beyond runs this itself

The same job runs daily in this repository, under Above Beyond's own account. That is a
public run on GitHub's infrastructure with no credential of theirs, and it is not an
outsider's run: the account is theirs. Their conformance statement says exactly that, and
the row stays open until someone else's fork has a verdict in it.

Draft standard: https://github.com/AAI-Society/ov-poc-standard. Conformance statement:
https://github.com/abovebeyond-ai/control/tree/main/conformance.
