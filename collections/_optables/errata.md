---
layout: optable
theme: default

---

Changes from the [PASTRAISER](http://www.pastraiser.com/cpu/gameboy/gameboy_opcodes.html) version
=================================================================================================

Errors in the provided tables
-----------------------------
* The old way of referring to opcode `$E9` as `JP (HL)` is confusing and has been changed to `JP HL`.
* `STOP` is a single byte in size, older documents encode it as `$10 $00`. This was probably done because of the halt bug.
  - See [TCAGBD](https://github.com/AntonioND/giibiiadvance/blob/master/docs/TCAGBD.pdf), section 4.10. “The HALT Instruction Behaviour”.
* `$E2` and `$F2` are a single byte in size, not two.

Misc
----
* Fixed some typos
* Updated the given descriptions
* Replaced mentions of LR35902 with SM83. The former was printed on early revisions of the DMG-CPU but current evidence leads
to the conclusion that the Game Boy’s CPU was based on a Sharp SM83 CPU core.

New features
------------
* Different color schemes
* Octal view of the tables
* Responsive design, enjoy reading large tables on your tiny mobile phone!
