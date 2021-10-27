---
title: python调用shell的常用方法
date: 2021-10-27 08:22:12
tags:
---

### 方法一： os.system
```python
import os
val = os.system('ls -al')
print val
```

### 方法二： os.popen()
```python
import os
os.popen('ls -al')
```

### 方法三： commands模块
```python
import commands
commands.getstatusouput(cmd)
commands.getoutput(cmd)
commands.getstatus(cmd)
```

### 方法四：subprocess
```python
import subprocess
subprocess.run()
subprocess.call()
subprocess.check_call()
```

more info [shell调用](https://www.jb51.net/article/186301.htm)



