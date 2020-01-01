# Objectives

#### Found on your badge (click on your avatar)

---

* [x] 0. Talk to Santa in the Quad

> Enter the campus quad and talk to Santa.


1. Solution: Go north out of the building after talking to Santa

---

* [ ] 1. Find the Turtle Doves

> Find the missing turtle doves.


1. Hints: walk around and talk to elves. Possible challenges?

2. Found elf: Tangle Coalbox (East of Santa, Dormitory building)
  - Needs help accessing keypad

  - `Frosty Keypad Hints: One digit is repeated once, it's prime, and you can see which keys were used`

  - Looks like `1` `3` and `7` are used more

  - Common numbers in "leet speak" (e.g. `1337`)

  - Probably 4 digits

  - Tried: `1234` `1337` `3137` `3371` `7331`

  - See https://calculla.com/prime_number

  - Solution: `7331` `LEET/1337` backwards?

  - Achievement: `You have completed the Frosty Keypad challenge!`


3. Entered KringleCon (North of Santa, Student Union)
  - Found [Smart Braces (terminal-002)](terminal-002-iptables.md/)
  - Found elf: Shiny Upatree (NE corner of Student Union)
    - Only says, "Hey there."
    - Others in chat mentioned talking to other elves first


4. Entered Hermey Hall
  - Found elf: SugarPlum Mary
    - Needs help with Linux terminal
    - `How to find file with specific name?`
      - `find`, `locate`
    - `What happens when an executable with the same name appears multiple times in my $PATH`
      - The closest executable is run first
  - Provides new hint, `Linux Path: Green words matter, files must be found, and the terminal's $PATH matters.`
  - Found [Linux Path (terminal-003)](terminal-003-linux-path.md/)




---

* [ ] 2. Unredact Threatening Document

> [Difficulty: 1/5] Someone sent a threatening letter to Elf University.
What is the first word in ALL CAPS in the subject line of the letter?
Please find the letter in the Quad.

[#2 Letter to Elf U Personnel pdf](https://downloads.elfu.org/LetterToElfUPersonnel.pdf)


---


* [ ] 3. Windows Log Analysis: Evaluate Attack Outcome

> [Difficulty: 1/5] We're seeing attacks against the Elf U domain!
Using the event log data, identify the user account that the attacker compromised using a password spray attack.
Bushy Evergreen is hanging out in the train station and may be able to help you out.


---


* [ ] 4. Windows Log Analysis: Determine Attacker Technique

> [Difficulty: 2/5] Using these normalized Sysmon logs, identify the tool the attacker used to retrieve domain password hashes from the lsass.exe process. For hints on achieving this objective, please visit Hermey Hall and talk with SugarPlum Mary.

[#4 sysmon data](https://downloads.elfu.org/sysmon-data.json.zip)


---

* [ ] 5. Network Log Analysis: Determine Compromised System

> [Difficulty: 2/5]
The attacks don't stop! Can you help identify the IP address of the malware-infected system using these Zeek logs? For hints on achieving this objective, please visit the Laboratory and talk with Sparkle Redberry.

[#5 Elf U Zeek logs](https://downloads.elfu.org/elfu-zeeklogs.zip)
