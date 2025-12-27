# Description

[ver.151]

Enables battery saver mode in period of picked start time and end time.

Also has a separate fiber to turn on battery saver mode anytime on mobile data. When WiFi is connected then battery saver is disabled. This fiber checks time limits from another fiber if any, and doesn't do anything within time limits. 

For some weird reason data network default block with when changed proceed requests location every 10 seconds when WiFi is on and connected. When no WiFi connected then it doesn't request location. 

# Dependencies

None