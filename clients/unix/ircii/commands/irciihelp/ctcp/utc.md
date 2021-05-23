---
title: 'ircii help: utc'
author: Michael Sandrof, Troy Rollo, Matthew R. Green
datecreated: 3 August 2020
layout: default
license: ircii
summary: >
  ircii version: 20190117
  create with help2md.pl
---
```
Usage: CTCP <nick> UTC <system time>
  This is primarily for robots to send date and time information
  to users and have it displayed in local time. The format of the
  UTC CTCP is:
    UTC number
  where number is the ASCII representation of the 32 bit
  integer representing the time as is used on UNIX machines.
  When IRCII receives this CTCP, it replaces the text of
  the local time expressed in the local language back into
  the original message. Thus if you send the following:
    NOTICE nick The time is ^AUTC 702777074^A
  The user might see:
    -yournick- The time is Thu Apr  9 09:51:14 1992
  (if their timezone is Australian Eastern Standard Time).
  Obviously you can use the $TIME() function here effectively.
```

[index](index.html)
[up](..)

<small> ircii 20190117 </small>