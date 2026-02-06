# Description

[ver.74]

Log applications screen start and stop time. Also logs device locks and unlocks.

Default folder for logs is '/Documents/automate/screen_time_tracker'.

Based on [flow](https://llamalab.com/automate/community/flows/51931)

Changes from original:

1. Refactored blocks positioning
2. Added folder picker
3. Added variables for target directory and files in it
4. Added delta logging between start and stop
5. Added limit logging for logs exceeded limit
6. Fixed empty end time when first device lock is made after flow start
7. Fixed log with 'to be ignored'

# Dependencies

None