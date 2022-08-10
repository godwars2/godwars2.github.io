---
layout: help
title: emote
syntax:
  - emote <text>
  - emote @ <target> <verb> <text from target's perspective>
  - emote @ <target> <text containing 'you', 'your' or 'yours'>
---

This command allows your character to 'emote' an action - whatever text you 
type will appear after your name.  For example, 'emote grins' will display the 
message 'Player grins' to everyone within 25 feet.

Note that you may also specify a target, by placing '@ <their name>' as the 
first argument - for example 'emote @kavir grins' (no space is needed after 
the '@').  The first word you type ('grins' in the previous example) is the 
verb, and the mud will automatically insert an 'at you' after it unless you 
specifically include the word 'you', 'your' or 'yours' somewhere in the text.

Note that a full stop (period) is automatically added at the end of the text 
unless you've explicitly terminated the text with your own punctuation.

The , (comma) character is a shortcut for 'emote'.  You may also substitute 
'to' for '@' if you wish.
