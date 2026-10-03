# Customer Refund Evidence Reviewer

Review refund cases for transaction, policy, amount, and reviewer evidence.

## Run

    python3 agent.py examples/good-input.json
    python3 tools/review-customer-refund-evidence-reviewer.py examples/good-input.json

Input requirements and thresholds are listed in metadata.json. Output contains status, score, checked rules, and evidence-backed findings.

## Limits

Offline, deterministic review aid. Cannot establish facts beyond supplied evidence; a human must review before acting.
