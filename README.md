# radare2-snippets
my custom made Radare2 scripts/snippets/commands.



### Padding, shifts, rotates and Cryptography

```
## logic right shift (0 padding)
rasm2 -C -a x64 -b 64 -w "shl"

## logic left shift (0 padding)
rasm2 -C -a x64 -b 64 -w "shr"





```
