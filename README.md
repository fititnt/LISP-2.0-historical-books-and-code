# LISP-2.0-historical-books-and-code
Some historical books and code related to Lisp 2.0 and influence on other languages.

For more content, see the original
source at <http://www.softwarepreservation.org/projects/LISP/lisp2_family/>
(this personal git repository have just a few all documents there.)

> LISP 2
> "The LISP 2 project was a collaboration of System Development Corporation
and Information International Inc., and was initially planned for the Q32
computer, which was built by IBM for military purposes and which had a 48 bit
word and 18 bit addresses, i.e., it was better than the IBM 7090 for an
ambitious project. Unfortunately, the Q32 at SDC was never equipped with
more than 48K words of this memory. When it became clear that the Q32 had
too little memory, it was decided to develop the language for the IBM 360/67
and the Digital Equipment PDP-6 — SDC was acquiring the former, while III
and M.I.T. and Stanford preferred the latter. The project proved more
expensive than expected, the collaboration proved more difficult than
expected, and so LISP 2 was dropped. From a 1970s point of view, this was
regrettable, because much more money has since been spent to develop LISPs with
fewer features. However, it was not then known that the dominant machine for
AI research would be the PDP-10, a successor of the PDP-6. A part of the AI
community, e.g. BBN and SRI made what proved to be an architectural
digression in doing AI work on the SDS 940 computer." [McCarthy 1978]

---
<!-- TOC -->

- [LISP-2.0-historical-books-and-code](#lisp-20-historical-books-and-code)
    - [1960~ "LISP 2 system. 80 character/line"](#1960-lisp-2-system-80-characterline)
    - [1964 "LISP 2 Specifications Proposal. AIM-21, Stanford Artificial Intelligence Project, Stanford University, August 19, 1964"](#1964-lisp-2-specifications-proposal-aim-21-stanford-artificial-intelligence-project-stanford-university-august-19-1964)
    - [1965  LISP II Project : The Internal Language](#1965--lisp-ii-project--the-internal-language)
    - [1966 The Implementation of LISP 2 (paper)](#1966-the-implementation-of-lisp-2-paper)
    - [1974 GTL for Burroughs B 5500 at Georgia Institute of Technology](#1974-gtl-for-burroughs-b-5500-at-georgia-institute-of-technology)
    - [1941 CRISP A Programming Language and System](#1941-crisp-a-programming-language-and-system)

<!-- /TOC -->
---

## 1960~ "LISP 2 system. 80 character/line"

- [LISP_2_SYM_darker.pdf](LISP_2_SYM_darker.pdf)
- **LISP 2 system. 80 character/line, 1 inch notebook. Property of Jeff Barnett. Scanned copy, darker threshold setting. PDF**
- Jeff Barnett. Annotations. June 2010. HTML
  - http://www.softwarepreservation.org/projects/LISP/lisp2/listing-notes/
- **Source: <http://www.softwarepreservation.org/projects/LISP/lisp2/LISP_2_SYM_darker.pdf>**

## 1964 "LISP 2 Specifications Proposal. AIM-21, Stanford Artificial Intelligence Project, Stanford University, August 19, 1964"

- [Stanford-AIM-21.pdf](Stanford-AIM-21.pdf)
- **R. W. Mitchell. LISP 2 Specifications Proposal. AIM-21, Stanford Artificial Intelligence Project, Stanford University, August 19, 1964, 12 pages. PDF**

> "Specifications for a LISP 2 system are proposed. The source language is basically ALGOL 60 extended to include list processing, input/output and language extension facilities. The system would be implemented with a source language translator and optimizer, the output of which could be processed by either an interpreter or a compiler. The implementation is specified for a single address computer with particular reference to an IBM 7090 where necessary. Expected efficiency of the system for list processing is significantly greater than the LISP 1.5 interpreter and also somewhat better than the LISP 1.5 compiler. For execution of numeric algorithms the system should be comparable to many current "algebraic" compilers. Some familiarity with LISP 1.5, ALGOL and the IBM 7090 is assumed."

## 1965  LISP II Project : The Internal Language
- [LISP-II-The-internal-language.pdf](LISP-II-The-internal-language.pdf)
  - Source: <http://www.softwarepreservation.org/projects/LISP/lisp2/TM-2260_002_01-The_Internal_Language.pdf>
- "S. L. Kameny. The Internal Language. Memo No. 1, LISP II Project, TM-2260/002/01, System Development Corporation, Santa Monica, California, September 3, 1965, 30 pages. Gift of Clark Weissman. PDF"

## 1966 The Implementation of LISP 2 (paper)
- [Kameny_et_al-Implementation_of_LISP_2.pdf](Kameny_et_al-Implementation_of_LISP_2.pdf)
> Stanley L. Kameny, Lowell Hawkinson, Clark Weissman, Jeffrey A. Barnett,
  Robert A. Saunders, Erwin Book, Donna Firth, and Paul W. Abrahams.
  The Implementation of LISP 2. 1966? PDF


## 1974 GTL for Burroughs B 5500 at Georgia Institute of Technology

> Martin Alexander. GTL -- Georgia Tech Language. Georgia Institute of
  Technology, Atlanta, Georgia. Extends Burroughs Extended Algol compiler with
  strings, records, complex arithmetic, list processing, plex processing,
  and extended I/O features. The list processing features are based on LISP 2.

- [Burroughs-B5500/GTL_Programmers_Reference_Manual_for_the_Burroughs_B_5500_Aug1974.pdf](Burroughs-B5500/GTL_Programmers_Reference_Manual_for_the_Burroughs_B_5500_Aug1974.pdf)
  - Source: <http://bitsavers.org/pdf/georgiaTech/GTL_Programmers_Reference_Manual_for_the_Burroughs_B_5500_Aug1974.pdf>
- Source code. In CUBE library, version 13. See 
  - [Burroughs-B5500/GTL-L200015.alg](Burroughs-B5500/GTL-L200015.alg)
  - [Burroughs-B5500/GTL-L200016.dat](Burroughs-B5500/GTL-L200016.dat)


## 1941 CRISP A Programming Language and System

- "J. A. Barnett and D. L. Pintar. CRISP: A Programming Language and System. TM-5455/000/00 (DRAFT), System Development Department, December 31, 1974, 323 pages. PDF"
  - [CRISP/1974-CRISP-A-Programming-Language-and-System.pdf](CRISP/1974-CRISP-A-Programming-Language-and-System.pdf)
  - Source: <http://www.softwarepreservation.org/projects/LISP/crisp_ibm370_sdc/TM-5444_000_00.pdf>
- "Jeffrey A. Barnett. The CRISP Programming Language System: an Historical Overview. A slide presentation to the Albuquerque Lisp/Scheme Group, September 20, 2009. PDF"
  - [CRISP/2009-CRISP-talk.pdf](CRISP/2009-CRISP-talk.pdf)
