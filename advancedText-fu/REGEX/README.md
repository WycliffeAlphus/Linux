## regex

It helps in doing pattern based selection.

The test string is:

```
ally sells seashells
by the seashore
```

1. Beginning of a line with ^

```
^by
would match the line "by the seashore"
```

```bash
grep "^by" reg.txt
```

2. End of a line with $

```
seashore$
would match : "by the seashore"
```
3. Matching any single character with "."

```
b.
would match "by"
```
4. Bracket notation with []

Allow one to specify characters found within the bracket

```
d[iou]g

would match: dig, dog, dug
```

When anchor tag ^ is used it means anything else except wht is in the bracket:

```
d[^i]g
would match: dog and dug but not dig
```
Brackets can also use ranges:

```
d[a-c]g

will match patterns like dag, dbg, and dcg
```

Note brackets are case sensitive:

```
d[A-C]g

will match dAg, dBg and dCg
but not dag, dbg and dcg
```