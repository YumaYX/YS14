---
layout: post
category: User
---

# Making a Group

```sh
pw groupadd -q -n mygroup -g 12345
```

# Making a User

```sh
pw useradd -n myuser -u 12345 -s /bin/bash -m -G mygroup
```
