# Description

[ver.391]

Check if incoming phone is considered spam. Skip phones from contacts.

Uses broadcast event for network checking in separate flow. If no network is detected then skips query.

Query callfilter.app and spravportal.ru. After query creates notifications with results.


# Dependencies

1. Net Check automate [flow](/Net%20Check%20[24][2025-02-22][ver.16].md).