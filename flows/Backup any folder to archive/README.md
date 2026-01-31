# Description

[ver.57]

Backups any folder to archive with any extension.

Uses file as source of data. Default is /Documents/automate_flow_data/backup_folder.json. If it is not found, then asks to pick one.


# Dependencies

1. Needs file with data in json format.

[
   {
      "source_dir": "Documents/Obsidian",
      "target_dir": "Documents/obsidian_backups",
      "file_name": "obsidian-zip",
      "extension": ".txt"
   }
]

2. File picker automate [flow](../File%20picker)