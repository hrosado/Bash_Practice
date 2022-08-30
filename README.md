\*\*# Bash_Practice
Bash Practice

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

