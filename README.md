# asm-on-linux
Learning asm!!! Let's learn together!

# Installation
First, you will need an assembler. We will use nasm.

`sudo apt install gdb gcc binutils as31 nasm`

Done! This will include your `nasm` assembler and `ld` linker for creating executable assembly files.
# Create Your Executable: Compilation and Linking

Assemble:
`nasm -f elf64 <asmFile.s>`

Note: This will create a .o (out) file.

Linker:
`ld -s -o <asmFile> <asmFile.o>`
