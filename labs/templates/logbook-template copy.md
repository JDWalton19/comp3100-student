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
**Week:** 12
**Work Order No.:**
11
## Milestone 1
**What I did:**
make -C check m1
**Output or seal:**
```~~~ WAX SEAL of the Guild: 5B79A45C ~~~
```
**What it means:**
Covers file descriptors (0, 1, 2), output and error redirection (>, >>, <, 2>, 2>&1, &>), and character device files in /dev along with their major and minor numbers.
## Milestone 2
**What I did:**
make -C check m2
**Output or seal:**
``` ~~~ WAX SEAL of the Guild: F8D8DAE5 ~~~
```
**What it means:**
creating and using FIFOs (named pipes) with mkfifo, observing how pipes buffer data, how multiple readers split a stream, and handling broken pipes (SIGPIPE).
## Milestone 3
**What I did:**
make -C check m3
**Output or seal:**
``` ~~~ WAX SEAL of the Guild: 7AFD0197 ~~~
```
**What it means:**
Covers inspecting an active pneumatic line, tracing standard output and file descriptors across living processes, and examining file permissions and process boundaries.
## Milestone 4
**What I did:**

**Output or seal:**
```
```
**What it means:**
Covers using fuser, lsof, ps, and /proc/<pid>/cmdline to identify processes holding open files or tubes across different user accounts.
> Fewer or more milestones this week? Copy a block above as needed.

## Reflection

1. **(Prompt 1 from the work order):**
2. **(Prompt 2 from the work order):**

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
