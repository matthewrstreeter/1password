# 1password
1Password related scripts

## Included scripts

- `vault-user-group-access-report-updated.py` — generate a 1Password vault access report with per-vault CSV exports, consolidated reporting, backup retention, and filtered export support.

## Notes

- The script uses the `op` CLI to list vaults, vault users, vault groups, and group memberships.
- It writes per-vault CSV files and can combine them into a single report.
- Backup directories, log retention, and filtered exports are supported via script configuration and command-line options.
