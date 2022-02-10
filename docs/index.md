---
layout: home
title: HOME
---


```console?error=ERROR:
ERROR: Unexepected shutdown, try to reboot...
# '[ KERNEL ]': Loading ...
  reading sect(0,0) to sect(0,6)
# '[ KERNEL ]': Loaded
# '[ KERNEL ]': Loading 'OS' ...
ERROR: Multiple corrupted sectors
# '[ KERNEL ]': Recover corrupted sector...
ERROR: Sector recovery falied
# '[ KERNEL ]': Recover '0' out of '?' corrupted sector on track '1'
# '[ KERNEL ]': Switching to 'recovery' mode
{% for post in site.posts %}
# '[ KERNEL ]': Recover file '{{ post.title }}' ...{% endfor %}
{% for page in site.pages %}{% unless page.title == None %}
# '[ KERNEL ]': Recover file '{{ page.title }}' ...{% endunless %}{% endfor %}

# '[ KERNEL ]': Run 'RECOVERY_SHELL' ...

+----------------+
| RECOVERY SHELL |
+----------------+

------------------
PRINTING LINK IN TOP OF TERMINAL

------------------
DISPLAYING RECOVERED FILES:
```
