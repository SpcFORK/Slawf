# Slawf
Multi-Layered UWF HVM Ontop Tacit Langauge.

# Goals
- [ ] Registers, Stacks, Tables, History-Dictionaries
- [ ] CowCstHeapMem Implementation
  - [ ] 3hb head, (13hb - head) body -> 0x000  00000 00000
  - [ ] 1hb head, (13hb - head) body -> 0x0  000000 000000
  - [ ] 2hb head, (13hb - head) body -> 0x00  00000 000000

- [ ] Hypervisor
  - [ ] VM suite
    - [ ] VMs may interface eachother using Hypervisor instance
    - [ ] VMs may make instances of VMs
    - [ ] VMs may instance sub-visors
      - [ ] Ring levels
        - [ ] Flagged access & hidden addressed memory
        - [ ] Privilage is managed top down, while allowing top levels to implement layer elevation and or emulation by acting for the lower ring
  - [ ] Threading where possible and or Fake Threading for environments unable

- [ ] Upgraded version of Oakl setups
  - [ ] Either...
    - [ ] Better Web-Interop that does not conflict?
    - [ ] Slawf Web Interop
       
- [ ] More modules
  - [ ] Oak-JS interop suite
    - [ ] Abstraction Redundance swap-in for core JS functions to shorten code
      - (Instead of std.each, asks if interopping, if so, use core functions instead of unwrapped abstractions)
  - [ ] Inklang's BMP image module
  - [ ] Better Crypto.oak
    - [ ] Base* coding suite
    - [ ] Parity check suite
    - [ ] Encryption primitives
      - [ ] For example:  XORENCY
  - [ ] Compression suite!
  - [ ] Bitwise suite!
  - [ ] CVM tech...?
  - [ ] Matrix Math tech
    - [ ] FFT & FFI
    - [ ] Wavelets
    - [ ] GrDc

- [ ] Compiler?
  - [ ] WASM Compiler?  (Refer to Odin Drunk Code session)

- [ ] Transpilers
  - [ ] To Oakl!
    - [ ] Must transpile to Oak AST
  - [ ] To F95!
  - [ ] To PHP!
  - [ ] To NIM?
  - [ ] Go?

- [ ] Broader evaluation setup
  - [ ] Standardized Binary forms
    - [ ] More than ELF?
    - [ ] ARM?
    - [ ] Oak Bytecode instead of only ELF (requires engine)?

- [ ] Bootstrap..?
  - ...If binary size does not grow larger than non-strapped version
