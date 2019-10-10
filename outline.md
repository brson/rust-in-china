# Build a VM in Rust

In this talk we will explain the basics of how to build a Virtual Machine, using
the Rust programming language; discuss the specifics of how we implemented
RISC-V in CKB-VM, and some of the problems encountered. Finally, we will use
CKB-VM to create a live networked video game called Ferris-Fight that runs
arbitrary Rust code in a RISC-V sandbox.

Distribute flyers on community-swag table before the talk so people can
play with the game and gossip about it.

## Outline

- Pre-roll slide
  - Title
  - Link to repo / slides / code / live server instructions
- About us
- Session overview
  - Building a VM in Rust that also runs Rust
- Part 1: Building a VM
  - Why build a VM?
    - Generally, CKB, VMs are cool
    - Use cases
  - Something about ISAs?
  - RISC-V
    - Why RISC-V?
      - open ISA, minimal, simple, elegant
      - cool
    - RISC-V reference card visual
    - RISC-V industry adopters?
  - ?
  - CKB-VM
    - stage direction: start building CKB-VM
  - VM Architecture
    - VM + Runtime + Client code (todo where does this go?)
  - Rust VM code
    - TODO
  - The limits of Rust
    - where did CKB-VM have problems with Rust
    - link to Xiao's talk
  - Performance numbers
- Part 2: Running Rust on CKB-VM
  - Demo Ferris-Fight
  - RISC-V toolchains
  - The C test case
    - Show and explain
    - Run it live
  - The Rust test case
    - Code it live
  - Runtimes
  - Tour the Ferris-Fight runtime
- Contributing to CKB-VM and Ferris-Fight
- Thanks