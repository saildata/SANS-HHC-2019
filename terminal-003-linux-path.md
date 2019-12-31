# Terminal 003 - Linux path

## Inside Hermey Hall

#### Objectives
* [ ] Get a listing (ls) of your current directory

#### Steps

```
I need to list files in my home/
To check on project logos
But what I see with ls there,
Are quotes from desert hobos...

which piece of my command does fail?
I surely cannot find it.
Make straight my path and locate that-
I'll praise your skill and sharp wit!

Get a listing (ls) of your current directory.
```

1. Noticed green words in prompt: `file home/ ls which find path locate`
2. `env`

```
SHELL=/bin/bash
PWD=/home/elf
LOGNAME=elf
HOME=/home/elf
USER=elf
SHLVL=1
PATH=/usr/local/bin:/usr/bin:/bin:/usr/local/games:/usr/games
MAIL=/var/mail/elf
```
3. Solution:

```
elf$ ls
This isn't the ls you're looking for
elf$ which ls
/usr/local/bin/ls
elf$ /usr/local/bin/ls
This isn't the ls you're looking for
elf$ /bin/ls
' '   rejected-elfu-logos.txt
Loading, please wait......



You did it! Congratulations!
```

#### Achievements
`You have completed the Linux Path challenge!`

4. Look at `rejected-elfu-logos.txt` and other local files.. not much

5.
