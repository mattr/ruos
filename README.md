# RuOS

Exploring OS design in Rust.

A "Princess Bride" reference is a must.

## QEMU

To boot in QEMU, use the following command:

```bash
qemu-system-x86_64 -drive format=raw,file=target/x86_64-ruos/debug/bootimage-ruos.bin
```