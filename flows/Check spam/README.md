# Description

[ver.726]

Check if incoming phone is considered spam. Skip phones from contacts.

Uses broadcast event for network checking in separate flow. If no network is detected then skips query.

## Features

1) Check incoming phones for spam and shows results in notifications.
2) Allow repeated calls in time period of 3 minutes, even if it was blocked first time.
3) Persistent notification to check any number for spam.
4) Allow is default option in case of unreachable network or errors in external service.
5) Phones from contacts are skipped from checking and always allowed.

## Integrations

1) callfilter.app as webview. 
2) spravportal.ru as webview.
3) фильтр-звонков.рф for decision making to allow or reject.

# Limitations

- Call screening response should be in the same fiber (thread) as a call screening request.

# Dependencies

1. Net Check automate [flow](../Net%20Check).