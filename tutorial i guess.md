so u jus downld the config file with the ascii art, rename the config to ***whatever u want***.jsonc, move it to ``~/.config/fastfetch`` then in the conf file, locate the 

```sh
"source": "placeholder/ascii-art.txt",
```
and replace the placeholder with the directory where u downloaded the ascii art

### exampl:
```sh
"source": "/home/urgovname/Downloads/ascii-art.txt",
```

and execute it with 
```sh
$fastfetch --config ~/.config/fastfetch/whatever u want.jsonc
```


