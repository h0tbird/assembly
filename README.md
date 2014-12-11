assembly
========

Let's learn some assembly programming:

- http://cs.lmu.edu/~ray/notes/nasmexamples/
- http://eli.thegreenplace.net/2011/09/06/stack-frame-layout-on-x86-64/
- http://0xax.blogspot.com.es/2014/08/say-hello-to-x64-assembly-part-1.html
- http://www.pentesteracademy.com/course?id=7

````
gdb -q ./a.out -tui
````
````
(gdb) set disassembly-flavor intel
(gdb) break _start
(gdb) run
(gdb) layout asm
(gdb) layout regs
(gdb) stepi
````
