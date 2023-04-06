### ENTRYPOINT

ENTRYPOINT is used to run the container just like CMD . But there are few differences.
Main diffrence is we can't override in ENTRYPOINT , but we can override in CMD.
We cant override ENTRYPOINT, if you try to do so it will go and append to ENTRYPOINT command.
CMD will supply default arguments to ENTRYPOINT.
You can always override at the runtime.