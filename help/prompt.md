---
layout: help
title: prompt
syntax:
  - prompt <text>
  - cprompt <text>
  - display
---

These commands allow you to customise your prompts.  Type 'display' to view a 
list of the variables that can be used within your prompts.

For example, you could type 'prompt $h/$H ($a)> ' to show your current Health, 
maximum Health, and action points (this is also the default prompt).

The 'prompt' command sets your normal prompt, while 'cprompt' sets your combat 
prompt.  If you have a combat prompt defined, you will see it instead of your 
regular prompt while you have an adrenaline rush.  If you only want to see the 
one prompt, type 'cprompt clear' and stick to the regular 'prompt' command.

Typing 'config prompt' will hide your prompt/s.

See also: display colour
