# Description

[ver.132]

Delete files in any folder older than some period of time. Flow could be started by another flow and pass payload with directory and retention in days. Or just started normally from start button.

Uses file as source of data. Default is /Documents/automate_flow_data/retention_folders.json. If it is not found, then asks to pick one.

## ATTENTION!!!
Deletes files and folders. If folder is older than retention day, then it is going to be deleted even if contents of folder is not suitable for deletion. So use wisely.

# Dependencies

1. Needs file with data in json format.

[
  {
    "dir": "Documents/obsidian_backups",
    "retention_days": 5,
    "recursive": 0
  },
  {
    "dir": "Backup-Sync/automate/full",
    "retention_days": 7,
    "recursive": 0
  },
  {
    "dir": "Backup-Sync/automate/flows",
    "retention_days": 7,
    "recursive": 0
  }
]

2. File picker automate [flow](../File%20picker)