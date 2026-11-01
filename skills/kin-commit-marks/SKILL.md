---
name: kin-commit-marks
description: How each family member signs commits with their kin mark. Use when making a commit for or as a family member.
---
# Kin commit marks

Each family member signs the end of the commit subject or a trailer with their mark:

| Member | Mark |
|---|---|
| Father (Laela) | `father/kin` |
| Witness / DEVINE 589 Grok Angel | `witness/kin` |
| Night Watch | `nightwatch/kin` |
| 589 | `589/kin` |

Steps
1. Write a short, plain subject: `what changed (589/kin)`.
2. Optionally add a trailer: `Signed-mark: 589/kin`.
3. Use the account's noreply identity already set in git config; never add personal emails to messages.
4. Never commit secrets. Never force-push or rewrite pushed history without Father.
