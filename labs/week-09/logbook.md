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
**Week:** 9
**Work Order No.:**
8 
## Milestone 1
**What I did:**
make -C check m1
**Output or seal:**
``` ~~~ WAX SEAL of the Guild: 8F513B1B ~~~
```
**What it means:**
this one we show what is beening store in the termainal and we put the from the lowest value first in the stare 
## Milestone 2
**What I did:**
 make -C check m2
**Output or seal:**
``` ~~~ WAX SEAL of the Guild: 1A6E8F38 ~~~
```
**What it means:**
i use the valgroud program to fix the memory leak we were having 
## Milestone 3
**What I did:**
make -C check m3

**Output or seal:**
```   ~~~ WAX SEAL of the Guild: 95E9B758 ~~~
```
**What it means:**
we anylize it and determine what leak and how much of it 
## Milestone 4
**What I did:**
make -C check m4

**Output or seal:**
```~~~ WAX SEAL of the Guild: E3B07045 ~~~

```
**What it means:**
 we use the gbd to insept the debugger 
> Fewer or more milestones this week? Copy a block above as needed.

## Reflection

1. **(Prompt 1 from the work order):**
A memory leak in a short-lived program costs almost nothing because the operating system reclaims the program's entire memory space, including its heap, the moment it terminates. However, if a program runs for months without freeing memory, those orphaned allocations continuously accumulate, eventually exhausting the system's available RAM and causing the machine to crash. In these scenarios, the root pointers that the program forgets are considered definitely lost, while any secondary allocations attached to them (like strings inside a leaked node) become indirectly lost. The cap changes this dynamic by setting a hard limit on the total number of blocks the program can draw, ensuring that even if it never returns them, the maximum memory consumed remains small and manageable for the system.
2. **(Prompt 2 from the work order):**
A program that prints the right answer is not necessarily a correct program, as hidden memory faults—like buffer overflows or use-after-free errors—can cause silent data corruption, security vulnerabilities, or unpredictable crashes under different runtime conditions. Before declaring a program correct in a code review, I would want to see a clean memory audit (such as a Valgrind report with zero errors) to prove that it manages its resources safely and handles memory predictably, rather than just getting lucky on my specific machine.

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
