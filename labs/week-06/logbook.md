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

**Name:** jd walton
**Week:** 6
**Work Order No.:**
6
## Milestone 1
**What I did:**
 make -C check m1
**Output or seal:**
``` ~~~ WAX SEAL of the Guild: 883642FC ~~~
```
**What it means:**
i added to some of the code that prevent some  show for unprotected member lead in c program
## Milestone 2
**What I did:**
make -C check m2
**Output or seal:**
``` ~~~ WAX SEAL of the Guild: 2DA46117 ~~~
```
**What it means:**
remove code from the sorted floor 
## Milestone 3
**What I did:**
make -C check m3

**Output or seal:**
```  ~~~ WAX SEAL of the Guild: 85DAAF22 ~~~

```
**What it means:**
repair a program
4

make -C check m4
  ~~~ WAX SEAL of the Guild: F4BE746C ~~~
lang table and we see how and who  to fork it

5

 make -C check m5

  ~~~ WAX SEAL of the Guild: 2A5CA4EF ~~~
we found the uid and the light house 
We secured the ledger hall simulation by implementing a writer-preferring reader-writer lock to guarantee accurate data reads without starving the updating thread.
impleneteinf a semaphone and muteax to a sorting floor and appleied reader
> Fewer or more milestones this week? Copy a block above as needed.

## Reflection

1. **(Prompt 1 from the work order):**While a condition variable uniquely allows threads to sleep until a specific state changes, using it instead of a simple mutex for a basic critical section creates a correct but uselessly slow program due to the overhead of constant signaling. Semaphores uniquely track resource counts, making them perfect for managing a bounded buffer, but using a simple semaphore instead of a reader/writer lock for a read-heavy document would correctly prevent crashes while uselessly bottlenecking all readers into a single-file line. Finally, a reader/writer lock uniquely allows simultaneous reads while isolating writes, but using a naive version in a constantly updated system can cause writer starvation, rendering the program useless as the writer waits forever in an endless line of readers.

The fact that perfectly reasonable rules can still cause a sudden stall shows that standard testing is completely inadequate for concurrent programs, as deadlocks are caused by incredibly rare timing alignments rather than obvious logic errors. Knowing a program ran successfully a few times is meaningless because those rare collisions might only trigger once a month. Before assuring the Guild that a concurrent machine is safe, my standard requires subjecting the code to extreme stress tests and timing-manipulation tools (like ThreadSanitizer) to intentionally force these timing edge-cases and prove it survives the absolute worst-case scenario.

## Sources and help

Anyone or anything that helped you this week — a classmate, a man page,
a Stack Overflow answer, an AI assistant. One line each: who or what,
and what you used it for. This is **not graded and never costs points**;
it is the habit professional engineers keep, and the syllabus asks for
it under *Academic integrity* and *Use of AI tools*.
matthew mahn
- *(example)* Worked through the `fork` ordering with Sam in studio.
- *(example)* Used an AI assistant to explain what `EAGAIN` means in the trace.

*Nothing to report? Write "None" — that's a perfectly normal week.*

## Time spent

Roughly how long this took, start to finish: 4 hours
*No wrong answer — this just helps calibrate future work orders.*
