# Unix Dynamic Linker used to create a shared object

* LD_PRELOAD
* LD_LIBRARY

Command to run:
```bash
gcc -fPIC -shared -nostartfiles -o /tmp/preload.so preload.c
sudo LD_PRELOAD=/tmp/preload.so program-name-here
```
