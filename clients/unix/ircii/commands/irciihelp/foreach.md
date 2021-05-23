---
title: 'ircii help: foreach'
author: Michael Sandrof, Troy Rollo, Matthew R. Green
datecreated: 3 August 2020
layout: default
license: ircii
summary: >
  ircii version: 20190117
  create with help2md.pl
---
```
Usage: FOREACH <structure> <variable> { <commands> }
       FOR <structure> <variable> { <commands> }
       FOR (<commence,<evaluation>,<iteration>) { <commands> }
  This causes <commands> to be executed once for each 
  element in the structure.  The aliases inside the {} 
  are not expanded until execution unless the leading { 
  is quoted like \{
  The 2nd style of FOR allows C-style for loops.
  Here are a couple examples of basic foreach commands.
    assign blue.1 one
    assign blue.2 two 
    assign blue.3 three
    foreach blue ii { echo $ii $blue[$ii] }
  will return
    1 one
    2 two
    3 three
  FOREACH can also be imbedded such as in the following example.
    assign blue.1.1 one one
    assign blue.1.2 one two
    assign blue.2.1 two one
    assign blue.2.2 two two
    alias showblue {
      foreach blue ii
      {
        foreach blue.$ii jj
        {
	  echo $ii $jj $blue[$ii][$jj]
        }
      }
    }
  And /showblue returns.. 
    1 1 one one
    1 2 one two 
    2 1 two one
    2 2 two two

Note:
  When using this format the {} in the foreach must be on separate 
  lines by themselves.  This is true for IF and WHILE as well.

  Notice that variable names 'ii' and 'jj' were used.  Any name can
  be used for the index but keep in mind that single letter vars can
  interfere with the built in single char vars.  See ALIAS special

```
See Also:
  [expressions](expressions.html)
  [ALIAS special](alias/special.html)

[index](index.html)
[up](..)

<small> ircii 20190117 </small>