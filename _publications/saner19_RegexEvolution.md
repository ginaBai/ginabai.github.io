---
title: "Exploring Regular Expression Evolution"
collection: publications
permalink: /publication/icse19_GenderBias
date: 2019-2-24
venue: 'The IEEE 26th International Conference on Software Analysis, Evolution and Reengineering <b>SANER 2019</b>'
citation: 'Peipei Wang, <b>Gina R. Bai</b>, and Kathryn T. Stolee.'
---
[[Full Paper]](http://ginabai.github.io/files/PaperPreprints/saner19_RegexEvolution.pdf)

## Abstract
Although there are tools to help developers un- derstand the matching behaviors between a regular expression and a string, regular-expression related faults are still common. Learning developers’ behavior through the change history of regular expressions can identify common edit patterns, which can inform the creation of mutation and repair operators to assist with testing and fixing regular expressions.

In this work, we explore how regular expressions evolve over time, focusing on the characteristics of regular expression edits, the syntactic and semantic difference of the edits, and the feature changes of edits. Our exploration uses two datasets. First, we look at GitHub projects that have a regular expression in their current version and look back through the commit logs to collect the regular expressions’ edit history. Second, we collect regular expressions composed by study participants during problem- solving tasks. Our results show that 1) 95% of the regular expressions from GitHub are not edited, 2) most edited regular expressions have a syntactic distance of 4-6 characters from their predecessors, 3) over 50% of the edits in GitHub tend to expand the scope of regular expression, and 4) the number of features used indicates the regular expression language usage increases over time. This work has implications for supporting regular expression repair and mutation to ensure test suite quality.

---
Recommended citation: 

Peipei Wang, Gina R. Bai and Kathryn T. Stolee, "Exploring Regular Expression Evolution," <i>2019 IEEE 26th International Conference on Software Analysis, Evolution and Reengineering (SANER)</i>, 2019, pp. 502-513, doi: 10.1109/SANER.2019.8667972.
