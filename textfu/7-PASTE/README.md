## paste

It is similar to cat, it merges different lines together in a file:

```bash
cat sample2.txt
The
quick
brown
fox
```

The default delimiter for space is `TAB`

```BASH
paste -s sample2.txt
The     quick   brown   fox
```


- Without `-s`, paste merges lines column-wise from multiple files.

- With `-`s`, paste merges lines row-wise (serially).

One can use another delimiter say , space:

```BASH
paste -d ' ' -s sample2.txt
The quick brown fox
```
