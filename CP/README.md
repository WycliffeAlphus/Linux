To copy a file use the command:

``` cp filename <path of destination>```

One can also use wildcards for example:

```*``` represent single characters or any string.

```cp *.jpg /path/```

```?``` one character

```[]``` any character

It copies all files with the .jpg extension.

To copy all the contents in a folder do a recursive copy:

```cp -r folder/  /destinationPath/```

Using the i- flag can help one from overwriting a file accidentally:

```cp -i mycoolfile /path/```

