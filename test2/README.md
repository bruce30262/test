


Some useful tools download from internet.

---------------------

checksec.sh
---------------
can be used to check some information of a ELF (PIE, NX, stack guard...)
**main usage:**
`./checksec.sh --file [filename] `
for more information, use`./checksec.sh --help` 
or check the official [website](http://www.trapkit.de/tools/checksec.html)


getenvaddr.c
-----------------

used to check the address of a **env** when executing a program
**usage:**
`./getenvaddr [env] [program]`


xocopy.c
----------------

used to dump an ELF, **even if you can't read the file** ( = with the permission `--x`)
**usage:**
`./xocopy [-a addr] <file>`
where addr is the memory address of the elf header
[official webpage](http://reverse.lostrealm.com/tools/xocopy.html)
