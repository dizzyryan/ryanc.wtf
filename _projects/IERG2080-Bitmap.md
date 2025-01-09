---
title: "IERG2080 Project: 2D bitmap editor"
order_number: 1
---

[IERG2080 Project: 2D bitmap editor](https://github.com/dizzyryan/CUHK-CS-Notes/blob/bf9a807f64c491d62685a233bd8f789d982280ca/IERG2080/proj.c)
You can compile the code by
```
gcc proj.c -o proj -lcurses
```

Or by creating a Makefile
```
make:
	gcc proj.c -o proj -lcurses
```

Then, you can use the program by

```
./proj [in=in_file] [out=out_file]
./proj [out=out_file] [in=in_file]
```

Both arguments are optional. Yet, the phase in= or out= must be provided if the corresponding argument is used. in_file is the input file name, and out_
file is the output file name.