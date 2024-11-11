## How to run :

```bash
flex wh.l
bison wh.y
gcc wh.tab.c -lfl
./a.out
```

Try entering while(a>1){ b=1;}