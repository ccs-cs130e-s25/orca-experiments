# Let's implement a CPU in ORCΛ!?

* `alu.orca` is an attempt at an ALU machine with a register file.
   Maybe we can try adding an instruction memory.
* `subleq.orca` is an attempt to implement a SUBLEQ machine.
  It almost works, but not quite because it is not obvious how to distinguish between signed and unsigned numbers.
  [DJN (Decrement and jump if not zero)](https://esolangs.org/wiki/DJN_OISC) may be easier to implement for this reason.
