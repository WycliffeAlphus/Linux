# cut

It helps in extracting portions of text from a file.

For example when extracting the 5th character use:

```bash
cut -c 5 filename.txt
```

Contents can also be extracted by a field, and by default it uses TABs as delimiters

```bash
cut -f 2 filename.txt
```

One can also combine the field flag with the delimiter flag to extract the contents by a custom delimiter:

```bash
cut -f 1 -d ";" filename.txt
```
That means we are cutting the first field separated by ";" and any tab is changed to ";"