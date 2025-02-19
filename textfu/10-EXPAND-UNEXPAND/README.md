## expand and unexpand

The expand command is used to change TABS to spaces:

```bash
expand sample.txt
```

The result can be directed to a file:

```bash
expand sample.txt > result.txt
```

One can also go back to TAB:

```bash
unexpand -a result.txt
```
And one can confirm using:

```bash
unexpand -a result.txt > result2.txt
```

then:

```bash
cat -A result2.txt
```
A tab is shown using `^I`
