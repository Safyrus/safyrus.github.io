---
layout: home
title: HOME
---


```console?error=ERROR:
ERROR: Unexepected shutdown, try to reboot...
# '[ KERNEL ]': Loading ...
  reading sect_0_0
  reading sect_0_1
  reading sect_0_2
  reading sect_0_3
  reading sect_0_4
  reading sect_0_5
  reading sect_0_6
# '[ KERNEL ]': Loaded
# '[ KERNEL ]': Loading 'OS' ...
ERROR: Corrupted Sector 0 on Track 1
ERROR: Corrupted Sector 1 on Track 1
ERROR: Corrupted Sector 2 on Track 1
ERROR: Corrupted Sector 3 on Track 1
# '[ KERNEL ]': Recover corrupted sector...
ERROR: Sector recovery falied
ERROR: Sector recovery falied
ERROR: Sector recovery falied
ERROR: Sector recovery falied
# '[ KERNEL ]': Recover '0' out of '4' corrupted sector on track '1'
# '[ KERNEL ]': Switching to 'recovery' mode
{% for post in site.posts %}
# '[ KERNEL ]': Recover file '{{ post.title }}' ...
# '[ KERNEL ]': file '{{ post.title }}' recovered{% endfor %}
# '[ KERNEL ]': Run 'RECOVERY_SHELL' ...

+----------------+
| RECOVERY SHELL |
+----------------+
/ > LS
```
