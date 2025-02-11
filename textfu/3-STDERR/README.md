The file descriptors for stdin, stdout and stderr is 0, 1, and 2 respectively.


Therefore to redirect stderr to a file use:

```bash
ls /fake/directory 2> pt.txt
```
Therefore the stderr will be in the pt.txt file.

To see both stderr and stdout in the pt.txt file use:

```bash
ls /fake/directory > pt.txt 2>&1
```

A shorter version of redirecting both the stdout and stderr is:

```bash
ls /fake/directory &> pt.txt
```
In order to discard the stderr, it can be directed to /dev/null/

```bash
ls /fake/directory 2> /dev/null
```