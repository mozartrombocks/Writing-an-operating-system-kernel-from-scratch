# Writing a 64-bit operating system kernel from scratch
Prerequisites required to install if not installed already:
  -> nasm, qemu, xorriso, grub-common, x86_64_elf-ld, x86_64_elf-gcc
 
BUILD: 
  -> make build-x86_64
  
EMULATE: 
  -> qemu-system-x86_64 -cdrom dist/x86_64/kernel.iso
