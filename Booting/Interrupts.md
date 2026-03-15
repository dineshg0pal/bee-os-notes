# Interrupts

- Interrupts - CPU stops & listens

- It happens in both **Hardware & Software

- when interrupts happens, CPU pauses, runs handlers & resumes

## Components

### IDT

- It stands for (**Interrupts Descriptor Table**)
- it tells the CPU, where the interrupts happened, it is a table in memory

### ISR

- It stands for (**interrupt Service Routine**)
- It is a function/code, which handles the interrupts

### PIC/APIC

- It stands for (**PIC - Programable Interrupt Controller**)
- It stands for (**APIC - Advanced Programable Interrupt Controller**)
- pic is a old controller, where apic is a modern controller
- It is a hardware for managing interrupts from devices
