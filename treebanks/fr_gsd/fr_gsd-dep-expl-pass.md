---
layout: base
title:  'Statistics of expl:pass in UD_French-GSD'
udver: '2'
---

## Treebank Statistics: UD_French-GSD: Relations: `expl:pass`

This relation is a language-specific subtype of <tt><a href="fr_gsd-dep-expl.html">expl</a></tt>.
There are also 2 other language-specific subtypes of `expl`: <tt><a href="fr_gsd-dep-expl-pv.html">expl:pv</a></tt>, <tt><a href="fr_gsd-dep-expl-subj.html">expl:subj</a></tt>.

768 nodes (0%) are attached to their parents as `expl:pass`.

768 instances of `expl:pass` (100%) are right-to-left (child precedes parent).
Average distance between parent and child is 1.13020833333333.

The following 1 pairs of parts of speech are connected with `expl:pass`: <tt><a href="fr_gsd-pos-VERB.html">VERB</a></tt>-<tt><a href="fr_gsd-pos-PRON.html">PRON</a></tt> (768; 100% instances).


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 3 expl:pass	color:blue
1	La	le	DET	_	Definite=Def|Gender=Fem|Number=Sing|PronType=Art	2	det	_	wordform=la
2	Selle-en-Luitré	Selle-en-Luitré	PROPN	_	Gender=Fem|Number=Sing	4	nsubj:pass	_	_
3	se	se	PRON	_	Person=3|PronType=Prs|Reflex=Yes	4	expl:pass	_	_
4	trouve	trouver	VERB	_	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	0	root	_	_
5	à	à	ADP	_	_	6	case	_	_
6	environ	environ	ADV	_	_	4	obl:arg	_	_
7	:	:	PUNCT	_	_	4	punct	_	_

~~~


