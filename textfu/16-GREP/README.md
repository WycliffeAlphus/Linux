# grep

The grep commands helps one to know if a certain test is in a file or a file is in a directory

```bash
grep fox filename.txt
```

It highlights the matched searched words.

Patterns that are case insensitive can also be used using the -i flag command:

```bash
grep -i somepattern somefile
```

It can also be combined with other commands:

```bash
env | grep -i User
```

One can also use a regular expression in the pattern:

```bash
ls foldername | grep '.txt$'
```