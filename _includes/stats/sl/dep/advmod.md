

--------------------------------------------------------------------------------

## Treebank Statistics (UD_Slovenian)

This relation is universal.

10970 nodes (8%) are attached to their parents as `advmod`.

8396 instances of `advmod` (77%) are right-to-left (child precedes parent).
Average distance between parent and child is 2.13865086599818.

The following 31 pairs of parts of speech are connected with `advmod`: [sl-pos/VERB]()-[sl-pos/ADV]() (4407; 40% instances), [sl-pos/VERB]()-[sl-pos/PART]() (2446; 22% instances), [sl-pos/ADJ]()-[sl-pos/ADV]() (1267; 12% instances), [sl-pos/VERB]()-[sl-pos/CONJ]() (843; 8% instances), [sl-pos/ADJ]()-[sl-pos/PART]() (426; 4% instances), [sl-pos/NOUN]()-[sl-pos/ADV]() (381; 3% instances), [sl-pos/ADV]()-[sl-pos/ADV]() (373; 3% instances), [sl-pos/NOUN]()-[sl-pos/PART]() (197; 2% instances), [sl-pos/ADJ]()-[sl-pos/CONJ]() (128; 1% instances), [sl-pos/ADV]()-[sl-pos/PART]() (91; 1% instances), [sl-pos/NUM]()-[sl-pos/ADV]() (88; 1% instances), [sl-pos/VERB]()-[sl-pos/NUM]() (59; 1% instances), [sl-pos/NOUN]()-[sl-pos/CONJ]() (55; 1% instances), [sl-pos/DET]()-[sl-pos/ADV]() (46; 0% instances), [sl-pos/PRON]()-[sl-pos/ADV]() (34; 0% instances), [sl-pos/NUM]()-[sl-pos/PART]() (27; 0% instances), [sl-pos/PRON]()-[sl-pos/PART]() (26; 0% instances), [sl-pos/DET]()-[sl-pos/PART]() (23; 0% instances), [sl-pos/PROPN]()-[sl-pos/ADV]() (20; 0% instances), [sl-pos/ADJ]()-[sl-pos/NUM]() (7; 0% instances), [sl-pos/PRON]()-[sl-pos/CONJ]() (7; 0% instances), [sl-pos/NOUN]()-[sl-pos/X]() (4; 0% instances), [sl-pos/PROPN]()-[sl-pos/PART]() (4; 0% instances), [sl-pos/PROPN]()-[sl-pos/CONJ]() (3; 0% instances), [sl-pos/ADP]()-[sl-pos/ADV]() (2; 0% instances), [sl-pos/CONJ]()-[sl-pos/PART]() (1; 0% instances), [sl-pos/NOUN]()-[sl-pos/SCONJ]() (1; 0% instances), [sl-pos/NUM]()-[sl-pos/X]() (1; 0% instances), [sl-pos/PRON]()-[sl-pos/X]() (1; 0% instances), [sl-pos/PROPN]()-[sl-pos/X]() (1; 0% instances), [sl-pos/SCONJ]()-[sl-pos/ADV]() (1; 0% instances).


~~~ conllu
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 1 advmod	color:blue
1	Zdaj	zdaj	ADV	Rgp	Degree=Pos	4	advmod	_	Dep=4|Rel=AdvO
2	sem	biti	AUX	Va-r1s-n	Mood=Ind|Negative=Pos|Number=Sing|Person=1|Tense=Pres|VerbForm=Fin	4	aux	_	Dep=4|Rel=PPart
3	se	se	PRON	Px------y	PronType=Prs|Reflex=Yes|Variant=Short	4	expl	_	Dep=4|Rel=PPart
4	spomnil	spomniti	VERB	Vmep-sm	Aspect=Perf|Gender=Masc|Number=Sing|VerbForm=Part	0	root	_	SpaceAfter=No|Dep=0|Rel=Root
5	,	,	PUNCT	Z	_	9	punct	_	Dep=0|Rel=Root
6	kam	kam	ADV	Rgp	Degree=Pos	9	advmod	_	Dep=9|Rel=Conj
7	sem	biti	AUX	Va-r1s-n	Mood=Ind|Negative=Pos|Number=Sing|Person=1|Tense=Pres|VerbForm=Fin	9	aux	_	Dep=9|Rel=PPart
8	jo	on	PRON	Pp3fsa--y	Case=Acc|Gender=Fem|Number=Sing|Person=3|PronType=Prs|Variant=Short	9	dobj	_	Dep=9|Rel=Obj
9	vtaknil	vtakniti	VERB	Vmep-sm	Aspect=Perf|Gender=Masc|Number=Sing|VerbForm=Part	4	ccomp	_	SpaceAfter=No|Dep=4|Rel=Obj
10	!	!	PUNCT	Z	_	4	punct	_	SpaceAfter=No|Dep=0|Rel=Root

~~~


~~~ conllu
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 6 advmod	color:blue
1	Srebrni	srebrn	ADJ	Agpmsay	Case=Acc|Definite=Def|Degree=Pos|Gender=Masc|Number=Sing	3	amod	_	Dep=3|Rel=Atr
2	častni	časten	ADJ	Agpmsay	Case=Acc|Definite=Def|Degree=Pos|Gender=Masc|Number=Sing	3	amod	_	Dep=3|Rel=Atr
3	znak	znak	NOUN	Ncmsan	Animacy=Inan|Case=Acc|Gender=Masc|Number=Sing	5	dobj	_	Dep=5|Rel=Obj
4	je	biti	AUX	Va-r3s-n	Mood=Ind|Negative=Pos|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	5	aux	_	Dep=5|Rel=PPart
5	prejela	prejeti	VERB	Vmep-sf	Aspect=Perf|Gender=Fem|Number=Sing|VerbForm=Part	0	root	_	Dep=0|Rel=Root
6	tudi	tudi	PART	Q	_	5	advmod	_	Dep=0|Rel=Root
7	Pia	Pia	PROPN	Npfsn	Case=Nom|Gender=Fem|Number=Sing	5	nsubj	_	Dep=5|Rel=Sb
8	Mlakar	Mlakar	PROPN	Npfsn	Case=Nom|Gender=Fem|Number=Sing	7	name	_	SpaceAfter=No|Dep=7|Rel=Atr
9	.	.	PUNCT	Z	_	5	punct	_	SpaceAfter=No|Dep=0|Rel=Root

~~~


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 3 advmod	color:blue
1	Joj	joj	INTJ	I	_	5	discourse	_	SpaceAfter=No|Dep=0|Rel=Root
2	,	,	PUNCT	Z	_	1	punct	_	Dep=0|Rel=Root
3	kako	kako	ADV	Rgp	Degree=Pos	5	advmod	_	Dep=4|Rel=Conj
4	sem	biti	VERB	Va-r1s-n	Mood=Ind|Negative=Pos|Number=Sing|Person=1|Tense=Pres|VerbForm=Fin	5	cop	_	Dep=0|Rel=Root
5	raztresen	raztresen	ADJ	Appmsnn	Case=Nom|Definite=Ind|Degree=Pos|Gender=Masc|Number=Sing|VerbForm=Part	0	root	_	SpaceAfter=No|Dep=4|Rel=Atr
6	!	!	PUNCT	Z	_	5	punct	_	Dep=0|Rel=Root

~~~




--------------------------------------------------------------------------------

## Treebank Statistics (UD_Slovenian-SST)

This relation is universal.

3867 nodes (13%) are attached to their parents as `advmod`.

2770 instances of `advmod` (72%) are right-to-left (child precedes parent).
Average distance between parent and child is 2.07938970778381.

The following 47 pairs of parts of speech are connected with `advmod`: [sl-pos/VERB]()-[sl-pos/ADV]() (1673; 43% instances), [sl-pos/VERB]()-[sl-pos/PART]() (611; 16% instances), [sl-pos/VERB]()-[sl-pos/CONJ]() (297; 8% instances), [sl-pos/ADJ]()-[sl-pos/ADV]() (263; 7% instances), [sl-pos/NOUN]()-[sl-pos/ADV]() (195; 5% instances), [sl-pos/ADV]()-[sl-pos/ADV]() (164; 4% instances), [sl-pos/NOUN]()-[sl-pos/PART]() (115; 3% instances), [sl-pos/PRON]()-[sl-pos/ADV]() (84; 2% instances), [sl-pos/ADJ]()-[sl-pos/PART]() (82; 2% instances), [sl-pos/NOUN]()-[sl-pos/CONJ]() (42; 1% instances), [sl-pos/ADJ]()-[sl-pos/CONJ]() (37; 1% instances), [sl-pos/PRON]()-[sl-pos/PART]() (35; 1% instances), [sl-pos/PRON]()-[sl-pos/CONJ]() (33; 1% instances), [sl-pos/PROPN]()-[sl-pos/ADV]() (31; 1% instances), [sl-pos/ADV]()-[sl-pos/PART]() (30; 1% instances), [sl-pos/NUM]()-[sl-pos/ADV]() (27; 1% instances), [sl-pos/ADV]()-[sl-pos/CONJ]() (16; 0% instances), [sl-pos/DET]()-[sl-pos/ADV]() (13; 0% instances), [sl-pos/PROPN]()-[sl-pos/PART]() (13; 0% instances), [sl-pos/NUM]()-[sl-pos/PART]() (12; 0% instances), [sl-pos/PART]()-[sl-pos/PART]() (12; 0% instances), [sl-pos/AUX]()-[sl-pos/ADV]() (11; 0% instances), [sl-pos/PART]()-[sl-pos/ADV]() (9; 0% instances), [sl-pos/X]()-[sl-pos/ADV]() (8; 0% instances), [sl-pos/PROPN]()-[sl-pos/CONJ]() (7; 0% instances), [sl-pos/AUX]()-[sl-pos/CONJ]() (5; 0% instances), [sl-pos/VERB]()-[sl-pos/X]() (4; 0% instances), [sl-pos/X]()-[sl-pos/PART]() (4; 0% instances), [sl-pos/NOUN]()-[sl-pos/ADJ]() (3; 0% instances), [sl-pos/PART]()-[sl-pos/CONJ]() (3; 0% instances), [sl-pos/VERB]()-[sl-pos/ADJ]() (3; 0% instances), [sl-pos/VERB]()-[sl-pos/ADP]() (3; 0% instances), [sl-pos/X]()-[sl-pos/CONJ]() (3; 0% instances), [sl-pos/ADJ]()-[sl-pos/ADJ]() (2; 0% instances), [sl-pos/DET]()-[sl-pos/PART]() (2; 0% instances), [sl-pos/NOUN]()-[sl-pos/PRON]() (2; 0% instances), [sl-pos/VERB]()-[sl-pos/NUM]() (2; 0% instances), [sl-pos/VERB]()-[sl-pos/PRON]() (2; 0% instances), [sl-pos/ADJ]()-[sl-pos/NOUN]() (1; 0% instances), [sl-pos/ADJ]()-[sl-pos/NUM]() (1; 0% instances), [sl-pos/ADP]()-[sl-pos/ADV]() (1; 0% instances), [sl-pos/ADP]()-[sl-pos/PART]() (1; 0% instances), [sl-pos/NOUN]()-[sl-pos/ADP]() (1; 0% instances), [sl-pos/NUM]()-[sl-pos/CONJ]() (1; 0% instances), [sl-pos/NUM]()-[sl-pos/NUM]() (1; 0% instances), [sl-pos/NUM]()-[sl-pos/PRON]() (1; 0% instances), [sl-pos/PRON]()-[sl-pos/ADJ]() (1; 0% instances).


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 3 advmod	color:blue
1	pa	pa	CONJ	Cc	_	2	advmod	_	word=pa|msd=Vp
2	greš	iti	VERB	Vmbr2s	Mood=Ind|Number=Sing|Person=2|Tense=Pres|VerbForm=Fin	0	root	_	word=greš|msd=Ggvsde
3	ven	ven	ADV	Rgp	Degree=Pos	2	advmod	_	word=vn|msd=Rsn
4	pa	pa	CONJ	Cc	_	2	cc	_	word=pa|msd=Vp
5	prideš	priti	VERB	Vmer2s	Aspect=Perf|Mood=Ind|Number=Sing|Person=2|Tense=Pres|VerbForm=Fin	2	conj	_	word=prieš|msd=Ggdsde
6	nazaj	nazaj	ADV	Rgp	Degree=Pos	5	advmod	_	word=nazaj|msd=Rsn

~~~


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 2 advmod	color:blue
1	saj	saj	CONJ	Cc	_	4	cc	_	word=s|msd=Vp
2	še	še	PART	Q	_	4	advmod	_	word=še|msd=L
3	ne	ne	PART	Q	_	4	neg	_	word=ne|msd=L
4	vem	vedeti	VERB	Vmpr1s	Aspect=Imp|Mood=Ind|Number=Sing|Person=1|Tense=Pres|VerbForm=Fin	0	root	_	word=vem|msd=Ggnspe
5	kam	kam	ADV	Rgp	Degree=Pos	4	ccomp	_	word=kam|msd=Rsn
6	v	v	ADP	Sa	Case=Acc	7	case	_	word=v|msd=Dt
7	avstralijo	Avstralija	PROPN	Npfsa	Case=Acc|Gender=Fem|Number=Sing	4	parataxis	_	word=Avstralijo|msd=Slzet
8	ali	ali	CONJ	Cc	_	7	cc	_	word=al|msd=Vp
9	pa	pa	CONJ	Cc	_	8	mwe	_	word=pa|msd=Vp
10	v	v	ADP	Sa	Case=Acc	11	case	_	word=v|msd=Dt
11	ameriko	Amerika	PROPN	Npfsa	Case=Acc|Gender=Fem|Number=Sing	7	conj	_	word=Ameriko|msd=Slzet

~~~


~~~ conllu
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 1 advmod	color:blue
1	pa	pa	CONJ	Cc	_	2	advmod	_	word=pa|msd=Vp
2	greš	iti	VERB	Vmbr2s	Mood=Ind|Number=Sing|Person=2|Tense=Pres|VerbForm=Fin	0	root	_	word=greš|msd=Ggvsde
3	ven	ven	ADV	Rgp	Degree=Pos	2	advmod	_	word=vn|msd=Rsn
4	pa	pa	CONJ	Cc	_	2	cc	_	word=pa|msd=Vp
5	prideš	priti	VERB	Vmer2s	Aspect=Perf|Mood=Ind|Number=Sing|Person=2|Tense=Pres|VerbForm=Fin	2	conj	_	word=prieš|msd=Ggdsde
6	nazaj	nazaj	ADV	Rgp	Degree=Pos	5	advmod	_	word=nazaj|msd=Rsn

~~~


