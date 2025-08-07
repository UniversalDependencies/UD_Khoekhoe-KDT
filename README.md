# Summary

UD\_Khoekhoe-KDT is a Universal Dependencies (UD) treebank for the Khoekhoe language. The annotation was performed manually based on glosses. This treebank includes texts from various sources: fiction, grammar, and spoken conversation. The treebank contains **27k tokens**, distributed as follows:

- **Training set**: 15k tokens
- **Development set**: 2k tokens
- **Test set**: 10k tokens

# Introduction

The UD\_Khoekhoe-KDT treebank consists of various texts translated into Khoekhoe by native speakers, then glossed and annotated. The included texts are:

- **grammar\_Cairo**: 20 examples from the [Cairo Cicling Corpus](https://github.com/UniversalDependencies/cairo/blob/master/translations.txt))
- **grammar\_BivalTyp**: [BivalTyp](https\://www\.bivaltyp.info/languages/descriptions/Khoekhoe.html) dataset.
- **film\_Bridge**: Subtitles from *Bridge of Spies* (2015).
- **film\_Titanic**: A section of subtitles from *Titanic* (1997).
- **book\_Khomai**: Chapters from the school book *Khomai* (1971), with shuffled sentences.
- **conversation\_Windhoek5**: A recorded conversation between two friends, anonymized by shuffling sentences.

## Genre Classification

- **Fiction**: Sentence IDs start with *film/book*.
- **Grammar**: Sentence IDs start with *grammar*.
- **Spoken**: Sentence IDs start with *conversation*.

## Data Splits

- **Training set**: Full **grammar\_Cairo**, sections of **grammar\_BivalTyp**, **film\_Bridge**, **book\_Khomai**, **conversation\_Windhoek5**
- **Development set**: Sections of **grammar\_BivalTyp**, **film\_Bridge**, **conversation\_Windhoek5**
- **Test set**: Full **film\_Titanic**, sections of **grammar\_BivalTyp**, **book\_Khomai**, **conversation\_Windhoek5**

# Acknowledgments

Roswitha Gases, Mauricius Gariseb, Mildred Howoses, Petronella Nauises, Dorothea Tases, Zarina Molochieva, Meidad Ovadia, Adam Rapoport, Naama Tiroshi, Anna Veselovsky, Margaret Zellers

# References

* Witzlack-Makarevich, Alena and Sylvanus Job. 2024. Bivalent patterns in Khoekhoe. In: Say, Sergey (ed.). BivalTyp: Typological database of bivalent verbs and their encoding frames. (Data first published on January 23, 2024; last revised on December 10, 2024.) (Available online at [https://www.bivaltyp.info](https://www.bivaltyp.info), Accessed on 18 February 2025.)

# Changelog

* 2025-05-15 v2.16
  * Initial release in Universal Dependencies.


<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.16
License: CC BY-NC-SA 4.0
Includes text: yes
Genre: fiction grammar-examples spoken
Lemmas: manual native
UPOS: manual native
XPOS: manual native
Features: manual native
Relations: manual native
Contributors: Tulchynska, Kira; Witzlack-Makarevich, Alena; Job, Sylvanus; Hahn, Michael
Contributing: here
Contact: kira.tulchynska@mail.huji.ac.il, witzlack@gmail.com
===============================================================================
</pre>
