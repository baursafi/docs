---
udver: '2'
layout: relation
title: 'obl:sentcon'
shortdef: 'sentence-initial discourse connective'
---

The relation `obl:sentcon` denotes pronouns that are used as sentence-initial discourse connectives.

~~~ sdparse
Upe rire ma kova'e mitã'i , cheremiarirõ'i oiko , ojau . \n Then after BDY this little-child , my-grandchild live , born .
obl:sentcon(oiko, Upe)
case(Upe, rire)
dep:mod(Upe, ma)
obl:sentcon(live, Then)
case(Then, after)
dep:mod(Then, BDY)
~~~

“And then this one, my grandchild, was born.”

<!-- Interlanguage links updated St lis 3 20:59:06 CET 2021 -->
