# yv6

My solutions for [OSTEP](https://pages.cs.wisc.edu/~remzi/OSTEP/) xv6 labs, based on MIT's [xv6-riscv](https://github.com/mit-pdos/xv6-riscv).

## OSTEP Projects

| Project | Status |
|---------|--------|
| initial-xv6 | #1 |
| initial-xv6-tracer | [#2](https://github.com/platonoff-dev/yv6/issues/2) |
| scheduling-xv6-lottery | [#3](https://github.com/platonoff-dev/yv6/issues/3) |
| vm-xv6-intro | [#4](https://github.com/platonoff-dev/yv6/issues/4) |
| concurrency-xv6-threads | [#5](https://github.com/platonoff-dev/yv6/issues/5) |

Non-xv6 OSTEP projects are tracked in [ostep-projects](https://github.com/platonoff-dev/ostep-projects).

## Building and running

Requires a RISC-V toolchain and QEMU for `riscv64-softmmu`.

```sh
make qemu
```
