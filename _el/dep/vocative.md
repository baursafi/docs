---
layout: relation
title: 'vocative'
shortdef: 'vocative'
udver: '2'
---

The *vocative* relation is used to mark a dialogue participant addressed in text (common in emails and newsgroup postings). The relation links the addressee's name to its host sentence.

~~~ sdparse
Κύριοι , έχετε βαριά ευθύνη
vocative(έχετε, Κύριοι)
~~~

~~~ sdparse
ROOT Καλημέρα , συνάδελφοι
vocative(Καλημέρα, συνάδελφοι)
root(ROOT, Καλημέρα)
~~~

<!--
TODO
~~~ sdparse
Κύριε Πρόεδρε , έχετε το λόγο
vocative(έχετε, Πρόεδρε)
~~~
-->
<!-- Interlanguage links updated St lis 3 20:59:10 CET 2021 -->
