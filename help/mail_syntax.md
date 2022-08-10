---
layout: help
title: mail syntax
syntax:
  - mail                         - View your inbox.
  - mail read [<num>]            - Read specified (or unread) message. 
  - mail write @<name> <subject> - Write a new message.
  - mail reply <num>             - Write a reply to the specified message.
  - mail delete <num>            - Delete specified message from inbox.

  - mail show                    - Show message you're currently writing.
  - mail list                    - List line numbers for current message.
  - mail +[<num>] <text>         - Add (or insert) line to current message.
  - mail ++[<num>] <text>        - As above, but paragraph instead of line.
  - mail -<num>                  - Delete line number of current message.
  - mail find <text>             - Find specified text in current message.
  - mail replace <a> with <b>    - Replace text in current message.
  - mail format                  - Format the text in the current message.

  - mail discard                 - Discard the current message.
  - mail send                    - Send the current message.
---

