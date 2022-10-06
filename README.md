# Argument Minining Corpora
A compilation of the most famous/used argument mining corpora in English.

| Id  |  Corpus | Relevant Papers |
| --- | ------- | --------------- |
| 1   | AraucariaDB | [Reed, C., 2005](http://www.arg.tech/people/chris/publications/2005/cuba.pdf) <br> [Reed et al., 2008](https://aclanthology.org/L08-1553/) |
| 2   | European Court of Human Rights (ECHR) | [Mochales & Moens, 2007](https://dl.acm.org/doi/10.5555/1565610.1565624) <br> [Mochales & Moens, 2008](https://dl.acm.org/doi/10.5555/1564008.1564011) |
| 3   | Internet Argument corpus (IAC) | [Walker et al. 2012](https://aclanthology.org/L12-1643/) |
| 4   | Argument Annotated Essays Corpus (AAEC) | [Stab & Gurevych, 2014a](https://aclanthology.org/C14-1142/) |
| 5   | Wikipedia articles | [Aharoni et al., 2014 ](https://aclanthology.org/W14-2109/) |
| 6   | User-generated Web Discourse<br>Gold standard Toulmin corpus (study 2) | [Habernal & Gurevych, 2017](https://arxiv.org/abs/1601.02403) |

## Details of the corpus
Some statistics and characteristics of the previously listed corpora are presented below.

<table>
  <tr><th align="center" colspan="2">1 - AraucariaDB</th></tr>
  <tr><th align="left">Domain</th><td>Newspapers and court cases</td></tr>
  <tr><th align="left">Language</th><td>English</td></tr>
  <tr><th align="left">Size</th><td>Over 700 analyses, and a total of 80,000 words</td></tr>
  <tr><th align="left">Argument model</th><td>Walton’s schemes</td></tr>
  <tr><th align="left">Annotation process</th><td>1. AML: Argument Markup Language (XML-based tree structure)<br>2. Two annotator (one main analyst and one secondary analyst)</td></tr>
  <tr><th align="left">Agreement</th><td>Unknown</td></tr>
  <tr><th align="left">Comments</th><td>Text gathered from newspaper editorials, parliamentary records, judicial summaries and discussion boards</td></tr>
  <tr><th align="left">URL</th><td><a href="https://arg-tech.org/index.php/research/araucariadb/">https://arg-tech.org/index.php/research/araucariadb/</a></td></tr>
</table>

<table>
  <tr><th align="center" colspan="2">2 - European Court of Human Rights (ECHR)</th></tr>
  <tr><th align="left">Domain</th><td>Legal</td></tr>
  <tr><th align="left">Language</th><td>English</td></tr>
  <tr><th align="left">Size</th><td>12,904 sent., 10,133 non arg. and 2,771 arg., 2,355 premises and 416 conclusions</td></tr>
  <tr><th align="left">Time</th><td>4 weeks - docs analyzed by 2 lawyers </td></tr>
  <tr><th align="left">Argument model</th><td>Argumentation schemes<br>AC: conclusion, and premise<br>AR: support / attack</td></tr>
  <tr><th align="left">Annotation process</th><td>1. All documents are annotated independently by 2 lawyers<br>2. The annotations were analysed by another legal expert<br>3. Fourth legal expert who annotated again the documents</td></tr>
  <tr><th align="left">Agreement</th><td>K = 0.58, K = 0.80</td></tr>
  <tr><th align="left">Comments</th><td>55 documents composed of 25 legal cases and 29 admissibility reports</td></tr>
</table>

<table>
  <tr><th align="center" colspan="2">3 - Internet Argument corpus (IAC)</th></tr>
  <tr><th align="left">Domain</th><td>Political</td></tr>
  <tr><th align="left">Language</th><td>English</td></tr>
  <tr><th align="left">Size</th><td>Set of 390,704 posts in 11,800 discussions (from debate site 4forums.com)</td></tr>
  <tr><th align="left">Annotation process</th><td>1. With Amazon’s Mechanical Turk: Complex process, with several stages, and several Turkers<br>2. Data stored in JSON files with most annotations in CSV format</td></tr>
  <tr><th align="left">Agreement</th><td>K(topic) =  0.22–0.60<br>K(avg) =  0.47v</td></tr>
  <tr><th align="left">Comments</th><td>Corpus for research in political debate on Internet forums. It consists of approximately 11,000 discussions, 390,000 posts, and some 73,000,000 words</td></tr>
  <tr><th align="left">URL</th><td><a href="https://nlds.soe.ucsc.edu/iac">https://nlds.soe.ucsc.edu/iac</a></td></tr>
</table>

<table>
  <tr><th align="center" colspan="2">4 - Argument Annotated Essays Corpus (AAEC)</th></tr>
  <tr><th align="left">Domain</th><td>Persuasive essays (various)</td></tr>
  <tr><th align="left">Language</th><td>English</td></tr>
  <tr><th align="left">Size</th><td>90 persuasive essays, 1,673 sentences with 34,917 tokens</td></tr>
  <tr><th align="left">Argument model</th><td>AC: major claim, claim, and premise<br>AR: support / attack</td></tr>
  <tr><th align="left">Annotation process</th><td>1. Three scorers for the ACs and RCs<br>2. ACs are consolidated and selected by majority vote<br>3. Same for RCs</td></tr>
  <tr><th align="left">Agreement</th><td>αU(comp) = 0.72<br>αU(rel) = 0.81</td></tr>
  <tr><th align="left">Comments</th><td>The corpus consists of 90 English persuasive essays (collected from essay forum). The corpus contains 1,879 sentences. 402 Essays about 8 controversial topics</td></tr>
  <tr><th align="left">URL</th><td><a href="http://corpora.aifdb.org/AAECv2">http://corpora.aifdb.org/AAECv2</a></td></tr>
</table>

<table>
  <tr><th align="center" colspan="2">5 - Wikipedia articles</th></tr>
  <tr><th align="left">Domain</th><td>Various</td></tr>
  <tr><th align="left">Language</th><td>English</td></tr>
  <tr><th align="left">Size</th><td>~50,000 sent, 2,683 argument elements, collected in the context of 33 controversial topics</td></tr>
  <tr><th align="left">Argument model</th><td>AC: claim and its associated supporting evidence<br>In detail: Topic, Context Dependent Claim (CDC), Context Dependent Evidence (CDE)</td></tr>
  <tr><th align="left">Annotation process</th><td>20 carefully trained in-house labelers<br>Two-stage labeling approach:<br>1. Five labelers worked independently on the same text<br>2. Five labelers independently crosschecked the joint list of the detected candidates<br>Candidates confirmed by at least three labelers were included in the corpus</td></tr>
  <tr><th align="left">Agreement</th><td>K(claim) = 0.39<br>K(evidence) = 0.4</td></tr>
  <tr><th align="left">Comments</th><td>A corpus of 2,683 argument elements, collected in the context of 33 predefined controversial topics</td></tr>
</table>

<table>
  <tr><th align="center" colspan="2">6 - User-generated Web Discourse</th></tr>
  <tr><th align="left">Language</th><td>English</td></tr>
  <tr><th align="left">Size</th><td>340 documents</td></tr>
  <tr><th align="left">Time</th><td>Each annotator spent 35 hours by annotating in the course of 5 weeks<br>Discussions and consolidation of the gold data took another 6 hours</td></tr>
  <tr><th align="left">Argument model</th><td>Adaptation of Toulmin’s model<br>AC: claim, premise, backing, rebuttal, and refutation</td></tr>
  <tr><th align="left">Annotation process</th><td>All docs were annotated by 3 independent annotators. Three phases:<br>1. 50 random comments and forum posts were annotated<br>2. 148 comments and forum posts as well as 41 blog posts<br>3. 96 comments/forum posts, 8 blog posts, and 8 articles for this phase</td></tr>
  <tr><th align="left">Agreement</th><td>αU = 0.48<br>Joint logos (claim, premise, backing, rebuttal, refutation) for Articles + Blog posts + Comments + Forum posts</td></tr>
  <tr><th align="left">Comments</th><td>Contains 340 documents about 6 controversial topics in education</td></tr>
  <tr><th align="left">URL</th><td><a href="https://bit.ly/2vdkHOD">https://bit.ly/2vdkHOD</a></td></tr>
</table>

## Authors
Created on Oct 04, 2022  
Created by:
- <a href="https://github.com/ansegura7" target="_blank">Andrés Segura-Tinoco</a>

## License
This project is licensed under the terms of the <a href="https://github.com/argrecsys/am-corpora/blob/main/LICENSE">Apache License 2.0</a>.

## Acknowledgements
This work was supported by the Spanish Ministry of Science and Innovation (PID2019-108965GB-I00).
