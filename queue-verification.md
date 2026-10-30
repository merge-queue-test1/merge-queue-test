# Controlled merge-queue rejection candidate

Do not merge. This harmless documentation-only PR verifies that the required API regression tests check runs on merge_group and prevents merging when it fails. The test workflow runs a pinned, known-green application snapshot and deliberately exits nonzero on merge_group only. Close this PR after collecting evidence.
