# my-first-bison-flex

GNU bisonとflexを使った簡単な計算機

```
$ flex calc.l
$ bison calc.y
$ gcc -o calc -lfl calc.tab.c
$ echo "1+1" | ./calc
2
$ echo "2*(3+4)" | ./calc
14
```
