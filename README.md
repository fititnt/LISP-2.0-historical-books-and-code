# LISP-2.0-historical-books-and-code
Some historical books related to Lisp 2.0. For more content, see the original
source at <http://www.softwarepreservation.org/projects/LISP/lisp2_family/>.
This personal git repository have just a few **(not all)** of the documents
from the  softwarepreservation.org

> LISP 2
> "The LISP 2 project was a collaboration of System Development Corporation and Information International Inc., and was initially planned for the Q32 computer, which was built by IBM for military purposes and which had a 48 bit word and 18 bit addresses, i.e., it was better than the IBM 7090 for an ambitious project. Unfortunately, the Q32 at SDC was never equipped with more than 48K words of this memory. When it became clear that the Q32 had too little memory, it was decided to develop the language for the IBM 360/67 and the Digital Equipment PDP-6 — SDC was acquiring the former, while III and M.I.T. and Stanford preferred the latter. The project proved more expensive than expected, the collaboration proved more difficult than expected, and so LISP 2 was dropped. From a 1970s point of view, this was regrettable, because much more money has since been spent to develop LISPs with fewer features. However, it was not then known that the dominant machine for AI research would be the PDP-10, a successor of the PDP-6. A part of the AI community, e.g. BBN and SRI made what proved to be an architectural digression in doing AI work on the SDS 940 computer." [McCarthy 1978]

> Source: http://www.softwarepreservation.org/projects/LISP/lisp2_family/


---
<!-- TOC -->

- [LISP-2.0-historical-books-and-code](#lisp-20-historical-books-and-code)
    - [1960~ "LISP 2 system. 80 character/line" (`LISP_2_SYM_darker.pdf`)](#1960-lisp-2-system-80-characterline-lisp_2_sym_darkerpdf)
    - [1964 "LISP 2 Specifications Proposal. AIM-21, Stanford Artificial Intelligence Project, Stanford University, August 19, 1964" (`Stanford-AIM-21.pdf`)](#1964-lisp-2-specifications-proposal-aim-21-stanford-artificial-intelligence-project-stanford-university-august-19-1964-stanford-aim-21pdf)
    - [1966 The Implementation of LISP 2 (paper) (`Kameny_et_al-Implementation_of_LISP_2.pdf`)](#1966-the-implementation-of-lisp-2-paper-kameny_et_al-implementation_of_lisp_2pdf)
    - [1974 GTL for Burroughs B 5500 at Georgia Institute of Technology (`GTL_Programmers_Reference_Manual_for_the_Burroughs_B_5500_Aug1974.pdf`)](#1974-gtl-for-burroughs-b-5500-at-georgia-institute-of-technology-gtl_programmers_reference_manual_for_the_burroughs_b_5500_aug1974pdf)

<!-- /TOC -->
---

## 1960~ "LISP 2 system. 80 character/line" (`LISP_2_SYM_darker.pdf`)

- [LISP_2_SYM_darker.pdf](LISP_2_SYM_darker.pdf)
- **LISP 2 system. 80 character/line, 1 inch notebook. Property of Jeff Barnett. Scanned copy, darker threshold setting. PDF**
- Jeff Barnett. Annotations. June 2010. HTML
  - http://www.softwarepreservation.org/projects/LISP/lisp2/listing-notes/
- **Source: <http://www.softwarepreservation.org/projects/LISP/lisp2/LISP_2_SYM_darker.pdf>**

## 1964 "LISP 2 Specifications Proposal. AIM-21, Stanford Artificial Intelligence Project, Stanford University, August 19, 1964" (`Stanford-AIM-21.pdf`)

- [Stanford-AIM-21.pdf](Stanford-AIM-21.pdf)
- **R. W. Mitchell. LISP 2 Specifications Proposal. AIM-21, Stanford Artificial Intelligence Project, Stanford University, August 19, 1964, 12 pages. PDF**

> "Specifications for a LISP 2 system are proposed. The source language is basically ALGOL 60 extended to include list processing, input/output and language extension facilities. The system would be implemented with a source language translator and optimizer, the output of which could be processed by either an interpreter or a compiler. The implementation is specified for a single address computer with particular reference to an IBM 7090 where necessary. Expected efficiency of the system for list processing is significantly greater than the LISP 1.5 interpreter and also somewhat better than the LISP 1.5 compiler. For execution of numeric algorithms the system should be comparable to many current "algebraic" compilers. Some familiarity with LISP 1.5, ALGOL and the IBM 7090 is assumed."


## 1966 The Implementation of LISP 2 (paper) (`Kameny_et_al-Implementation_of_LISP_2.pdf`)
- [Kameny_et_al-Implementation_of_LISP_2.pdf](Kameny_et_al-Implementation_of_LISP_2.pdf)
> Stanley L. Kameny, Lowell Hawkinson, Clark Weissman, Jeffrey A. Barnett,
  Robert A. Saunders, Erwin Book, Donna Firth, and Paul W. Abrahams.
  The Implementation of LISP 2. 1966? PDF


## 1974 GTL for Burroughs B 5500 at Georgia Institute of Technology (`GTL_Programmers_Reference_Manual_for_the_Burroughs_B_5500_Aug1974.pdf`)

> Martin Alexander. GTL -- Georgia Tech Language. Georgia Institute of
  Technology, Atlanta, Georgia. Extends Burroughs Extended Algol compiler with
  strings, records, complex arithmetic, list processing, plex processing,
  and extended I/O features. The list processing features are based on LISP 2.

- [GTL_Programmers_Reference_Manual_for_the_Burroughs_B_5500_Aug1974.pdf](GTL_Programmers_Reference_Manual_for_the_Burroughs_B_5500_Aug1974.pdf)
  - Source: <http://bitsavers.org/pdf/georgiaTech/GTL_Programmers_Reference_Manual_for_the_Burroughs_B_5500_Aug1974.pdf>
- Source code. In CUBE library, version 13. See 
  - [Burroughs-B5500/GTL-L200015.alg](Burroughs-B5500/GTL-L200015.alg)
  - [Burroughs-B5500/GTL-L200016.dat](Burroughs-B5500/GTL-L200016.dat)