To move or rename files use the ```mv``` command.

To rename use:

```bash
mv oldfile newfile
```

to move the file to another directory:

```bash
mv file2 /home/pete/Documents
```

Multiple files:

```bash
mv file_1 file_2 /directory
```

renaming directory is also possible:

```bash
mv directory1 directory2
```

Though is something will be overwritten use:

```bash
mv -i directory1 directory2
```

If one wishes to still keep or backup the previous version use:

```bash 
mv -b directory1 directroy2
```

