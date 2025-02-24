## uniq

The uniq keyword is used to parse text
It returns only the unique ones if there are duplicates

```bash
uniq reading.txt
```

count of the unique values can also be determined:

```bash
uniq -c reading.txt
```
one can also get only the one that is not repeated

```bash
uniq -u reading.txt
```
To get duplicate values use:

```bash
uniq -d reading.txt
```

`Note that the uniq command do not work if the duplicate values are not adjacent; it will reaturn back the values as they are:

to overcome that:
first sort:

```bash
sort reading.txt | uniq
```