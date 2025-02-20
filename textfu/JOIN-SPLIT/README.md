## join and split

The join command allows one to join multiple files together using a common field:

```bash
join file1.txt file2.txt
```
By default that joins the files by theie first fields and the fileds have to be identical and sorted for `join` to work.

One can also specify the fields to use in a join:

```bash
join -1 2 -2 1 file1.txt file2.txt
```
-1 refers to file1.txt and -2 is file2.txt

The split command can also be used to split a file:

```bash
split filename
```

It will split the file into different lines, 1000 line limit by default abd the files are named X**.