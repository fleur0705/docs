---
layout: base
title:  'Statistics of amod in UD_Turkish_German-SAGT'
udver: '2'
---

## Treebank Statistics: UD_Turkish_German-SAGT: Relations: `amod`

This relation is universal.

501 nodes (2%) are attached to their parents as `amod`.

488 instances of `amod` (97%) are right-to-left (child precedes parent).
Average distance between parent and child is 1.32934131736527.

The following 12 pairs of parts of speech are connected with `amod`: <tt><a href="qtd_sagt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="qtd_sagt-pos-ADJ.html">ADJ</a></tt> (436; 87% instances), <tt><a href="qtd_sagt-pos-VERB.html">VERB</a></tt>-<tt><a href="qtd_sagt-pos-ADJ.html">ADJ</a></tt> (23; 5% instances), <tt><a href="qtd_sagt-pos-PROPN.html">PROPN</a></tt>-<tt><a href="qtd_sagt-pos-ADJ.html">ADJ</a></tt> (12; 2% instances), <tt><a href="qtd_sagt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="qtd_sagt-pos-ADV.html">ADV</a></tt> (6; 1% instances), <tt><a href="qtd_sagt-pos-PRON.html">PRON</a></tt>-<tt><a href="qtd_sagt-pos-ADJ.html">ADJ</a></tt> (6; 1% instances), <tt><a href="qtd_sagt-pos-ADJ.html">ADJ</a></tt>-<tt><a href="qtd_sagt-pos-ADJ.html">ADJ</a></tt> (4; 1% instances), <tt><a href="qtd_sagt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="qtd_sagt-pos-DET.html">DET</a></tt> (4; 1% instances), <tt><a href="qtd_sagt-pos-ADV.html">ADV</a></tt>-<tt><a href="qtd_sagt-pos-ADJ.html">ADJ</a></tt> (3; 1% instances), <tt><a href="qtd_sagt-pos-PROPN.html">PROPN</a></tt>-<tt><a href="qtd_sagt-pos-PROPN.html">PROPN</a></tt> (3; 1% instances), <tt><a href="qtd_sagt-pos-NUM.html">NUM</a></tt>-<tt><a href="qtd_sagt-pos-ADJ.html">ADJ</a></tt> (2; 0% instances), <tt><a href="qtd_sagt-pos-ADJ.html">ADJ</a></tt>-<tt><a href="qtd_sagt-pos-ADV.html">ADV</a></tt> (1; 0% instances), <tt><a href="qtd_sagt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="qtd_sagt-pos-PRON.html">PRON</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 9	bgColor:blue
# visual-style 9	fgColor:white
# visual-style 9 8 amod	color:blue
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
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 3 amod	color:blue
1	Also	also	ADV	_	_	4	advmod	_	LangID=DE
2	sınavlar	sınav	NOUN	_	Case=Nom|Number=Plur	4	nsubj	_	LangID=TR
3	iyi	iyi	ADJ	_	_	4	amod	_	LangID=TR
4	geçti	geç	VERB	_	Aspect=Perf|Evident=Fh|Mood=Ind|Number=Sing|Person=3|Tense=Past	0	root	_	LangID=TR
5	aslında	aslında	ADV	_	_	4	advmod	_	LangID=TR
6	öyle	öyle	ADV	_	_	9	discourse	_	LangID=TR
7	fazla	fazla	ADJ	_	_	9	amod	_	LangID=TR
8	zorluk	zorluk	NOUN	_	Case=Nom|Number=Sing	9	obj	_	LangID=TR
9	yaşamadım	yaşa	VERB	_	Aspect=Perf|Evident=Fh|Mood=Ind|Number=Sing|Person=1|Polarity=Neg|Tense=Past	4	advcl	_	LangID=TR|SpaceAfter=No
10	.	.	PUNCT	_	_	4	punct	_	LangID=OTHER

~~~


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 4 amod	color:blue
1	Ben	ben	PRON	_	Case=Nom|Number=Sing	2	nsubj	_	LangID=TR
2	isterdim	iste	VERB	_	Aspect=Hab|Evident=Fh|Mood=Ind|Number=Sing|Person=1|Tense=Past	0	root	_	LangID=TR
3	daha	daha	ADV	_	_	4	advmod	_	LangID=TR
4	fazla	fazla	ADJ	_	_	5	amod	_	LangID=TR
5	Deutsch	deutsch	PROPN	_	Case=Nom|Gender=Neut|Number=Sing	2	obj	_	LangID=DE|SpaceAfter=No
6	,	,	PUNCT	_	_	7	punct	_	LangID=OTHER
7	aber	aber	ADV	_	_	2	conj	_	LangID=DE|SpaceAfter=No
8	.	.	PUNCT	_	_	2	punct	_	LangID=OTHER

~~~


