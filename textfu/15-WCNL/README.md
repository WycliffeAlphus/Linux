## wc and nl

`wc` command shows the total count pf words in a file:

```bash
wc README.md
```

by default is shows the number of lines, then number of words and number of words:

`6 19 96 README.md`

To just see the details of one field use:

`-l` for lines

`-w` for words

`-c` for bytes

```bash
wc -w README
```

The `nl` command can also be used to check the count of lines on a given file.

It lists the lines that have printable characters, as it gives them numbers. The empty new lines are not counted.

eg:

```
file1.txt

I

like

turtles
```
```bash
nl file.txt
1. I
2. like
3. turtles
```
