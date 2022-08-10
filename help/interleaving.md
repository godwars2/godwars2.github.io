---
layout: help
title: interleaving
---

When queuing up multiple combat techniques, you should use an approach called 
interleaving.  For example if you want to perform three strikes with each hand,
rather than typing 'ls', 'ls', 'ls', 'rs', 'rs', 'rs', you should instead type 
'ls', 'rs', 'ls', 'rs', 'ls', 'rs', so that the techniques alternate between 
your left and right hand.

The reason for this is that commands come off the queue in the order that they
were added.  If you enter all of the left strikes first, then no right strikes
will come off the queue until all of the left ones have first been used.  While
this might initially seem counterintuitive, it does ensure that all your queued
commands will be performed.

If you type 'config interleaving', each location will instead pull techniques 
off the queue as soon as possible.  However you should be aware that this may 
result in situations where high-AP techs never came off the queue, because the 
cheaper techs are performed the moment you have sufficient AP.
