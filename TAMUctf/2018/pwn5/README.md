This challenge has a `stack overflow` vulnerability, by which you can overwrite the return address. Then, using `return oriented programing (ROP)`, you are able to spawn `/bin/sh`.

There are nice writeups for this in CTFTime! (Generally for ROP gadgets)
