**GSoC CLTK 2018 Summary**
==========================


Middle High German
==================
**Related PRs**: [#692](https://github.com/cltk/cltk/pull/692), [#711](https://github.com/cltk/cltk/pull/711), [#786](https://github.com/cltk/cltk/pull/786), [#816](https://github.com/cltk/cltk/pull/816)

**Deliverables**:

- stopword filtering

- tokenizer

- stemmer

- text normalizer

- syllabifier

- IPA transcription

- Soundex-based phonetic indexing

- ASCII encoder

Middle English
==============

**Related PRs**: [#757](https://github.com/cltk/cltk/pull/757), [#758](https://github.com/cltk/cltk/pull/758), [#759](https://github.com/cltk/cltk/pull/759)

**Deliverables**:

- tokenizer

- stemmer

- text normalizer

- syllabifier

- stresser

- Soundex-based phonetic indexing

Old English
===========
**Related PRs**: [#767](https://github.com/cltk/cltk/pull/767), [#809](https://github.com/cltk/cltk/pull/809)

**Deliverables**:

- IPA Transcription 

- syllabifier

Middle Low German
=================
**Related PRs**: [#770](https://github.com/cltk/cltk/pull/770)

**Related repositories**:
* [low german models](https://github.com/cltk/middle_low_german_models_cltk)

**Deliverables**:

- backoff tagger

Other
=====

- [Levenshtein Distance and Word Alignment](https://github.com/cltk/cltk/pull/740)

*Lexical distance alignment algorithms (Levenshtein Distance, Damerau-Levenshtein Distance, Needleman-Wunsch)*

- [Levenshtein Automata](https://github.com/cltk/cltk/pull/762)

*Deterministic, Nondeterministic and Levenshtein Automata (along with a spelling corrector). Wordlist to trie conversion*

- [Anglo-Saxon/Anglo-Frisian runic transliteration](https://github.com/cltk/cltk/pull/774)

*Anglo-Saxon/Anglo-Frisian runes to Latin transliterator*

- [Language Agnostic Syllabifier](https://github.com/cltk/cltk/pull/788)

*Language-agnostic syllabification*

Beyond Summer
=============

Having laid the foundations for some of the major Germanic languages, my future goal would be to further expand the core to prosody scansion modules. I would also like to go back and parallelize part of the Levenshtein Automaton spell checker, to create a historical spelling normalizer.


I would like to thank both my mentors, Todd Cook and James Tauber as well as the whole community for the amazing learning experience.
