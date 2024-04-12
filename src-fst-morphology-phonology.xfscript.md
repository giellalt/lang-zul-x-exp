Rule file for Zulu

Definitions

Define Vow, Cns, Syll, Dummy

Rules

!Insertion change

{{{define uwChange [ u -> w || _ %> a ] ; }}}
* to handle diminutive abantu - abantwana

{{{define yInsert [ [..] -> y || Vow %> _ Vow ] ; }}}

!Deletion rules

PrefixShortening umu to um

VowelSimplification a u to o

* * *

<small>This (part of) documentation was generated from [src/fst/morphology/phonology.xfscript](https://github.com/giellalt/lang-zul-x-exp/blob/main/src/fst/morphology/phonology.xfscript)</small>
