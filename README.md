![RiscV](https://camo.githubusercontent.com/143dba22c3a3598a9d816983e1ebe6039a8683e155b8f197970bf0242e830389/68747470733a2f2f72697363762e6f72672f77702d636f6e74656e742f75706c6f6164732f323032302f30362f72697363762d636f6c6f722e737667)

---
# Risc-V toolchain


Ready to use toolchain toward Risc-V architectures. <br>
More information about cooking your self compiler on the official [repo](https://github.com/riscv-collab/riscv-gnu-toolchain).

Compiled on Debian 12 toward 64 bits and 32 bits architecture.

Download [here](https://drive.google.com/drive/folders/11C1n7rLyf0IovMW2e5B_ucTmM_tOaJCT?usp=sharing)

---

### Exemple uses

```
RISCV=path/to/toolchain
```
> **GCC toolchain (32)**
```
$RISCV/bin/riscv32-unknown-linux-gnu-gcc -o hello_world hello_world.c
```

> **Clang toolchain**
```
$RISCV/bin/clang -march=rv64imafdc -o hello_world hello_world.c
```
