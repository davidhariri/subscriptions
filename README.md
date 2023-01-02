# My RSS Subcriptions

Download [/subscriptions.xml](/subscriptions.xml) and import it into your RSS client

## Note for me:
I create the list for my blog automatically using the following Regex:

```
Find: <outline text="(.*?)"(.*?)xmlUrl="(.*?)" htmlUrl="(.*?)"\/>

Replace: - [$1]($4) • *[Feed]($3)*
```
