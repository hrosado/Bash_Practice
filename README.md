
**Bash Practice**

Use the _type_ command to identify whether a word is a _keyword_, _builtin_, or _file_.

\$ type -t if
keyword

\$ type -t pwd
builtin

\$ type -t ls
file

Use the _script_ command to record actions.

The *compgen* command provides a list of *commands*, *builtins*, and *keywords*.

\$ compgen -c [list commands]

\$ compgen -b [list buitins]

\$ compgen -k [list keywords]


Example of *redirection* and *piping*:
handywork < data.in > results.out

stdin 	= 0
stdout 	= 1
strerr	= 2

handywork 2> err.msgs

Example of all three:
handywork < data.in > results.out 2> err.msgs

stderr (2) 
file location or filename (&1)

handywork < data.in &> results.out



