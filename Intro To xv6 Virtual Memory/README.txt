Null-pointer Dereference & Read-only Code

added system calls
int mprotect(void *addr, int len)
int munprotect(void *addr, int len)

Changes in:

exec.c
defs.h
syscall.c
sysproc.c
sysfunc.h
vm.c