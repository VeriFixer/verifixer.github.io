---
title: "VeriFixer: Automated Repair for Verification-Aware Programming Languages"
---

![VeriFixer Logo](VeriFixer-Logo-300dpi.png)

Writing software without bugs is not trivial. Automated Program Repair (APR), the process of automatically identifying a fix for a given bug, is a promising approach to increasing software quality by helping developers in the process of correcting their programs. However, in general, APR is based on weak correctness criteria, such as a test-suite, in which case the repaired program is considered fixed when it passes all tests successfully. This provides assurances to a certain degree but it does not guarantee that the program is correct. As Edsger Dijkstra famously put it: testing can show the presence of errors but never their absence. 

Testing is enough in many contexts, but, in critical systems, further assurances are needed which can be achieved through software verification, which mathematically assures that the software behaves exactly as intended, with respect to a certain formal specification or property. Several verification-aware programming languages and systems, where logical constructs such as pre- and post-conditions, invariants, and assertions provide assurances about the correctness of the program, are available and enable verification alongside code development. When using these to write code, bugs are usually flagged by a verifier which warns the user of specification violations. However, despite the availability of formal specifications that can act as strong correctness criteria for APR, users have to fix their programs manually since work on APR for verification-aware languages is still scarce.

**The main goal of this project is to develop techniques for the automated repair of programs written in a verification-aware programming language.** Due to the exploratory nature of this project, we will focus on Dafny programs (Leino, 2010), but the techniques will be applicable to other verification-aware languages and systems, such as VCC (Dahlweid et al., 2009), KeY (Ahrendt, 2016), and Verus (Verus, 2022). The repair will be guided by the formal specification, i.e., the formal specification will be assumed to be correct and a program that does not meet the specification will be automatically repaired to satisfy it. The short-term vision is to build an open-source, proof-of-concept, tool that supports users in the correction of bugs in verification-aware programming languages, and to provide to the community benchmark datasets from real-world code examples to support further developments in this area, and against which the outcomes of this project will be assessed. **The overall goal is to encourage a wider adoption of verification-aware programming languages and to reduce the burden of repairing programs written using them.** The outcomes of this project will result from a close collaboration between researchers from INESC TEC, INESC-ID Lisboa, and Carnegie Mellon.



## Contacts
**Principal Investigator (INESC TEC):** [Alexandra Mendes](https://archimendes.com)

[**Meet the Team**](/people)

**Research and Academic Institutions:** 
 - [INESC TEC: Instituto de Engenharia de Sistemas e Computadores, Tecnologia e Ciência](https://www.inesctec.pt/en)
 - [Carnegie Mellon University](https://www.cmu.edu)
 - [INESC-ID: Instituto de Engenharia de Sistemas e Computadores, Investigação e Desenvolvimento em Lisboa (INESC-ID)](https://inesc-id.pt)
 - [Instituto Superior Técnico, Universidade de Lisboa](https://tecnico.ulisboa.pt) 
 - [Faculty of Engineering, University of Porto](https://www.up.pt/feup/en)

## Funding
VeriFixer is funded by Fundação para a Ciência e a Tecnologia (FCT).
**Funded amount: 49.354,41 €**

[More details in the SciPROJ portal](https://sciproj.ptcris.pt/176595PRJ/).
