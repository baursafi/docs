---
layout: base
title:  'UD_Moksha-JR'
udver: '2'
---

<!-- This page is automatically generated from the README file and from
     the data files in the latest release.

     Please do not edit this page directly. -->

# UD Moksha JR

Language: [Moksha](/mdf/index.html) (code: `mdf`)<br/>
Family: Uralic, Mordvin

This treebank has been part of Universal Dependencies since the UD v2.5 release.

The following people have contributed to making this treebank part of UD: Jack Rueter, Maria Levina, Nadezhda Kabaeva, Judit Molnár.

Repository: [UD_Moksha-JR](https://github.com/UniversalDependencies/UD_Moksha-JR)<br />
Search this treebank on-line: [PML-TQ](https://lindat.mff.cuni.cz/services/pmltq/#!/treebank/udmdf_jr29)<br />
Download all treebanks: [UD 2.9](/#download)

License: CC BY-SA 4.0

Genre: nonfiction, news

Questions, comments?
General annotation questions (either Moksha-specific or cross-linguistic) can be raised in the [main UD issue tracker](https://github.com/UniversalDependencies/docs/issues).
You can report bugs in this treebank in the [treebank-specific issue tracker on Github](https://github.com/UniversalDependencies/UD_Moksha-JR/issues).
If you want to collaborate, please contact [rueter&nbsp;•&nbsp;jack&nbsp;(æt)&nbsp;gmail&nbsp;•&nbsp;com].
Development of the treebank happens directly in the UD repository, so you may submit bug fixes as pull requests against the dev branch.

| Annotation | Source |
|------------|--------|
| Lemmas | annotated manually in non-UD style, automatically converted to UD |
| UPOS | annotated manually in non-UD style, automatically converted to UD |
| XPOS | annotated manually |
| Features | annotated manually in non-UD style, automatically converted to UD |
| Relations | annotated manually in non-UD style, automatically converted to UD |

## Description

Erme Universal Dependencies annotated texts Moksha are the origin of UD_Moksha-JR with annotation (CoNLL-U) for texts in the Moksha language,
it originally consists of a sample from a number of fiction authors writing originals in Moksha.




This is a collection of sentences from almost entirely original Moksha-language literary sources dating back to the 1880s with
Universal Dependencies (UD) annotations. It has been constructed in alignment with parallel work on Erzya language Universal Dependencies.

There are also about 20 parallel sentences translated by Marina Levina from the Erzya and Russian
texts: [http://ilazki.thinkgeek.co.uk/brat/#/uralic/myv](http://ilazki.thinkgeek.co.uk/brat/#/uralic/myv) and
[http://ilazki.thinkgeek.co.uk/brat/#/uralic/rus](http://ilazki.thinkgeek.co.uk/brat/#/uralic/rus)

The sent_id attribute value is not randomized in works published earlier than 1938. Developing UD documentation can be found at https://github.com/UniversalDependencies/docs for Erzya.

[https://github.com/rueter/erme-ud-moksha](https://github.com/rueter/erme-ud-moksha)


## Acknowledgments

The original annotation has been performed by Jack Rueter at the University of Helsinki with the help of Marina Levina
at the Mordovian State University im. P.N. Ogariova, Mordvin Languages Department using morphological tools
that were originally built with funding from a Kone Foundation «Language Programme» funded project:
«Creation of Morphological Parsers for Minority Finno-Ugrian Languages» (2013–2014) with the linguistic work of
Merja Salo, and facilitated at the Norwegian Arctic University in Tromsø. Work with the Moksha treebank
builds upon previous experience with the UD_Erzya-JR treebank and continued consultations and discussions
with Francis Tyers, Tommi Pirinen, Jonathan Washington. Without the Moksha writers themselves, however, we would be no where…

Annotation work is simultaneous to finite-state transducer development by Nadjezhda Kabaeva, Marina Levina and Jack Rueter in the [GiellaLT](https://giellalt.uit.no/lang-mdf) infrastucture, which also works with Constraint Grammar disambiguation of the morphological analysis.

## References

If you use this data set in an academic publication, I would be ever so grateful if you cited it as follows:

Jack Rueter. (2018, January 20). Erme UD Moksha (Version v1.0) http://doi.org/10.5281/zenodo.1156112

[![DOI](https://zenodo.org/badge/118232421.svg)](https://zenodo.org/badge/latestdoi/118232421)


## About the authors

- Кузнецов, Юрий 1975: *Сембось ушеткшни киста*. Саранск.
- Mishanina, V. I. (Мишанина, В. И.) 1972: *Лиендень очконяса*. Мокша №3, 38–39. Саранск. (MishaninaValentina_LiendenyOchkonyasa_Moksha-1972-No2-pp38-39) (Мордовиянь Кадошкина аймаконь Адаж веле)
- * Мокшень кяль. Синтаксис* : учебник / аноклаф-тиф Н. С. Алямкинонь и О. Е. Поляковонь профессорхнень вятемаснон ала. -- Саранск : Изд-во Мордов. ун-та, 2008. -- 200 с. -- На морд.-мокша яз.
- Pyanzin, Fyodor (Пьянзин, Фёдор) 1991: *Седить тердеманц коряс*: Повесть. -- Саранск: Мордов. кн. изд-во, 1991. -- 120 с. Мордов.-мокша яз.

In release 2.7 additional example sentences used in the Moksha-language grammar *Мокшень кяль, синтаксис: учебник* (2008) were included. These sentences are marked with sent_id-s that contain the components `MKS:2008:page:n-th sentence:original author`. It is hoped that the inclusion of these sentences will help cover various grammatical phenomena in Moksha syntax. When refering to these sentences, we advise you also cite the original source:

- Алямкин, Н. С. (гл. ред.); Гришунина, В. П.; Иванова, Г. С.; Кабаева, Н. Ф.; Кулакова, Н. А.; Левина, М. З.; Поляков, О. Е. (гл. ред.); Рогожина, В. Ф.; Седова, П. Е. 2008: * Мокшень кяль. Синтаксис : учебник [Moksha language. Syntax: reader]. -- Саранск : Изд-во Мордов. ун-та.
- Alâmkin, N. S. (chief ed.); Grushinina, V. P.; Ivanova, G. S.; Kabaeva, N. F.; Kulakova, N. A.; Levina, M. Z.; Polâkov, O. E. (chief ed.); Rogozhina, V. F.; Sedova, P. E. 2008: * Mokshen' kâl'. Sintaksis: uchebnik [Moksha language. Syntax: reader]. -- Saransk : Izd-vo Mordov. un-ta.
- Kehayov, Petar 2020: Between facts and speech acts: The conditional and condictional-conjunctive in Moksha Mordvin. *Linguistica Uralica LVI 2020 1* [https://dx.doi.org/10.3176/lu.2020.1.03]


# Statistics of UD Moksha JR

## POS Tags

[ADJ](mdf_jr-pos-ADJ.html) – [ADP](mdf_jr-pos-ADP.html) – [ADV](mdf_jr-pos-ADV.html) – [AUX](mdf_jr-pos-AUX.html) – [CCONJ](mdf_jr-pos-CCONJ.html) – [DET](mdf_jr-pos-DET.html) – [INTJ](mdf_jr-pos-INTJ.html) – [NOUN](mdf_jr-pos-NOUN.html) – [NUM](mdf_jr-pos-NUM.html) – [PART](mdf_jr-pos-PART.html) – [PRON](mdf_jr-pos-PRON.html) – [PROPN](mdf_jr-pos-PROPN.html) – [PUNCT](mdf_jr-pos-PUNCT.html) – [SCONJ](mdf_jr-pos-SCONJ.html) – [VERB](mdf_jr-pos-VERB.html) – [X](mdf_jr-pos-X.html)

## Features

[Abbr](mdf_jr-feat-Abbr.html) – [AdpType](mdf_jr-feat-AdpType.html) – [AdvType](mdf_jr-feat-AdvType.html) – [Animacy](mdf_jr-feat-Animacy.html) – [Aspect](mdf_jr-feat-Aspect.html) – [Case](mdf_jr-feat-Case.html) – [Clitic](mdf_jr-feat-Clitic.html) – [Connegative](mdf_jr-feat-Connegative.html) – [Definite](mdf_jr-feat-Definite.html) – [Degree](mdf_jr-feat-Degree.html) – [Derivation](mdf_jr-feat-Derivation.html) – [Gender](mdf_jr-feat-Gender.html) – [Mood](mdf_jr-feat-Mood.html) – [NameType](mdf_jr-feat-NameType.html) – [NounType](mdf_jr-feat-NounType.html) – [Number](mdf_jr-feat-Number.html) – [Number[obj]](mdf_jr-feat-Number-obj.html) – [Number[psor]](mdf_jr-feat-Number-psor.html) – [Number[subj]](mdf_jr-feat-Number-subj.html) – [NumForm](mdf_jr-feat-NumForm.html) – [NumType](mdf_jr-feat-NumType.html) – [Person](mdf_jr-feat-Person.html) – [Person[obj]](mdf_jr-feat-Person-obj.html) – [Person[psor]](mdf_jr-feat-Person-psor.html) – [Person[subj]](mdf_jr-feat-Person-subj.html) – [Polarity](mdf_jr-feat-Polarity.html) – [PronType](mdf_jr-feat-PronType.html) – [Reflex](mdf_jr-feat-Reflex.html) – [Style](mdf_jr-feat-Style.html) – [Tense](mdf_jr-feat-Tense.html) – [Typo](mdf_jr-feat-Typo.html) – [Valency](mdf_jr-feat-Valency.html) – [Variant](mdf_jr-feat-Variant.html) – [VerbForm](mdf_jr-feat-VerbForm.html) – [VerbType](mdf_jr-feat-VerbType.html)

## Relations

[acl](mdf_jr-dep-acl.html) – [acl:relcl](mdf_jr-dep-acl-relcl.html) – [advcl](mdf_jr-dep-advcl.html) – [advcl:cau](mdf_jr-dep-advcl-cau.html) – [advcl:tcl](mdf_jr-dep-advcl-tcl.html) – [advmod](mdf_jr-dep-advmod.html) – [advmod:cau](mdf_jr-dep-advmod-cau.html) – [advmod:deg](mdf_jr-dep-advmod-deg.html) – [advmod:eval](mdf_jr-dep-advmod-eval.html) – [advmod:foc](mdf_jr-dep-advmod-foc.html) – [advmod:freq](mdf_jr-dep-advmod-freq.html) – [advmod:lfrom](mdf_jr-dep-advmod-lfrom.html) – [advmod:lmod](mdf_jr-dep-advmod-lmod.html) – [advmod:lto](mdf_jr-dep-advmod-lto.html) – [advmod:mmod](mdf_jr-dep-advmod-mmod.html) – [advmod:tmod](mdf_jr-dep-advmod-tmod.html) – [amod](mdf_jr-dep-amod.html) – [appos](mdf_jr-dep-appos.html) – [aux](mdf_jr-dep-aux.html) – [aux:cnd](mdf_jr-dep-aux-cnd.html) – [aux:nec](mdf_jr-dep-aux-nec.html) – [aux:neg](mdf_jr-dep-aux-neg.html) – [aux:opt](mdf_jr-dep-aux-opt.html) – [aux:q](mdf_jr-dep-aux-q.html) – [case](mdf_jr-dep-case.html) – [cc](mdf_jr-dep-cc.html) – [cc:preconj](mdf_jr-dep-cc-preconj.html) – [ccomp](mdf_jr-dep-ccomp.html) – [compound](mdf_jr-dep-compound.html) – [conj](mdf_jr-dep-conj.html) – [cop](mdf_jr-dep-cop.html) – [csubj](mdf_jr-dep-csubj.html) – [csubj:cop](mdf_jr-dep-csubj-cop.html) – [dep](mdf_jr-dep-dep.html) – [det](mdf_jr-dep-det.html) – [discourse](mdf_jr-dep-discourse.html) – [dislocated](mdf_jr-dep-dislocated.html) – [expl](mdf_jr-dep-expl.html) – [fixed](mdf_jr-dep-fixed.html) – [flat](mdf_jr-dep-flat.html) – [flat:name](mdf_jr-dep-flat-name.html) – [list](mdf_jr-dep-list.html) – [mark](mdf_jr-dep-mark.html) – [nmod](mdf_jr-dep-nmod.html) – [nmod:appos](mdf_jr-dep-nmod-appos.html) – [nmod:bahuv](mdf_jr-dep-nmod-bahuv.html) – [nmod:comp](mdf_jr-dep-nmod-comp.html) – [nmod:lmod](mdf_jr-dep-nmod-lmod.html) – [nmod:poss](mdf_jr-dep-nmod-poss.html) – [nmod:tmod](mdf_jr-dep-nmod-tmod.html) – [nsubj](mdf_jr-dep-nsubj.html) – [nsubj:cop](mdf_jr-dep-nsubj-cop.html) – [nsubj:pass](mdf_jr-dep-nsubj-pass.html) – [nummod](mdf_jr-dep-nummod.html) – [obj](mdf_jr-dep-obj.html) – [obl](mdf_jr-dep-obl.html) – [obl:agent](mdf_jr-dep-obl-agent.html) – [obl:cau](mdf_jr-dep-obl-cau.html) – [obl:comp](mdf_jr-dep-obl-comp.html) – [obl:freq](mdf_jr-dep-obl-freq.html) – [obl:inst](mdf_jr-dep-obl-inst.html) – [obl:lfrom](mdf_jr-dep-obl-lfrom.html) – [obl:lmod](mdf_jr-dep-obl-lmod.html) – [obl:lmp](mdf_jr-dep-obl-lmp.html) – [obl:lto](mdf_jr-dep-obl-lto.html) – [obl:tmod](mdf_jr-dep-obl-tmod.html) – [orphan](mdf_jr-dep-orphan.html) – [parataxis](mdf_jr-dep-parataxis.html) – [punct](mdf_jr-dep-punct.html) – [root](mdf_jr-dep-root.html) – [vocative](mdf_jr-dep-vocative.html) – [xcomp](mdf_jr-dep-xcomp.html)

<h2>Tokenization and Word Segmentation</h2>


<ul>
<li>This corpus contains 342 sentences, 3175 tokens and 3181 syntactic words.</li>
</ul>

<ul>
<li>This corpus contains 594 tokens (19%) that are not followed by a space.</li>
</ul>

<ul>
<li>This corpus does not contain words with spaces.</li>
</ul>

<ul>
<li>This corpus contains 32 types of words that contain both letters and punctuation. Examples: кати-коста, кодама-кодама, кой-кие, кой-кона, Алда-баба, Васток-васток, И., Кой-кинди, Коса-бди, Н., Панчк-ка, Пилсесь-лаксесь, кати-мезе, кодама-бъди, кядьта-пильгта, лиендихть-тиихть, лийфнесамазь-тисамазь, мезе-бди, мезень-бъди, обедамста-ужнамста, однек-сиренек, ризфсь-пичефкссь, саднек-мезнек, тиеда-арада, трнаты-вачкаты, тядяфтома-аляфтома, тяшнесь-нарнесь, фкя-фкянь, шталезе-урядалезе, эряй-ащи, эрямань-ащемань, ётай-потай</li>
</ul>

<ul>
<li>This corpus contains 3 multi-word tokens. On average, one multi-word token consists of 3.00 syntactic words.</li>
<li>There are 3 types of multi-word tokens. Examples: ласькозь-ласькихть, эрят-ащат, юмай-арай.</li>
</ul>

<h2>Morphology</h2>

<h3>Tags</h3>

<ul>
<li>This corpus uses 16 UPOS tags out of 17 possible: <a>ADJ</a>, <a>ADP</a>, <a>ADV</a>, <a>AUX</a>, <a>CCONJ</a>, <a>DET</a>, <a>INTJ</a>, <a>NOUN</a>, <a>NUM</a>, <a>PART</a>, <a>PRON</a>, <a>PROPN</a>, <a>PUNCT</a>, <a>SCONJ</a>, <a>VERB</a>, <a>X</a></li>
<li>This corpus does not use the following tags: SYM</li>
</ul>

<ul>
<li>This corpus contains 9 word types tagged as particles (PART): вдь, въдь, дяряй, нльне, нльня, сяда, улема, хоть, шять</li>
</ul>

<ul>
<li>This corpus contains 24 lemmas tagged as pronouns (PRON): иля, кати-мезе, кивок, кие, кой-кие, кой-кона, кона, лия, мезе, мезе-бди, мезевок, мон, монць, ня, сембе, сон, сонць, ся, сяка, тон, тона, тонць, тя, фкя-фкя</li>
</ul>

<ul>
<li>This corpus contains 14 lemmas tagged as determiners (DET): иля, кодама-бди, кой-кона, лама, лия, мзяра, ня, сембе, сняра, ся, сяка, тя, эрь, эсь</li>
</ul>

<ul>
<li>Out of the above, 8 lemmas occurred sometimes as PRON and sometimes as DET: иля, кой-кона, лия, ня, сембе, ся, сяка, тя</li>
</ul>

<ul>
<li>This corpus contains 9 lemmas tagged as auxiliaries (AUX): аф, аш, ба, катк, ли, савомс, сашендовомс, улемс, эрявомс</li>
</ul>

<ul>
<li>Out of the above, 2 lemmas occurred sometimes as AUX and sometimes as VERB: савомс, эрявомс</li>
</ul>

<ul>
<li>There are 5 <a href="../feat/VerbForm.html">(de)verbal forms:</a></li>
</ul>

<ul>
  <li>Conv
  <ul>
    <li>VERB: ласькозь, ётазь, Нолдазь, Тумстост, дивандазь, завтракамста, кенордазь, мадомста, обедамста-ужнамста, палозь</li>
  </ul>
  </li>
</ul>

<ul>
  <li>Conv,Part
  <ul>
    <li>AUX: апак</li>
  </ul>
  </li>
</ul>

<ul>
  <li>Inf
  <ul>
    <li>VERB: куцема, работама, тиемс, тонафтомс, арамс, ваномс, ванфтомс, васетькшнемс, венцямс, корхнемс</li>
  </ul>
  </li>
</ul>

<ul>
  <li>Part
  <ul>
    <li>VERB: анеляф, ацафоль, ащи, иретьфти, лиенди, максф, маскировандафт, моли, путфт, ранендаф</li>
  </ul>
  </li>
</ul>

<ul>
  <li>Vnoun
  <ul>
    <li>VERB: Авардемать, апрякама, ардомась, варьхмодема, видемда, кенярдема, ляцендемат, муськома, работаманкса, работамась</li>
  </ul>
  </li>
</ul>

<h3>Nominal Features</h3>


<ul>
  <li><a>Gender</a></li>
</ul>

<ul>
  <li>Fem
    <ul>
      <li>PROPN: Васильевна, Николаевнань</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Masc
    <ul>
      <li>PROPN: Вельдинонь, Голенков, Девинонь, Девятаев, Злобинонь, Келаськин, Кокоревонь, Кукушкинць, Пивкин, Покрышкинонь</li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>Animacy</a></li>
</ul>

<ul>
  <li>Hum
    <ul>
      <li>NOUN: тядяц</li>
      <li>PROPN: Васильевна, Вельдинонь, Голенков, Девинонь, Девятаев, Елена, Злобинонь, Келаськин, Кокоревонь, Кукушкинць</li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>Number</a></li>
</ul>

<ul>
  <li>Plur
    <ul>
      <li>ADJ: мазыхть, лямбот, малат, пяндрат</li>
      <li>DET: ня</li>
      <li>NOUN: ломаттне, ломатть, стирнятне, валхнень, гулянятнень, досканят, жаворонкатне, кизотнень, коволнятнень, сельмонень</li>
      <li>NUM: кемотть</li>
      <li>PRON: синь, минь, тейст, Лиятнень, конат, сятка, теест, тейнть, тинь, эсезост</li>
      <li>VERB: Лядыхне, кельгихть, ляцендемат, маскировандафт, путфт, шапфт, шнакшнематне</li>
      <li>VERB-Part: маскировандафт, путфт, шапфт</li>
      <li>VERB-Vnoun: ляцендемат, шнакшнематне</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Plur,Sing
    <ul>
      <li>ADJ: Ёмластокиге, Немойкс, аноконди, оцюняснон, пародонга</li>
      <li>DET: ламос</li>
      <li>NOUN: лангс, вирьса, кудса, лангса, ярмакса, Марянь, Саввань, Тишкань, атянь, больницяса</li>
      <li>NUM: Кемоньшка, кеветиешка, нильгемоньшка</li>
      <li>PRON: сембонь, конань, Кой-кинди, Конашка, Мезень, илянь, кинди, киньге, мезень-бъди, мезьса</li>
      <li>PROPN: Архипонь, Ванянди, Вельдинонь, Веряскинонди, Девинонь, Злобинонь, Кокоревонь, Николаевнань, Парижса, Петянь</li>
      <li>VERB-Vnoun: видемда, работаманкса, саманьконь, самозост, сяськоманкса, тумозонза, тушендомаснон, ужнамда, эрямань-ащемань</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Sing
    <ul>
      <li>ADJ: оцю, акша, козя, од, пара, сенем, тяфтама, васенце, лямбе, мазы</li>
      <li>DET: лама, эрь, Тя, сембе, ся, иля, кодама-бъди, кой-кона, лия, эсь</li>
      <li>NOUN: ава, шись, Тишка, цёранц, шамац, шиня, визькс, карденя, ланга, мялец</li>
      <li>NUM: фкя, кафта, кафцьке, колма, 225, 7, колмоцьке, комсь, ниле</li>
      <li>PRON: сон, сонь, мон, тя, тейнза, монь, тон, кие, кона, ся</li>
      <li>PROPN: Петя, Марья, Алда-баба, Анна, Браун, Василь, Васильевич, Васильевна, Васясь, Вельматов</li>
      <li>VERB: Авардемать, анеляф, апрякама, ардомась, варьхмодема, кенярдема, максф, муськома, работамась, саманцты</li>
      <li>VERB-Part: анеляф, максф, содафоль, тиф, эйндаф</li>
      <li>VERB-Vnoun: Авардемать, апрякама, ардомась, варьхмодема, кенярдема, муськома, работамась, саманцты, сувамац, тиемацка</li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>Case</a></li>
</ul>

<ul>
  <li>Abe
    <ul>
      <li>NOUN: лемфтома, перилафтома, эрьгяфтома</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Abl
    <ul>
      <li>ADJ: пародонга</li>
      <li>ADP: эзда, фталда, ширде, эздонк, эздост</li>
      <li>ADV: вярде</li>
      <li>NOUN: ломаньда, ширде, Аннада, алядот, вайгяльда, врьгазда, занятияда, иможда, класста, книгада</li>
      <li>PRON: Тяда, мондедон, сембода</li>
      <li>VERB-Inf: валдашкодомда, ванфтомода, видемда, корхтамда, крфамда, тиемда, шашнемда</li>
      <li>VERB-Vnoun: видемда, ужнамда</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Cau
    <ul>
      <li>ADP: инкса</li>
      <li>ADV: тянкса</li>
      <li>NOUN: лезксонкса</li>
      <li>VERB-Vnoun: работаманкса, сяськоманкса</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Cmp
    <ul>
      <li>ADP: эшка</li>
      <li>NOUN: пялешка, сурбряшка</li>
      <li>NUM: Кемоньшка, кеветиешка, нильгемоньшка</li>
      <li>PRON: Конашка</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Com
    <ul>
      <li>NOUN: куднек, саднек-мезнек, ульцянек</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Dat
    <ul>
      <li>ADJ: аноконди</li>
      <li>NOUN: Алязтиге, Дарюняти, Кепотьксонди, Луканди, Маринкати, Цёранянди, Ялгати, кизоти, классти, книгати</li>
      <li>PRON: тейнза, Тейне, теень, тейст, Кой-кинди, Мондейне, Сондеенза, Сондейнза, кинди, теест</li>
      <li>PROPN: Ванянди, Веряскинонди</li>
      <li>VERB-Vnoun: саманцты, цяпамати</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Ela
    <ul>
      <li>ADJ: Ёмластокиге</li>
      <li>ADP: пингста, ваксста</li>
      <li>ADV: тоста, кати-коста, курокста, эста</li>
      <li>NOUN: велеста, кудста, онцтон, пингста, пингстонза, ёткста, Москуста, библиотекста, вастстонза, губернияста</li>
      <li>VERB-Conv: Тумстост, завтракамста, мадомста, обедамста-ужнамста</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Gen
    <ul>
      <li>ADJ: омбоцеть, Передовойть, главнайть, оцюняснон</li>
      <li>ADV: кафтонь</li>
      <li>NOUN: цёранц, очконять, пингть, шить, Лугать, Марянь, Саввань, Тишкань, авать, атянь</li>
      <li>PRON: сонь, сембонь, монь, синь, конань, минь, тонь, тянь, Лиятнень, Мезень</li>
      <li>PROPN: Архипонь, Вельдинонь, Девинонь, Злобинонь, Кокоревонь, Николаевнань, Петянь, Покрышкинонь, Родькинонь, Тугановонь</li>
      <li>VERB-Vnoun: Авардемать, саманьконь, тушендомаснон, эводемать, эрямань-ащемань</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Ill
    <ul>
      <li>ADP: лангс, ваксс, коряс, малас, Корязост, корязон, корязонк, корязонт, эзонза</li>
      <li>ADV: Мес, тяза</li>
      <li>DET: ламос</li>
      <li>NOUN: лангс, вастс, каршес, лангозонза, вастозонза, воляс, кудрядс, кучкас, лафтубрязонза, мялезостка</li>
      <li>PRON: эсезост</li>
      <li>VERB-Vnoun: самозост, тумозонза</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Ine
    <ul>
      <li>ADP: ваксса, эса, лангса, каршесонк, эсонза, эсост</li>
      <li>ADV: тоса, тяса, маласа, Коса-бди, косовок, пяшксетольхть</li>
      <li>NOUN: вирьса, кудса, лангса, ярмакса, больницяса, вайгяльса, кизоса, мяльса, тюсса, Заводса</li>
      <li>PRON: мезьса</li>
      <li>PROPN: Парижса</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Lat
    <ul>
      <li>ADP: алу, шири</li>
      <li>ADV: вяри, алу, ичкози, оду, фталу</li>
      <li>NOUN: инголи, куду, ульцяв, шири, школав, Колхозу, Крыму, Мазы, Маманяв, Ошу</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Loc
    <ul>
      <li>ADP: ала, Инголенк, Инголест</li>
      <li>ADV: ичкозе, инголе, перьфпяле</li>
      <li>AUX: аш</li>
      <li>VERB-Inf: куцема, работама, шурокстомома, азонкшнема, ванондома, ватксема, вятемонза, лувома, морама, мярьгома</li>
      <li>VERB-Vnoun: апрякама</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Nom
    <ul>
      <li>ADJ: оцю, акша, козя, од, пара, сенем, тяфтама, васенце, лямбе, мазы</li>
      <li>DET: лама, эрь, Тя, сембе, ся, иля, кодама-бъди, кой-кона, лия, эсь</li>
      <li>NOUN: ломаттне, ава, шись, Тишка, шамац, визькс, карденя, ланга, ломатть, мялец</li>
      <li>NUM: фкя, кафта, кафцьке, колма, 225, 7, кемотть, колмоцьке, комсь, ниле</li>
      <li>PRON: сон, мон, тя, синь, тон, кие, кона, минь, ся, кивок</li>
      <li>PROPN: Петя, Марья, Алда-баба, Анна, Браун, Василь, Васильевич, Васильевна, Васясь, Вельматов</li>
      <li>VERB: Лядыхне, анеляф, ардомась, варьхмодема, кельгихть, кенярдема, ляцендемат, максф, маскировандафт, муськома</li>
      <li>VERB-Part: анеляф, максф, маскировандафт, путфт, содафоль, тиф, шапфт, эйндаф</li>
      <li>VERB-Vnoun: ардомась, варьхмодема, кенярдема, ляцендемат, муськома, работамась, сувамац, тиемацка, шнакшнематне</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Prl
    <ul>
      <li>ADP: мельгя, эзга, мельге</li>
      <li>ADV: перьфпяльге, Шобдава</li>
      <li>NOUN: вальмава, морява, пандонява, вастоваст, велькска, вельхкска, вирьгя, вярьгя, ингольгя, киге</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Tem
    <ul>
      <li>NOUN: шиня</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Tra
    <ul>
      <li>ADJ: Немойкс</li>
      <li>ADP: ланга</li>
      <li>NOUN: сторожкс, геройкс, июленнекс, кизоннекс, комендантокс, крайкс, лётчикокс, лётчикокска, мокшекс, пинекс</li>
    </ul>
  </li>
</ul>


<ul>
  <li><a>Definite</a></li>
</ul>

<ul>
  <li>Def
    <ul>
      <li>ADJ: омбоцеть, Передовойть, главнайть</li>
      <li>NOUN: ломаттне, шись, очконять, пингть, стирнятне, шить, Вармась, Лугать, Маринкась, Самолётсь</li>
      <li>PRON: Лиятнень, Сембось</li>
      <li>PROPN: Васясь, Игуазсь, Кукушкинць, Маринкась, Млай, Парижсь, Тугановть, Франциять, Цямкаерясь</li>
      <li>VERB: Авардемать, Лядыхне, ардомась, работамась, цяпамати, шнакшнематне, эводемать, ётафтысь</li>
      <li>VERB-Vnoun: Авардемать, ардомась, работамась, цяпамати, шнакшнематне, эводемать</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Ind
    <ul>
      <li>ADJ: оцю, акша, козя, од, пара, сенем, тяфтама, васенце, лямбе, мазы</li>
      <li>ADV: кати-коста, Коса-бди, кафтонь, косовок</li>
      <li>DET: лама, эрь, сембе, кодама-бъди, кой-кона, ламос, лия, эсь</li>
      <li>NOUN: лангс, ава, шиня, Тишка, визькс, вирьса, карденя, кудса, ланга, лангса</li>
      <li>NUM: фкя, кафта, кафцьке, колма, кеветиешка, кемотть, комсь, ниле, нильгемоньшка</li>
      <li>PRON: тя, сембонь, кона, ся, конань, сяка, Конашка, Сянь, Тяда, илянь</li>
      <li>PROPN: Петя, Марья, Алда-баба, Анна, Архипонь, Браун, Ванянди, Василь, Васильевич, Васильевна</li>
      <li>VERB: анеляф, апрякама, варьхмодема, видемда, кельгихть, кенярдема, ляцендемат, максф, маскировандафт, муськома</li>
      <li>VERB-Part: анеляф, максф, маскировандафт, путфт, содафоль, тиф, шапфт, эйндаф</li>
      <li>VERB-Vnoun: апрякама, варьхмодема, видемда, кенярдема, ляцендемат, муськома, работаманкса, сяськоманкса, ужнамда, эрямань-ащемань</li>
    </ul>
  </li>
</ul>

<h3>Degree and Polarity</h3>


<ul>
  <li><a>Degree</a></li>
</ul>

<ul>
  <li>Cmp
    <ul>
      <li>PART: сяда</li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>Polarity</a></li>
</ul>

<ul>
  <li>Neg
    <ul>
      <li>AUX: аф, ашезь, ашень, апак, афоль, аш, изь, Афи, афолеть, ашезе</li>
      <li>AUX-Conv,Part: апак</li>
      <li>INTJ: Аф</li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>Variant</a></li>
</ul>

<ul>
  <li>Long
    <ul>
      <li>PRON: Мондейне, Сондеенза, Сондейнза</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Short
    <ul>
      <li>PRON: тейнза, Тейне, теень, тейст, теест, тейнть, эсезост</li>
    </ul>
  </li>
</ul>

<h3>Verbal Features</h3>


<ul>
  <li><a>Aspect</a></li>
</ul>

<ul>
  <li>Hab
    <ul>
      <li>VERB: каннель, лезнель</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Perf
    <ul>
      <li>VERB-Part: анеляф, максф, содафоль, таргозьфтольхть, тиф, шапфт, эйндаф</li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>Mood</a></li>
</ul>

<ul>
  <li>Cnd
    <ul>
      <li>AUX: ба, савондяряй</li>
      <li>VERB: Касондярян, матодовондяряй, кадондярясак, кизефтендярясамазь, кирдендярясы, лездондярятада, лядондяряй, мярьгондяряй, няендяряйхть, путондяряй</li>
    </ul>
  </li>
</ul>

<ul>
  <li>CndSub
    <ul>
      <li>AUX: Улендяряль</li>
      <li>VERB: Путондяряльхть, Сандяряль, лисендяряль</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Des
    <ul>
      <li>VERB: Молелексолеть</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Imp
    <ul>
      <li>VERB: архт, ярхцада, тиеда-арада, тик</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Ind
    <ul>
      <li>AUX: ульсь, ашезь, ашень, изь, ульсть, эрявсь, Эрявихть, ашезе, ашельхть, ашесть</li>
      <li>VERB: марявсь, варжакстсь, кармась, рамась, сась, тусь, арась, кармасть, касан, лиссь</li>
    </ul>
  </li>
</ul>

<ul>
  <li>NegCndSub
    <ul>
      <li>AUX: улефтяряль</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Opt
    <ul>
      <li>AUX: катк, савоза</li>
      <li>VERB: кирдест, ванозазе</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Prec
    <ul>
      <li>VERB: Варжалите, Панчк-ка, варжака</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Sub
    <ul>
      <li>AUX: афоль, афолеть, улелеть</li>
      <li>VERB: Рамаль, арьселень, келептелине, ладяль, ладяльхть, лиелень, лихтельхть, лоткаль, нолдалезе, озалень</li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>Tense</a></li>
</ul>

<ul>
  <li>Past
    <ul>
      <li>ADJ: акшель, маниель, пароль, сятяволь, цебярель, эреколь, якстерель</li>
      <li>ADV: пяшксетольхть</li>
      <li>AUX: ульсь, ашезь, ашень, изь, ульсть, эрявсь, ашезе, ашель, ашельхть, ашесть</li>
      <li>NOUN: мялецоль, порядкасоль</li>
      <li>VERB: марявсь, варжакстсь, кармась, рамась, сась, тусь, арась, кармасть, лиссь, маштсь</li>
      <li>VERB-Part: ацафоль, содафоль, таргозьфтольхть</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Pres
    <ul>
      <li>AUX: аш, Эрявихть, сашендови, ули, улян, эряви</li>
      <li>NOUN: прясан</li>
      <li>VERB: ащи, касан, моли, Арьсян, ванан, корхтай, корхтан, лиси, мярьгат, пели</li>
      <li>VERB-Part: ащи, иретьфти, лиенди, моли, сай, ётай-потай</li>
    </ul>
  </li>
</ul>



<h3>Pronouns, Determiners, Quantifiers</h3>


<ul>
  <li><a>PronType</a></li>
</ul>

<ul>
  <li>Dem
    <ul>
      <li>ADJ: тяфтама</li>
      <li>DET: Тя, ся, ня</li>
      <li>PRON: тя, ся, тянь, Сянь, Тяда, сятка, тона</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Ind
    <ul>
      <li>ADV: коданга, козонга</li>
      <li>DET: кодама-бъди</li>
      <li>PRON: кивок, кой-кие, мезевок, Кой-кинди, кати-мезе, киньге, кой-кона, мезе-бди, мезень-бъди</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Int
    <ul>
      <li>ADJ: кодама</li>
      <li>ADV: Мес</li>
      <li>DET: Мъзяра</li>
      <li>PRON: кие, мезе, Мезень, кинди, мезьса</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Prs
    <ul>
      <li>PRON: сон, сонь, мон, синь, минь, тейнза, монь, тон, Тейне, монць</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Rcp
    <ul>
      <li>PRON: фкя-фкянь</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Rel
    <ul>
      <li>PRON: кона, конань, конат</li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>NumType</a></li>
</ul>

<ul>
  <li>Card
    <ul>
      <li>ADV: кафтонь</li>
      <li>NUM: фкя, кафта, вете, колма, кеветиешка, кемотть, комсь, ниле, нильгемоньшка</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Coll
    <ul>
      <li>NUM: кафцьке, колмоцьке</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Dist
    <ul>
      <li>ADJ: кодама-кодама</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Mult
    <ul>
      <li>ADV: весть</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Ord
    <ul>
      <li>ADJ: васенце, омбоце, омбоцеть, Нильгемонце, кемонце, колмоце, сизьгемонце</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Sets
    <ul>
      <li>NUM: кафонц</li>
    </ul>
  </li>
</ul>


<ul>
  <li><a>Reflex</a></li>
</ul>

<ul>
  <li>Yes
    <ul>
      <li>DET: эсь</li>
      <li>PRON: монць, сонць, сонцьке, тонцьке, эсезост</li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>Person</a></li>
</ul>

<ul>
  <li>1
    <ul>
      <li>PRON: мон, минь, монь, Тейне, монць, теень, Мондейне, мондедон, моньге</li>
    </ul>
  </li>
</ul>

<ul>
  <li>2
    <ul>
      <li>PRON: тон, тонь, тейнть, тинь, тонга, тонцьке</li>
    </ul>
  </li>
</ul>

<ul>
  <li>3
    <ul>
      <li>PRON: сон, сонь, синь, тейнза, сонць, тейст, Сондеенза, Сондейнза, сонцьке, теест</li>
    </ul>
  </li>
</ul>



<ul>
  <li><a>Number[psor]</a></li>
</ul>

<ul>
  <li>Plur
    <ul>
      <li>ADJ: оцюняснон</li>
      <li>ADP: корязост, Инголенк, Инголест, каршесонк, корязонк, корязонт, эздонк, эздост, эсост</li>
      <li>NOUN: сельмосна, бабасновок, ваймоньконь, валсна, вастоваст, веленьконь, велесонк, дружбаснон, кисетснон, кудсна</li>
      <li>VERB-Conv: Тумстост</li>
      <li>VERB-Vnoun: саманьконь, самозост, тушендомаснон</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Sing
    <ul>
      <li>ADJ: Нильгемонце</li>
      <li>ADP: мархтонза, корязон, перьфканза, эзонза, эсонза</li>
      <li>NOUN: цёранц, шамац, мялец, Алязе, брадозень, вазенц, лангозонза, мирденц, мялецоль, онцтон</li>
      <li>PROPN: Мишазе</li>
      <li>VERB-Inf: вятемонза</li>
      <li>VERB-Vnoun: саманцты, сувамац, тиемацка, тумозонза</li>
    </ul>
  </li>
</ul>

<h3>Other Features</h3>


<ul>
  <li><a>Abbr</a>
    <ul>
      <li>Yes
        <ul>
          <li>NOUN: И., Н.</li>
        </ul>
      </li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>AdpType</a>
    <ul>
      <li>Post
        <ul>
          <li>ADP: пачк, сюнеда, мельге, эшка</li>
        </ul>
      </li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>AdvType</a>
    <ul>
      <li>Deg
        <ul>
          <li>ADV: пяк, сяда, сяшкава, конашкава, тяшкава, ёфcи, ёфси</li>
        </ul>
      </li>
      <li>Loc
        <ul>
          <li>ADV: тов, алу, тяза</li>
        </ul>
      </li>
      <li>Man
        <ul>
          <li>ADV: цебярьста, мазыста, весяласта, павазуста, хитрайста, цебярняста</li>
        </ul>
      </li>
      <li>Tim
        <ul>
          <li>ADV: нинге, ни, эста, тага, рана, Кизонда, илять, шобдава, обедшкада, сёксенда</li>
          <li>NOUN: илять</li>
          <li>SCONJ: мъзярда</li>
        </ul>
      </li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>Clitic</a>
    <ul>
      <li>AddGA
        <ul>
          <li>ADV: вестенге</li>
          <li>NOUN: Алязтиге, ведняське, лётчикокска, мялезостка, школавга</li>
          <li>PRON: моньге, сонцьке, сятка, тонга, тонцьке</li>
          <li>VERB-Vnoun: тиемацка</li>
        </ul>
      </li>
      <li>AddKige
        <ul>
          <li>ADJ: Ёмластокиге</li>
          <li>ADV: ранакиге</li>
        </ul>
      </li>
      <li>AddNgA
        <ul>
          <li>ADJ: пародонга</li>
          <li>ADV: сядонга</li>
        </ul>
      </li>
      <li>AddVok
        <ul>
          <li>NOUN: бабасновок, самолётовок</li>
          <li>VERB: поладывок</li>
        </ul>
      </li>
      <li>I
        <ul>
          <li>ADV: Сясы</li>
          <li>AUX: Афи</li>
          <li>SCONJ: Сясы</li>
        </ul>
      </li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>Connegative</a>
    <ul>
      <li>Yes
        <ul>
          <li>VERB: матодов, ана, ваймак, карма, лотксе, макса, няенде, пице, сёлгов, абонда</li>
        </ul>
      </li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>Derivation</a>
    <ul>
      <li>Dimin
        <ul>
          <li>ADV: саворне</li>
          <li>NOUN: карденя, очконять, досканят, коволнятнень, пацяняц, стирнятне, Луганятне, Макарня, Маманяв, Очконясь</li>
        </ul>
      </li>
      <li>F
        <ul>
          <li>VERB-Part: анеляф, ацафоль, максф, маскировандафт, путфт, ранендаф, содафоль, таргозьфтольхть, тиф, шавф</li>
        </ul>
      </li>
      <li>GenAttr
        <ul>
          <li>ADJ: озадонь</li>
        </ul>
      </li>
      <li>NomAg
        <ul>
          <li>VERB: Лядыхне, кельгихть, ётафтысь</li>
        </ul>
      </li>
      <li>Ozj
        <ul>
          <li>VERB-Conv: ётазь, Нолдазь, дивандазь, кенордазь, палозь, путозь, учсезь</li>
        </ul>
      </li>
      <li>Poss
        <ul>
          <li>NOUN: зрняннеть, июленнекс, кизоннекс, сияннеть</li>
        </ul>
      </li>
      <li>Wife
        <ul>
          <li>PROPN: Цямкаерясь</li>
        </ul>
      </li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>NameType</a>
    <ul>
      <li>Geo
        <ul>
          <li>PROPN: Игуазсь, Парижса, Парижсь, Франциять</li>
        </ul>
      </li>
      <li>Giv
        <ul>
          <li>PROPN: Петя, Марья, Алда-баба, Анна, Архипонь, Ванянди, Василь, Васясь, Володя, Джейн</li>
        </ul>
      </li>
      <li>Pat
        <ul>
          <li>PROPN: Васильевич, Васильевна, Михайлович</li>
        </ul>
      </li>
      <li>Sur
        <ul>
          <li>NOUN: Канайкинонь, Ленинонь, Мазы, Малининонь, Тумкин</li>
          <li>PROPN: Браун, Вельдинонь, Вельматов, Веряскинонди, Голенков, Девинонь, Девятаев, Злобинонь, Каргалов, Келаськин</li>
        </ul>
      </li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>NounType</a>
    <ul>
      <li>Relat
        <ul>
          <li>ADP: лангс, ланга</li>
          <li>NOUN: лангс, ланга, лангса, каршес, лангозонза, шири, ёткста, Лангсонза, вельхкска, инголи</li>
        </ul>
      </li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>NumForm</a>
    <ul>
      <li>Digit
        <ul>
          <li>NUM: 225, 7</li>
        </ul>
      </li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>Number[obj]</a>
    <ul>
      <li>Plur
        <ul>
          <li>VERB: Лихтезь, азондозень, азондыне, аноклазень, вадердасыне, ванфнезь, васьфтьсамазь, венепнесайне, келептелине, крьвястезень</li>
        </ul>
      </li>
      <li>Plur,Sing
        <ul>
          <li>VERB: Кончайне</li>
        </ul>
      </li>
      <li>Sing
        <ul>
          <li>AUX: ашезе</li>
          <li>VERB: валхтозе, сявозе, сёрмадозе, Ладяйне, Няить, архтозе, валхтсамазь, ванозазе, вархцодезе, дивандафтомань</li>
        </ul>
      </li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>Number[subj]</a>
    <ul>
      <li>Plur
        <ul>
          <li>ADV: пяшксетольхть</li>
          <li>AUX: ульсть, Эрявихть, ашельхть, ашесть, исть, эрявсть</li>
          <li>VERB: кармасть, морасть, кирдест, лиссть, работасть, тисть, уендихть, эряйхть, ярхцада, Лихтезь</li>
          <li>VERB-Part: таргозьфтольхть</li>
        </ul>
      </li>
      <li>Sing
        <ul>
          <li>ADJ: акшель, маниель, пароль, сятяволь, цебярель, эреколь, якстерель</li>
          <li>AUX: ульсь, ашезь, ашень, афоль, аш, изь, эрявсь, Улендяряль, афолеть, ашезе</li>
          <li>NOUN: мялецоль, порядкасоль, прясан</li>
          <li>VERB: марявсь, варжакстсь, кармась, рамась, сась, тусь, арась, касан, лиссь, маштсь</li>
          <li>VERB-Part: ацафоль, содафоль</li>
        </ul>
      </li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>Person[obj]</a>
    <ul>
      <li>1
        <ul>
          <li>VERB: валхтсамазь, васьфтьсамазь, дивандафтомань, кизефтендярясамазь, лийфнесамазь-тисамазь, няйсамасть, пиксомань, шачфтомань</li>
        </ul>
      </li>
      <li>2
        <ul>
          <li>VERB: стардондярятанза</li>
        </ul>
      </li>
      <li>3
        <ul>
          <li>AUX: ашезе</li>
          <li>VERB: валхтозе, сявозе, сёрмадозе, Кончайне, Ладяйне, Лихтезь, Няить, азондозень, азондыне, аноклазень</li>
        </ul>
      </li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>Person[psor]</a>
    <ul>
      <li>1
        <ul>
          <li>ADP: Инголенк, каршесонк, корязон, корязонк, эздонк</li>
          <li>NOUN: Алязе, брадозень, онцтон, сельмонень, Алязтиге, алязень, арьсеманень, атязе, ваймоньконь, векозень</li>
          <li>PROPN: Мишазе</li>
          <li>VERB-Vnoun: саманьконь</li>
        </ul>
      </li>
      <li>2
        <ul>
          <li>ADJ: Нильгемонце</li>
          <li>ADP: корязонт</li>
          <li>NOUN: алядот, кице, свадьбацень, сёрмаце, тевцень</li>
        </ul>
      </li>
      <li>3
        <ul>
          <li>ADJ: оцюняснон</li>
          <li>ADP: мархтонза, корязост, Инголест, перьфканза, эздост, эзонза, эсонза, эсост</li>
          <li>NOUN: цёранц, шамац, мялец, вазенц, лангозонза, мирденц, мялецоль, пацяняц, пингстонза, сельмосна</li>
          <li>VERB-Conv: Тумстост</li>
          <li>VERB-Inf: вятемонза</li>
          <li>VERB-Vnoun: саманцты, самозост, сувамац, тиемацка, тумозонза, тушендомаснон</li>
        </ul>
      </li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>Person[subj]</a>
    <ul>
      <li>1
        <ul>
          <li>AUX: ашень, улян</li>
          <li>NOUN: прясан</li>
          <li>VERB: касан, Арьсян, Касондярян, ванан, корхтан, сявонь, тунь, ёран, Арьсень, Варжакстонь</li>
        </ul>
      </li>
      <li>2
        <ul>
          <li>AUX: афолеть, улелеть</li>
          <li>VERB: архт, мярьгат, ярхцада, Варжалите, Молелексолеть, Няить, Панчк-ка, арьсят, ащат, ванат</li>
        </ul>
      </li>
      <li>3
        <ul>
          <li>ADJ: акшель, маниель, пароль, сятяволь, цебярель, эреколь, якстерель</li>
          <li>ADV: пяшксетольхть</li>
          <li>AUX: ульсь, ашезь, афоль, аш, изь, ульсть, эрявсь, Улендяряль, Эрявихть, ашезе</li>
          <li>NOUN: мялецоль, порядкасоль</li>
          <li>VERB: марявсь, варжакстсь, кармась, рамась, сась, тусь, арась, кармасть, лиссь, маштсь</li>
          <li>VERB-Part: ацафоль, содафоль, таргозьфтольхть</li>
        </ul>
      </li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>Style</a>
    <ul>
      <li>Ped
        <ul>
          <li>ADV: кържа, Мзярда</li>
          <li>DET: Мъзяра, кодама-бъди</li>
          <li>PART: въдь</li>
          <li>PRON: мезень-бъди</li>
          <li>SCONJ: къда, мъзярда</li>
        </ul>
      </li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>Typo</a>
    <ul>
      <li>Yes
        <ul>
          <li>NOUN: карденя, велькска, карденяв</li>
        </ul>
      </li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>Valency</a>
    <ul>
      <li>1
        <ul>
          <li>AUX: ульсь, эрявсь, Эрявихть, савоза, сашендови, улелеть, ульсть, улян, эрявсть</li>
          <li>VERB: касан, ащи, кенярдсь, корхтай, лездсь, лиссть, лиссь, марявсь, мольсь, няевсь</li>
          <li>VERB-Conv: дивандазь, кенордазь, палозь</li>
          <li>VERB-Inf: стямс, Валдашкодомс, валдашкодомда, лездомс, лиендемс, молемс, налхксемс, работама, шашнемда, якама</li>
          <li>VERB-Part: ащи, иретьфти, лиенди, маскировандафт, моли, ранендаф, сай</li>
          <li>VERB-Vnoun: ардомась, варьхмодема, кенярдема, самозост</li>
        </ul>
      </li>
      <li>2
        <ul>
          <li>VERB: Арьсян, варжакстсь, сявонь, ёран, Арьсень, Варжакстонь, Ладяйне, Лихтезь, Няить, Панчк-ка</li>
          <li>VERB-Conv: ётазь</li>
          <li>VERB-Inf: анцемс, ватксема, дивандафтомс, кадомс, косьфтамс, лувома, нежедемс, петемс, рисовандама, сявондемс</li>
          <li>VERB-Part: ацафоль, путфт, шавф</li>
          <li>VERB-Vnoun: муськома</li>
        </ul>
      </li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>VerbType</a>
    <ul>
      <li>Aux
        <ul>
          <li>AUX: аф, ашезь, аш, ба, изь, Афоль, афолеть, ашель, ашельхть, ашесть</li>
        </ul>
      </li>
    </ul>
  </li>
</ul>

<h2>Syntax</h2>

<h3>Auxiliary Verbs and Copula</h3>

<ul>
<li>This corpus uses 2 lemmas as copulas (<a>cop</a>). Examples: улемс, аш.</li>
</ul>

<ul>
<li>This corpus uses 3 lemmas as auxiliaries (<a>aux</a>). Examples: улемс, савомс, сашендовомс.</li>
</ul>

<h3>Core Arguments, Oblique Arguments and Adjuncts</h3>

Here we consider only relations between verbs (parent) and nouns or pronouns (child).
<ul>
  <li><a>nsubj</a>
    <ul>
      <li>VERB--NOUN (1)</li>
      <li>VERB--NOUN-Nom (155)</li>
      <li>VERB--NOUN-Nom-ADP(мархта) (1)</li>
      <li>VERB--PRON-Nom (65)</li>
      <li>VERB-Inf--NOUN-Nom (1)</li>
      <li>VERB-Part--NOUN-Nom (3)</li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>obj</a>
    <ul>
      <li>VERB--NOUN-Abl (1)</li>
      <li>VERB--NOUN-Ela (1)</li>
      <li>VERB--NOUN-Gen (54)</li>
      <li>VERB--NOUN-Gen-ADP(эшка) (1)</li>
      <li>VERB--NOUN-Ine (1)</li>
      <li>VERB--NOUN-Nom (48)</li>
      <li>VERB--PRON-Gen (7)</li>
      <li>VERB--PRON-Nom (1)</li>
      <li>VERB-Conv--NOUN-Gen (3)</li>
      <li>VERB-Inf--NOUN-Gen (11)</li>
      <li>VERB-Inf--NOUN-Nom (8)</li>
      <li>VERB-Inf--PRON-Gen (2)</li>
      <li>VERB-Inf--PRON-Nom (1)</li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>iobj</a>
    <ul>
    </ul>
  </li>
</ul>




<h3>Relations Overview</h3>

<ul>
<li>This corpus uses 39 relation subtypes: <a>acl:relcl</a>, <a>advcl:cau</a>, <a>advcl:tcl</a>, <a>advmod:cau</a>, <a>advmod:deg</a>, <a>advmod:eval</a>, <a>advmod:foc</a>, <a>advmod:freq</a>, <a>advmod:lfrom</a>, <a>advmod:lmod</a>, <a>advmod:lto</a>, <a>advmod:mmod</a>, <a>advmod:tmod</a>, <a>aux:cnd</a>, <a>aux:nec</a>, <a>aux:neg</a>, <a>aux:opt</a>, <a>aux:q</a>, <a>cc:preconj</a>, <a>csubj:cop</a>, <a>flat:name</a>, <a>nmod:appos</a>, <a>nmod:bahuv</a>, <a>nmod:comp</a>, <a>nmod:lmod</a>, <a>nmod:poss</a>, <a>nmod:tmod</a>, <a>nsubj:cop</a>, <a>nsubj:pass</a>, <a>obl:agent</a>, <a>obl:cau</a>, <a>obl:comp</a>, <a>obl:freq</a>, <a>obl:inst</a>, <a>obl:lfrom</a>, <a>obl:lmod</a>, <a>obl:lmp</a>, <a>obl:lto</a>, <a>obl:tmod</a></li>
<li>The following 4 relation types are not used in this corpus at all: <a>iobj</a>, <a>clf</a>, <a>goeswith</a>, <a>reparandum</a></li>
</ul>
