# writeups

My notes and writeups from reverse-engineering and CTF practice.
Each writeup explains **how I approached the problem and what I learned**,
not just the answer.

## Index

<!-- Add a row for every writeup. Newest first. -->

| Date | Platform | Challenge | Category | Difficulty | Writeup |
|------|----------|-----------|----------|------------|---------|
| _—_ | _—_ | _first writeup coming soon_ | _—_ | _—_ | _—_ |

## Layout

| Folder | What goes there |
|--------|-----------------|
| [`crackmes/`](crackmes/) | Solutions to [crackmes.one](https://crackmes.one) challenges |
| [`picoctf/`](picoctf/) | [picoCTF](https://picoctf.org) / picoGym writeups |
| [`pwn-college-notes/`](pwn-college-notes/) | Concept notes from [pwn.college](https://pwn.college) — **no solutions** |

Start a new writeup by copying [`TEMPLATE.md`](TEMPLATE.md).

## Rules I follow

- **No writeups for live competitions.** I only publish after an event ends,
  or for permanent practice challenges (picoGym, crackmes.one).
- **pwn.college:** the platform asks students not to publish solutions, so that
  folder holds concept notes only: what a technique is, how it works, links.
  No flags, no challenge-specific steps.
- **Flags are redacted** as `picoCTF{REDACTED}` so the writeup teaches the
  method without handing out the answer.

## Toolbox

`gdb` + pwndbg · Ghidra · `objdump` · `strings` · `strace` / `ltrace` · `file` · Python + pwntools
