---
layout: post
title: string randomizing
categories: testing
tags: [testing,python]
---

super fun random string thing
prefix has stuff put before the random string
~~~python
import random, string
from datetime import datetime

random.seed(datetime.now().timestamp())

prefix = ""
supersecretrandomized = supersecretthing + "".join(random.choices(string.ascii_letters + string.digits, k=16))
print(supersecretrandomized)
~~~

ok thaats it
