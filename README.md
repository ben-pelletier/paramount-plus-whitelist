# paramount-plus-whitelist
A DNS Whitelist that fixes paramount plus when many common blacklist break it.

## Comments
This White list fixes paramount plus when your gravity sources for blacklist break the streaming service. 

Make sure to add as regex when applicable. Assume fqdns with no regex indicate full domain allowance.

Their is probably duplicates and maybe false flags that aren't realivent at all to streaming, but this is all that were assigned to my apple tv group, i wouldn't have added them if it werent to fix something that was broken. As it is, it's been working with no problembs for well over a year now. It's possible some of the shows with 'extras' like interviews and stuff they might not load still. 

This  does cause the service to show loading animation ~10-15 seconds as this seems to be it's timeout period for attempting to load ad services.

This also may fix some other streaming service issues, I think hulu was one of them

## Suggestions
As to not enable these addservers network wide, you may want create a group of devices on the dns or a vlan which contains yout devices you watch paramount, either by device host name, static ip or mac. 


