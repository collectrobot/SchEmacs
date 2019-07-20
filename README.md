# SchEmacs
Emacs implementation by Scheme
### build
```shell
cc -fPIC -shared -o  ./emacs.so ./emacs.c
```
### run
```shell
#!/bin/bash
export LD_LIBRARY_PATH=${LD_LIBRARY_PATH}:./
scheme  --script ./emacs.sc
```
![img](https://github.com/guenchi/Emacs/blob/master/img/0.png)

![img](https://github.com/guenchi/Emacs/blob/master/img/1.png)

![img](https://github.com/guenchi/Emacs/blob/master/img/2.png)



