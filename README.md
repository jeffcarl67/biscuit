XXX write me

the root of the repository contains the Go 1.4 tools/runtime. some of Biscuit's
code is modifications to the runtime, mostly in src/runtime/os_linux.{c,go}.

the vast majority of Biscuit's code is in biscuit/

you must build the go runtime before building Biscuit:

( cd src/ && ./make.bash )

then run Biscuit:

( cd biscuit/ && make qemu CPUS=2 )

then type a command:
ls
