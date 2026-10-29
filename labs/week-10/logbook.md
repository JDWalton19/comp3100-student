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

**Name:**jd walton
**Week:** 9
**Work Order No.:**
10
## Milestone 1
**What I did:** make -C check m1

**Output or seal:**
```  ~~~ WAX SEAL of the Guild: ABB554A4 ~~~
```
**What it means:**
ypou explored your own shell memory map to see the different region where they actualy the data learned the difference between reuqusteds memery and the activily used memeory 
## Milestone 2
**What I did:**
make -C check m2

**Output or seal:**
```~~~ WAX SEAL of the Guild: 457EB20E ~~~
```
**What it means:**
we used the memory governor to put a trict limit on a memory hogging program and woe the in th OOM killer ficibly terminate it 
## Milestone 3
**What I did:**
make -C check m3
**Output or seal:**
``` ~~~ WAX SEAL of the Guild: 1DD7F597 ~~~
```
**What it means:**
you invested a mystery proccess owned by aanother user to identify its owner in the UIB  which was 1849 in the specific walled off memory region that was completely hidden from our account
## Milestone 4
**What I did:**
make -C check m4
**Output or seal:**
```~~~ WAX SEAL of the Guild: 296321E9 ~~~
```
**What it means:**
we uesed the root privilaeges and a debugger to reas the walled of memory in the region from the procees owned by the other user
> Fewer or more milestones this week? Copy a block above as needed.

## Reflection

1. **(Prompt 1 from the work order):**
When storeroom initially requests 256 pages, the operating system simply grants it a range of virtual addresses without actually allocating any physical RAM, making the request nearly free. However, when the program attempts to read or write to a page for the first time, the hardware realizes the physical memory isn't actually there yet and triggers a page fault. This fault forces the operating system to pause the program, find available physical memory, update the translation table, and make that memory resident. By the time the second round occurs, the pages are already resident and fully mapped, meaning the CPU can access them directly without triggering any further page faults.
2. **(Prompt 2 from the work order):**
Yes, it was the right thing for the Engine to do, because the Overseer (the OOM killer) must intervene as a last resort to protect the operating system and other critical services from crashing when memory is exhausted. Instead of killing processes outright, a real server ideally degrades gracefully by utilizing swap space or explicitly rejecting new incoming network requests (load shedding). However, the cost of relying on swap space is a severe performance penalty (disk thrashing) that can make the server so incredibly slow it effectively becomes unresponsive anyway.

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
