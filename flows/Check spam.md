# Description

[ver.399]

Check if incoming phone is considered spam. Skip phones from contacts.

Uses broadcast event for network checking in separate flow. If no network is detected then skips query.

Query callfilter.app and spravportal.ru. After query creates notifications with results. 
 
Also queries фильтр-звонков.рф and makes decision to reject call or allow. 

# Limitations

- Call screening response should be in the same fiber (thread) as a call screening request. 

# Dependencies

1. Net Check automate [flow](Net%20Check.md).