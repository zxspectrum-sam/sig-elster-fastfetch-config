# signalis themed fastfetch config...
<img width="1193" height="635" alt="Screenshot_20260102_205025" src="https://github.com/user-attachments/assets/91862af7-1b94-4f09-bfd7-c0af71bd77a7" />

it uses the example config 25, i just did the ascii art and the coloring

<img width="1215" height="633" alt="изображение" src="https://github.com/user-attachments/assets/b792e4f3-0656-408e-8f5a-ccb133e93ee6" />

it also works on windows...

# TUTORIAL (LINUX)

- download the config file with the ascii art, rename the config to ***whatever u want***.jsonc (or dont), move it to ``~/.config/fastfetch`` then in the conf file, locate the 

```sh
"source": "placeholder/ascii-art.txt",
```
- and replace the placeholder with the directory where u downloaded the ascii art

### exampl:
```sh
"source": "/home/urgovname/Downloads/ascii-art.txt",
```

- and execute it with 
```sh
$fastfetch --config ~/.config/fastfetch/whatever u want.jsonc
```
# TUTORIAL (WINDOWS)

- first, download the needed files (ascii-art.txt and config.jsonc)
- get fastfetch via the winget command 
``` sh
winget install fastfetch
```
- open the terminal and generate the config file
``` sh 
fastfetch --gen-config
```
- locate the generated config file. 
### example:
``` sh
C:\ProgramData\fastfetch\config.jsonc
```
- replace the conf file with the new one
- then open the downloaded conf in notepad and replace the placeholder path in ```"source" :``` with the path where you installed the ascii art
## should look something like this: 
<img width="451" height="25" alt="изображение" src="https://github.com/user-attachments/assets/31bb96dd-1383-4cc2-9a55-1499fe034880" />

### and youre basically done!! congrats.
