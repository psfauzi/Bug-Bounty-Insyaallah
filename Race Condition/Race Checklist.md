### All Things Race Condition

###### Race Condition Leads To Make Bad review
---
1. Visit **redacted.com/v1/review/vote**
2. Intercept request >> Send to Turbo Intruder.
3. Append : **x-requeted: %s** on header
4. Use script **<a href="https://github.com/PortSwigger/turbo-intruder/blob/master/resources/examples/race.py">Klik</a>**
5. Done. you can get 2 200K Repsonse.

