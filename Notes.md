#Compile Error(s) and Warning(s).


### List of Simple Fixes ###

  * Compile with MVS 6.0 SP5. If you have the Processor Pack?? installed you will get 2 warnings in CPUA.C Just ignore them.

  * Proper fix for above (Remove "THIS IS A..." from Debug Output) doh!
> change line 191 in ULTRA.H to
> `#`define RELEASE 1