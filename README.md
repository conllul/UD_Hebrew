# UD_Hebrew

This repository contains the [CoNLL-UL formatted](http://conllul.github.io) morphological analysis of the [UD v2 Hebrew treebank](https://github.com/universaldependencies/UD_Hebrew).


The files were generated with [yap](https://github.com/habeanf/yap) with the following command line:

``./yap hebma -conllu <input file> -format ud -out <output file>``

Citation
-----------
If you make use of this data for research, we would appreciate the following citation:

"CoNLL-UL: Universal Morphological Lattices for Universal Dependency Parsing", Amir More, Özlem Çetinoğlu, Çağrı Çöltekin, Nizar Habash, Benoît Sagot, Djamé Seddah, Dima Taji, Reut Tsarfaty, Proceedings of LREC 2018, Japan.

HEBLEX, a Morphological Analyzer for Modern Hebrew in yap, relies on a slightly modified version of the BGU Lexicon. Please acknowledge and cite the work on the BGU Lexicon with this citation:
```
@inproceedings{adler06,
    Author = {Adler, Meni and Elhadad, Michael},
    Booktitle = {ACL},
    Crossref = {conf/acl/2006},
    Editor = {Calzolari, Nicoletta and Cardie, Claire and Isabelle, Pierre},
    Ee = {http://aclweb.org/anthology/P06-1084},
    Interhash = {6e302df82f4d7776cc487d5b8623d3db},
    Intrahash = {c7ac3ecfe40d039cd6c9ec855cb432db},
    Keywords = {dblp},
    Publisher = {The Association for Computer Linguistics},
    Timestamp = {2013-08-13T15:11:00.000+0200},
    Title = {An Unsupervised Morpheme-Based HMM for {H}ebrew Morphological
        Disambiguation},
    Url = {http://dblp.uni-trier.de/db/conf/acl/acl2006.html#AdlerE06},
    Year = 2006,
    Bdsk-Url-1 = {http://dblp.uni-trier.de/db/conf/acl/acl2006.html#AdlerE06}}
```
