# Description

[ver.237]

Saves all flows to selected directory with separate filenames for each flow. Appends the flow ID, current date and flow version to the filename.

Additionally creates separate file with description.

Also exports PNG file for every flow. Thank to author of [this](https://llamalab.com/automate/community/flows/11023)

[Example flow file](./Backup Automate Flows separately.flo)
[Example description file](./Backup Automate Flows separately.md)
[Example flow png](./Backup Automate Flows separately.png)


Uses file as source of data. Default is /Documents/automate_flow_data/automate_backup.json. If it is not found, then asks to pick one.


# Dependencies

1. Needs file with data in json format.

{
  "dir": "Backup-Sync/automate/flows"
}

2. File picker automate [flow](../File%20picker)