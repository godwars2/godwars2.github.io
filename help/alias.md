---
layout: help
title: alias
syntax:
  - alias list
  - alias add <new alias name> <expanded string>
  - alias show <alias name>
  - alias delete <alias name>
---

This command allows you to set aliases - customised commands, so to speak.  So
for example typing 'alias add forwards ff' would mean that whenever you typed 
'forwards', the mud would treat it as if you had typed 'ff' (feet forwards).

You may also include wildcards - %1, %2, %3, etc to represent single words, or
@1, @2, @3, etc to represent the word argument plus everything else up until 
the end of the line.  Thus if you typed 'alias add mutter say %1', the mutter 
alias would only say the first word you typed (so 'mutter hello there' would 
be the same as 'say hello'). But 'alias add mutter say @1' would cause the 
mutter alias to work exactly the same as say.

It is possible to have an alias with the same name as a command or social, in 
which case the alias will have priority.  So 'alias add grin grin %1 wickedly' 
(for example) would effectively give you a new default for the grin social.

Finally, you may also use the ':' character to separate multiple aliases - for 
example 'alias add walk stop:clear:target %1:ff'.
