# Terminal 001 - Escape Ed

## First room, next to Christmas tree 🎄

#### Objectives
* [x] Exit `ed`

#### Steps
1. [`tldr ed`](https://tldr.sh/)
2. Type `q` to quit & press `enter`

#### Achievements
`You have completed the Escape Ed challenge!`

```
                  ........................................
               .;oooooooooooool;,,,,,,,,:loooooooooooooll:
             .:oooooooooooooc;,,,,,,,,:ooooooooooooollooo:
           .';;;;;;;;;;;;;;,''''''''';;;;;;;;;;;;;,;ooooo:
         .''''''''''''''''''''''''''''''''''''''''';ooooo:
       ;oooooooooooool;''''''',:loooooooooooolc;',,;ooooo:
    .:oooooooooooooc;',,,,,,,:ooooooooooooolccoc,,,;ooooo:
  .cooooooooooooo:,''''''',:ooooooooooooolcloooc,,,;ooooo,
  coooooooooooooo,,,,,,,,,;ooooooooooooooloooooc,,,;ooo,
  coooooooooooooo,,,,,,,,,;ooooooooooooooloooooc,,,;l'
  coooooooooooooo,,,,,,,,,;ooooooooooooooloooooc,,..
  coooooooooooooo,,,,,,,,,;ooooooooooooooloooooc.
  coooooooooooooo,,,,,,,,,;ooooooooooooooloooo:.
  coooooooooooooo,,,,,,,,,;ooooooooooooooloo;
  :llllllllllllll,'''''''';llllllllllllllc,



Oh, many UNIX tools grow old, but this one's showing gray.
That Pepper LOLs and rolls her eyes, sends mocking looks my way.
I need to exit, run - get out! - and celebrate the yule.
Your challenge is to help this elf escape this blasted tool.

-Bushy Evergreen

Exit ed.

1100
```

3. After exiting `ed`, you are dropped back into a shell
4. `ls -al`
5. `more` all the things
- what else can we do here?
6. `env` shows what's in our environment, including our `$PATH`
7. `head /usr/local/bin/successfulescape` shows that `successfulescape` is a binary file :/
8. We don't have access to the `file` command to see any details on `successfulescape`, but noted that it is run at the end of the `.bashrc`, after `ed` process ends
```
ed .message
/usr/local/bin/successfulescape
```
