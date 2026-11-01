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
**Week:** 11
**Work Order No.:**
10
## Milestone 1
**What I did:**
make -C check m1
**Output or seal:**
```  ~~~ WAX SEAL of the Guild: ECCC5D52 ~~~


```
**What it means:**
we saw how linux handle files name and indoes and link and succeessfully recover a delected files that was still helfd open by an active shell proccess
## Milestone 2
**What I did:**
 make -C check m2
**Output or seal:**
```  ~~~ WAX SEAL of the Guild: 8CFE54A2 ~~~

```
**What it means:**
We mounted the cabinet disk image read-only to safely inspect its ext2 file system properties, block size, and shared inode links without altering the evidence.
## Milestone 3
**What I did:**
make -C check m3

**Output or seal:**
```  ~~~ WAX SEAL of the Guild: F7A8DA13 ~~~
```
**What it means:**
We analyzed the ledger files' modification timestamps to identify a forged entry that was written after the ledger hall's official closing time.
## Milestone 4
**What I did:**
make -C check m4

**Output or seal:**
```~~~ WAX SEAL of the Guild: 7D1C68B7 ~~~

```

**What it means:**
We used debugfs to locate deleted inodes and successfully recovered the struck correspondence to uncover the Chief Computer's warnings about the Engine's rounding errors.
> Fewer or more milestones this week? Copy a block above as needed.

## Reflection

1. **(Prompt 1 from the work order):**
When you use rm, it just deletes the file's name and lowers its link count. The file's inode and data blocks stay completely intact until the link count reaches zero and no programs are using it, which is when the space is finally freed. We could recover the memoranda because the cabinet is a frozen disk image where those freed blocks were left untouched. In contrast, your active home folder constantly writes new data and would immediately overwrite that free space.
2. **(Prompt 2 from the work order):**
If the cabinet had allowed writes, simply typing a careless command like touch note.txt could have permanently destroyed a memorandum. The file system would instantly reuse the deleted file's "freed" space to save your new file, overwriting the historical evidence forever. This proves exactly why you must always defend the habit of mounting forensic evidence as read-only.

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
