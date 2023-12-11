---
title: "Axiomatic Hardware-Software Contracts for Security"
collection: publications
excerpt: "We propose leakage containment models (LCMs)---novel axiomatic security contracts which support formally reasoning about the security guarantees of programs when they run on particular microarchitectures. Our core contribution is an axiomatic vocabulary for formalizing LCMs, derived from the established axiomatic vocabulary for formalizing processor memory consistency models. Using this vocabulary, we formalize microarchitectural leakage---focusing on leakage through hardware memory systems---so that it can be automatically detected in programs and provide a taxonomy for classifying said leakage by severity. To illustrate the efficacy of LCMs, we first demonstrate that our leakage definition faithfully captures a sampling of (transient and non-transient) microarchitectural attacks from the literature. Second, we develop a static analysis tool based on LCMs which automatically identifies Spectre vulnerabilities in programs and scales to analyze real-world crypto-libraries."
date: 2022-06-18
venue: "ISCA'22"
citation: "Nicholas Mosier, Hanna Lachnitt, Hamed Nemati, and Caroline Trippel. Axiomatic hardware-software contracts for security. In Proceedings of the 49th Annual International Symposium on Computer Architecture, ISCA ’22, page 72–86, New York, NY, USA, 2022. Association for Computing Machinery. https://doi.org/10.1145/3470496.3527412"
---
[pdf](/files/lcms.pdf)
[video](https://www.youtube.com/watch?v=Kb0XO9OE0SA)
