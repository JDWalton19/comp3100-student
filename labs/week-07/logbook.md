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

**Name:** JD Walton
**Week:**7
**Work Order No.:**
7
## Milestone 1
**What I did:**
make -C check m1
**Output or seal:**
```  ~~~ WAX SEAL of the Guild: 8FB23102 ~~~

```
**What it means:**

## Milestone 2
**What I did:**
make -C check m2
**Output or seal:**
```   ~~~ WAX SEAL of the Guild: 7ED21DDD ~~~
```
**What it means:**

## Milestone 3
**What I did:**
make -C check m3
**Output or seal:**
```  ~~~ WAX SEAL of the Guild: FDE452E7 ~~~
```
**What it means:**

> Fewer or more milestones this week? Copy a block above as needed.

## Reflection

1. **(Prompt 1 from the work order):**A deadlock is like a traffic jam that needs four specific things to happen at once. If you remove even one of these four conditions (mutual exclusion, hold and wait, no resource preemption, or circular wait), the jam clears up because the cycle is broken.However, preventing these conditions has costs ,Breaking Mutual Exclusion: This is usually impossible. You can't have two threads sharing a physical resource like a printer (or a train lever) at the exact same time without causing a crash or data corruption.  Breaking Hold and Wait: If you force a program to grab every resource it will ever need before it even starts running, it hogs things it isn't using yet. This slows the whole system down and ruins concurrency.
2. **(Prompt 2 from the work order):**
I would choose prevention over recovery. If you rely on recovery, the system has to waste processing power constantly checking for deadlocks. Worse, if you force a program to drop a lock or quit to break the deadlock, you risk permanently corrupting your shared data. It is much safer and cleaner to design the system so it never gets stuck in the first place.
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
