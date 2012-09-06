stutter
=======

Echos stdin to stdout and also pipes it to our own args, which are interpreted as a shell command.

This lets you say `foo | stutter bar`, which works like `foo | bar` but shows you what's passing between them.

This command is what I irrationally want `foo | tee - | bar` to do.

