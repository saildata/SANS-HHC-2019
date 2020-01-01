# Terminal 005 - Holiday Hack Trail

## Inside Dormitory, down hall

#### Objectives
* [ ] Travel to North Pole by 12/25

#### Steps
1. Click on HHT terminal
2. Click on `Easy`
3. `hhc://trail.hhc/store/?difficulty=0&distance=0&money=5000&pace=0&curmonth=7&curday=1&reindeer=2&runners=2&ammo=100&meds=20&food=400&name0=Dop&health0=100&cond0=0&causeofdeath0=&deathday0=0&deathmonth0=0&name1=Mildred&health1=100&cond1=0&causeofdeath1=&deathday1=0&deathmonth1=0&name2=Mildred&health2=100&cond2=0&causeofdeath2=&deathday2=0&deathmonth2=0&name3=Ryan&health3=100&cond3=0&causeofdeath3=&deathday3=0&deathmonth3=0`
4. URL is probably important:
  - `?difficulty=0`
  `&distance=0`
  `&money=5000`
  `&pace=0`
  `&curmonth=7`
  `&curday=1`
  `&reindeer=2`
  `&runners=2`
  `&ammo=100`
  `&meds=20`
  `&food=400`
  `&name0=Ryan`
  `&health0=100`
  `&cond0=0`
  `&causeofdeath0=`
  `&deathday0=0`
  `&deathmonth0=0`
  `&name1=Ron`
  `&health1=100`
  `&cond1=0`
  `&causeofdeath1=`
  `&deathday1=0`
  `&deathmonth1=0`
  `&name2=Chris`
  `&health2=100`
  `&cond2=0`
  `&causeofdeath2=`
  `&deathday2=0`
  `&deathmonth2=0`
  `&name3=Joseph`
  `&health3=100`
  `&cond3=0`
  `&causeofdeath3=`
  `&deathday3=0`
  `&deathmonth3=0`
5. Tried: $500k, game reset `:(`
6. Works: $65,500 `:)!`

```The more reindeer you have, the faster you can get to the North Pole. Spare runners can be handy as your sleigh can't move if you don't have two working ones. You'll need food every day and meds whenever someone is getting weak. Ammo can be handy when you run low on food.```

7. `hhc://trail.hhc/trail/?difficulty=0
&distance=885
&money=33049
&pace=0
&curmonth=7
&curday=24
&reindeer=7
&runners=6
&ammo=1099
&meds=40
&food=1985
&name0=Jane
&health0=100
&cond0=0
&causeofdeath0=
&deathday0=0
&deathmonth0=0
&name1=Mathias
&health1=100
&cond1=0
&causeofdeath1=
&deathday1=0
&deathmonth1=0
&name2=Savvy
&health2=100
&cond2=0
&causeofdeath2=
&deathday2=0
&deathmonth2=0
&name3=Sally
&health3=100
&cond3=0
&causeofdeath3=
&deathday3=0
&deathmonth3=0`

8. Works: Moving days back, e.g. 26 -> 21

```
Your party has succeeded!

    Jane is ready to jingle bell rock!
    Mathias is wicked psyched!
    Savvy is ready to jingle bell rock!
    Sally is ecstatic!
    Date completed: 8 December
    Reindeer remaining: 8
    Money remaining: 32939

Scoring:

    4 surviving party members X 1000 = 4000 points
    8 reindeer X 400 = 3200 points
    32939 money left X 1 = 32939 points
    Journey completed on 8 December: 17 days before Christmas X 50 = 850 points
    Total score: (4000 + 3200 + 32939 + 850) X 1 Easy multiplier = 40989!
    Verification hash: 2ba87ff8e5c615f51f676c23557f48c9
```

9. Probably need to do challenge on Hard, which takes away URL encoded string. Burp suite needed?
