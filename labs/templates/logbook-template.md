# Engineer's Logbook

*Honourable Guild of Enginewrights — Ex Vapore, Ordo*

Copy this into your week's folder as `logbook.md` and fill it in as you
work. Paste your wax seals where marked — that's how a milestone gets
marked done.

Write it the way you'd explain the week to a classmate who missed it:
plain sentences, no polish. An honest half-answer under "what it
means" — *I got the seal but I'm still fuzzy on why the second run
differed* — beats a confident sentence you don't believe, and it tells
me where to start when you bring it to studio.

**Name:**JD Walton
**Week:** 13
**Work Order No.:**
12
## Milestone 1
**What I did:**
 make -C check m1
**Output or seal:**
```~~~ WAX SEAL of the Guild: F3647AD8 ~~~
```
**What it means:**
we checking the user id and change who allow to read write and run the file
## Milestone 2
**What I did:**
make -C check m2
**Output or seal:**
``` ~~~ WAX SEAL of the Guild: B3F1D4C2 ~~~
```
**What it means:**
we tested thr special pereisin and proved that linux block it from working on shell script for security 
## Milestone 3
**What I did:**
make -C check m3
**Output or seal:**
```~~~ WAX SEAL of the Guild: 4411D53D ~~~
```
**What it means:**
we are serch ing thr computer for file that useed in command setuid and it was summarize what we found 
## Milestone 4
**What I did:**
make -C check m4
**Output or seal:**
``` ~~~ WAX SEAL of the Guild: 318D62BA ~~~
```
**What it means:**
we are comparing rh log in the termianf agaist the so what physical paper log to see if the key swiped matched the actual time peole signed into the building 


> Fewer or more milestones this week? Copy a block above as needed.

## Reflection

1. **(Prompt 1 from the work order):**
Explanation of passwd and the setuid bit:
Every user on a computer has an ID number called a uid, and every file has a permission rule called a mode that says who can use it. The passwd program is special because its mode has a "borrowed power" mark called the setuid bit. When you run it, this mark temporarily changes your active ID (your effective uid) to match the system administrator, letting you safely update your password in a locked file you can't normally see. However, the computer completely ignores this mark on simple text scripts because it's too easy for hackers to mess with scripts and steal those administrator powers.
2. **(Prompt 2 from the work order):**
To make the log record the actual person and not just the key, I would add a PIN code keypad or a fingerprint scanner to the door. By doing this, I would be giving up speed and convenience, because unlocking the door would take much longer and be more annoying for people every day
## Sources and help

Anyone or anything that helped you this week — a classmate, a man page,
a Stack Overflow answer, an AI assistant. One line each: who or what,
and what you used it for. This is **not graded and never costs points**;
it is the habit professional engineers keep, and the syllabus asks for
it under *Academic integrity* and *Use of AI tools*.

- *(example)* Worked through the `fork` ordering with Sam in studio.
- *(example)* Used an AI assistant to explain what `EAGAIN` means in the trace.

*Nothing to report? Write "None" — that's a perfectly normal week.*

## Time spent

Roughly how long this took, start to finish: _______ hours
*No wrong answer — this just helps calibrate future work orders.*
