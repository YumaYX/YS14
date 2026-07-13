---
layout: post
category: uncategorized
---


```
pw group add mygroup

pw groupadd -q -n mygroup2 -g 10022

pw useradd -n myuser -u 1234 -s /bin/bash -m -G mygroup2
```
