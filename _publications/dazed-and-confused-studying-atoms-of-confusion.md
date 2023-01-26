---
title: "Dazed and Confused: Studying the Prevalence of Atoms of Confusion in Long-Lived Java Libraries"
layout: page
date: 2022-10-07
year: 2022
month: 10
description:
tags: []
pub: true
authors: Wendell Mendes, Oton Pinheiro, Emanuele Santos, Lincoln Rocha, Windson Viana
in: "In Proceedings of 2022 IEEE International Conference on Software Maintenance and Evolution (ICSME)"
file: https://ieeexplore.ieee.org/document/9978238
image:  /assets/images/thumbs/dazed.png
bibtex: /assets/citations/mendes_icsme_2022.bib
---

# Dazed and Confused: Studying the Prevalence of Atoms of Confusion in Long-Lived Java Libraries

*Wendell Mendes, Oton Pinheiro, Emanuele Santos, Lincoln Rocha, Windson Viana (2022). In Proceedings of 2022 IEEE International Conference on Software Maintenance and Evolution (ICSME), Limassol, Cyprus, 106-116.*

<center><img src="/assets/images/thumbs/dazed.png" style="width: 100%;" /></center>

## Abstract

Program comprehension is a fundamental activity in software maintenance and evolution, impacting several tasks such as bug fixing, code reuse, and implementation of new features. The Atom of Confusion (AC) is considered the smallest piece of code that can confuse programmers, difficulting the correct understanding of the source code under consideration. Previous studies have shown that these atoms can significantly impact the presence of bugs in C++ projects and increase the time and effort to code understanding in C++ and Java programs. To gather more evidence about the diffusion of ACs in the Java ecosystem, we conduct a study to analyze the prevalence, co-occurrences (at the class level), and evolution of ACs in 27 long-lived Java libraries. To support our investigation, we developed an ACs automatic search tool, which found 11.404 occurrences in the studied libraries. The Conditional Operator and Logic as Control Flow ACs were the most prevalent among the 10 types of ACs assessed. Our findings show that Conditional Operator and Logic as Control Flow were more likely to co-occur in the same class. Finally, we observed that the prevalence of ACs did not decrease over time. On the contrary, in 13 libraries, the presence grew proportionally more than the size of the library in lines of code. Furthermore, in 15 libraries, the fraction of Java classes containing at least one AC also increases over time.

[Preprint](/assets/papers/mendes_icsme_2022.pdf) [Full paper](https://ieeexplore.ieee.org/document/9978238)



[BibTex](/assets/citations/mendes_icsme_2022.bib)