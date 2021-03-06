---
layout: base
title:  'Statistics of aux:q in UD_Turkish_German-SAGT'
udver: '2'
---

## Treebank Statistics: UD_Turkish_German-SAGT: Relations: `aux:q`

This relation is a language-specific subtype of <tt><a href="qtd_sagt-dep-aux.html">aux</a></tt>.
There are also 1 other language-specific subtypes of `aux`: <tt><a href="qtd_sagt-dep-aux-pass.html">aux:pass</a></tt>.

144 nodes (0%) are attached to their parents as `aux:q`.

131 instances of `aux:q` (91%) are left-to-right (parent precedes child).
Average distance between parent and child is 1.09027777777778.

The following 8 pairs of parts of speech are connected with `aux:q`: <tt><a href="qtd_sagt-pos-VERB.html">VERB</a></tt>-<tt><a href="qtd_sagt-pos-AUX.html">AUX</a></tt> (61; 42% instances), <tt><a href="qtd_sagt-pos-PART.html">PART</a></tt>-<tt><a href="qtd_sagt-pos-AUX.html">AUX</a></tt> (31; 22% instances), <tt><a href="qtd_sagt-pos-ADJ.html">ADJ</a></tt>-<tt><a href="qtd_sagt-pos-AUX.html">AUX</a></tt> (20; 14% instances), <tt><a href="qtd_sagt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="qtd_sagt-pos-AUX.html">AUX</a></tt> (15; 10% instances), <tt><a href="qtd_sagt-pos-PROPN.html">PROPN</a></tt>-<tt><a href="qtd_sagt-pos-AUX.html">AUX</a></tt> (8; 6% instances), <tt><a href="qtd_sagt-pos-PRON.html">PRON</a></tt>-<tt><a href="qtd_sagt-pos-AUX.html">AUX</a></tt> (5; 3% instances), <tt><a href="qtd_sagt-pos-ADV.html">ADV</a></tt>-<tt><a href="qtd_sagt-pos-AUX.html">AUX</a></tt> (3; 2% instances), <tt><a href="qtd_sagt-pos-INTJ.html">INTJ</a></tt>-<tt><a href="qtd_sagt-pos-AUX.html">AUX</a></tt> (1; 1% instances).


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 4 aux:q	color:blue
1	Eh	Eh	INTJ	_	_	3	discourse	_	LangID=TR
2	iyi	iyi	ADV	_	_	3	advmod	_	LangID=TR
3	hazırlandın	hazırlan	VERB	_	Aspect=Perf|Evident=Fh|Mood=Ind|Number=Sing|Person=2|Tense=Past	0	root	_	LangID=TR
4	mı	mi	AUX	_	Number=Sing|Person=3	3	aux:q	_	LangID=TR
5	şimdi	şimdi	NOUN	_	Case=Nom|Number=Sing	3	obl	_	LangID=TR
6	für	für	ADP	_	_	9	case	_	LangID=DE
7	die	der	DET	_	Case=Acc|Definite=Def|Gender=Fem|Number=Plur|PronType=Art	9	det	_	LangID=DE
8	mündlichen	_	ADJ	_	Case=Acc|Gender=Fem	9	amod	_	LangID=DE
9	Prüfungen	Prüfung	NOUN	_	Case=Acc|Gender=Fem|Number=Plur	3	obj	_	LangID=DE|SpaceAfter=No
10	?	?	PUNCT	_	_	3	punct	_	LangID=OTHER

~~~


~~~ conllu
# visual-style 9	bgColor:blue
# visual-style 9	fgColor:white
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 8 9 aux:q	color:blue
1	Vor	vor	ADP	_	_	2	case	_	LangID=DE
2	allem	alle	PRON	_	Case=Dat|Definite=Ind|Gender=Neut|Number=Sing|PronType=Ind	5	obl	_	LangID=DE
3	so	so	ADV	_	_	5	advmod	_	LangID=DE
4	mega	mega	ADJ	_	_	5	advmod	_	LangID=DE
5	perfektionistisch	perfektionistisch	ADJ	_	_	0	root	_	LangID=DE
6	filan	falan	ADV	_	_	5	advmod	_	LangID=TR|SpaceAfter=No
7	,	,	PUNCT	_	_	8	punct	_	LangID=OTHER
8	değil	değil	PART	_	_	5	parataxis:discourse	_	LangID=TR
9	mi	mi	AUX	_	Number=Sing|Person=3	8	aux:q	_	LangID=TR
10	ki	ki	ADV	_	_	8	advmod	_	SpaceAfter=No
11	.	.	PUNCT	_	_	5	punct	_	LangID=OTHER

~~~


~~~ conllu
# visual-style 9	bgColor:blue
# visual-style 9	fgColor:white
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 8 9 aux:q	color:blue
1	Ehm	ehm	INTJ	_	_	8	discourse	_	LangID=TR
2	orda	ora	PRON	_	Case=Loc|Number=Sing	8	obl	_	LangID=TR
3	etrafında	etraf	NOUN	_	Case=Loc|Number=Sing|Number[psor]=Sing|Person[psor]=2	8	obl	_	LangID=TR
4	aber	aber	CCONJ	_	_	8	cc	_	LangID=DE
5	ge--	genç	ADJ	_	_	6	reparandum	_	LangID=DE
6	genç	genç	ADJ	_	_	8	nsubj	_	LangID=TR
7	de	de	ADV	_	_	6	advmod:emph	_	LangID=TR
8	var	var	ADJ	_	_	0	root	_	LangID=TR
9	mı	mi	AUX	_	Number=Sing|Person=3	8	aux:q	_	LangID=TR
10	so	so	ADV	_	_	8	advmod	_	LangID=DE|SpaceAfter=No
11	?	?	PUNCT	_	_	8	punct	_	LangID=OTHER

~~~


