### stdout

When the `echo` command is used it takes the input from the standard out and displays it on the 
standard out.However, one can redirect the output to be saved in a file

```bash
echo Hello World > hello.txt
```

If the file do not exist it is created and "Hello World" is saved into it. 

To append the text use:

```bash
echo Hello World >> hello.txt
```
Also, if the file do not exist it will be created automatically.