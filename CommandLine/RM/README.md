When removing files use the command:

```bash
rm file1
```

One can also force removal of a file, even in a situation where they are write protected:

```bash
rm -f file1
```
To get prompts before removal use:

```bash
rm -i file
```
When removing a directory having files use recursive removal:

```bash
rm -r directory
```

Also this can help remove a directory if it is empty:

```bash
rmdir directory
```