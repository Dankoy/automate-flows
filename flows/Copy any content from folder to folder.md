# Description

[ver.53]

Copy files and directories from source directory to destination directory. File extension filters could be applied. 

Flow could be started by another flow and pass payload. Or just started normally from start button.

Uses file as source of data. Default is /Documents/automate_flow_data/copy_folders.json. If it is not found, then asks to pick one.

## ATTENTION!!!

Doesn't work with directories recursively. Only work with files and directories that exactly in source directory.

# Dependencies

1. Needs file with data in json format.

[
  {
    "dir": "Courses",
    "destination": "Backup-Sync/Syncthing/Mi9/Courses",
    "recursive": 0,
    "filters": {
      "extension": [
        ".stfolder", ".stignore"
      ]
    }
  },
  {
    "dir": "backups",
    "destination": "Backup-Sync/Syncthing/Mi9/backups",
    "recursive": 0,
    "filters": {
    }
  },
]

2. File picker automate [flow](File%20picker.md)