ULI: Word Count
===

> Version: 0
>
> Authors: Steven R. Loomis
>
> Date: 2017-01-16
>
> This Version: 
>
> Previous Version: n/Authors
>
> Latest Version: [https://github.com/unicode-org/uli-docs/wordcount.md](https://github.com/unicode-org/uli-docs/wordcount.md)

Summary
---

The purpose of this document is to collect requirements and discuss techniques for accurate and consistent word count, particularly for translation interchange purposes.

Status
---

This document is _intended to become_ a **Unicode Technical Note**.
Sole responsibility for its contents rests with the author(s). Publication does not imply any endorsement by the Unicode Consortium. This document is not subject to the [Unicode Patent Policy](http://www.unicode.org/policies/patent_policy.html).

For information on Unicode Technical Notes including criteria for acceptance, see [http://www.unicode.org/notes/](http://www.unicode.org/notes/).

Contents
---

* [Introduction](#Introduction)
* [References](#References)
* [Modifications](#Modifications)

Introduction
---

One of the challenges of translation interoperability is objectively measuring the difficulty of a particular translation workload. A common metric used is the word count. However, methods for counting words vary across different systems and languages.

Some examples will suffice. First, Thai is written without space characters between words, as is Japanese and Chinese. Should numbers be included or not included? Are Mongolian suffixes considered a separate word or not?

There are existing standards relating to word segmentation such as [UAX29](http://www.unicode.org/reports/tr29), as well as existing standards which relate to word count specifically, [GMX-V](http://www.unicode.org/uli/pas/gmx-v/).

The purpose of this document is to collect requirements and discuss techniques for accurate and consistent word count, particularly for translation interchange purposes.

References
---

* [UAX29](http://www.unicode.org/reports/tr29) Unicode Standard Annex #29: Unicode Text Segmentation

* [GMX-V](http://www.unicode.org/uli/pas/gmx-v/) Global Information Management Metrics Volume (GMX-V) 1.0 Specification

Modifications
---

-----

Fork me on [GitHub](https://github.com/unicode-org/uli-docs.git)!
