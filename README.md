# scc
scc means: sigma [to] c compiler because I wanted a brainrot name

This is based on Austin Z. Henley's teenytinycompiler. I added:
 - pointer things
 - brainrot keywords

Example code:
```
YAP "How many fibonacci numbers do you want?"
HEAROUT nums
YAP ""

COOK a = 0
COOK b = 1
EDGE nums > 0 REPEAT
    YAP a
    COOK c = a + b
    COOK a = b
    COOK b = c
    COOK nums = nums - 1
ENDEDGE
```
