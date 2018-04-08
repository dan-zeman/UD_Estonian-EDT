# Summary

UD Estonian is a conversion of a subpart of Estonian Dependency Treebank (EDT), originally annotated in the Constraint Grammar (CG) annotation scheme, and consisting of genres of fiction, newspaper texts and scientific texts.
The treebank consists of 26,197 trees, 366,351 tokens.

# Introduction

The Estonian UD v2.2 treebank is based on the [Estonian Dependency Treebank] (https://github.com/EstSyntax/) (EDT), created at the University of Tartu. The treebank has been automatically converted and then manually reviewed and reannotated.

The treebank covers 3 different genres, namely newspaper texts, fiction and scientific texts:

* fiction (67,741 tokens, 5,522 sentences)

* newspapers (205,177 tokens, 14,470 sentences)

* scientific text (84,233 tokens, 4,928 sentences)

* Also, the subpart of Estonian part of HamleDT 3.0 treebank has been reannotated and included in the treebank; it contains 9,200 tokens.


# Acknowledgments

We wish to thank all of the contributors to the original EDT annotation effort, especially Eleri Aedmaa, Riin Kirt and Dage Särg.

We also thank developers of [udapi](http://udapi.github.io/) and [ud annotatrix](https://github.com/jonorthwash/ud-annotatrix) tools.

This work was financed by the [National Programme for Estonian Language Technology](https://www.keeletehnoloogia.ee/en?set_language=en) and Estonian Ministery of Education and Research (grant 20-56 IUT20-56 "Computational models for Estonian").

# References

* Kadri Muischnek, Kaili Müürisep, Tiina Puolakainen, Eleri Aedmaa, Riin Kirt, Dage Särg.  2014.
  [Estonian Dependency Treebank and its annotation scheme](http://tlt13.sfs.uni-tuebingen.de/tlt13-proceedings.pdf).
  In: *Proceedings of the 13th Workshop on Treebanks and Linguistic Theories (TLT13),*
  pp. 285–291, ISBN 978-3-9809183-9-8, Tübingen, Germany.

* Kadri Muischnek, Kaili Müürisep and Tiina Puolakainen 2016. Estonian Dependency Treebank: from Constraint Grammar tagset to Universal Dependencies. - Proceedings of LREC 2016.

* Kadri Muischnek and Kaili Müürisep. 2017. Estonian copular and existential constructions as an UD annotation problem. In Proceedings of the NoDaLiDa 2017 Workshop on Universal Dependencies (UDW 2017), pp. 79-85. 2017.

# Changelog

* UD v2.2: more data added to v2.1; fixed errors in v2.1 files; repository renamed from UD_Estonian to UD_Estonian-EDT.

* UD v2.1: manual reannotation of copula sentences, names and appositions; semiautomatic reannotation of pronouns and determiners and coordinated structures; automatic reannotation of nmod and obl functions.

* UD v2.0: manual reannotation of copula sentences, names and appositions; semiautomatic reannotation of pronouns and determiners and coordinated structures; automatic reannotation of nmod and obl functions.

* UD v1.2 contained Arborest, a much smaller and older VISL-style treebank. It has been re-annotated and added to EDT for UD v1.3.

=== Machine-readable metadata =================================================
Documentation status: stub
Data source: semi-automatic
Data available since: UD v1.2
License: CC BY-NC-SA 4.0
Includes text: yes
Genre: fiction news nonfiction
Lemmas: converted from manual
UPOS: converted from manual
XPOS: converted from manual
Features: converted from manual
Relations: converted from manual
Contributing: here
Contributors: Muischnek, Kadri; Müürisep, Kaili; Puolakainen, Tiina; Rääbis, Andriela
Contact: kadri.muischnek@ut.ee, kaili.muurisep@ut.ee
===============================================================================
