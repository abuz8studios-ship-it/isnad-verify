# Proof ledger spec (v1)
Each entry: date | claim | witness (url/cmd) | transmitter | gap | status_url | verdict.
Verdicts: VERIFY_OK / PARTIAL / UNREAD / CUT (killed before shipping).
Rule: a claim without a status_url is not a claim.
