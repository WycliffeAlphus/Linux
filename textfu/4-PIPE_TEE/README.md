# pipe and tee


The pipe operator | , is used to take the stdout of a command and use it as the stdin of another process. 

The tee command can help show the output of a command in different streams:


```bash
ls | tee pp.txt
```

The output of ls will be shown on both the screen and pp.txt

