
+++

title = "Pervasive Computing @ UniBo / Cesena: overview"
description = "Quick overview of the research activities of the Pervasive Computing group at the University of Bologna, Cesena campus"
outputs = ["Reveal"]
aliases = [
    "/index/"
]

+++


# **Pervasive Computing**
# @ UniBo / Cesena: overview

#### [Danilo Pianini](mailto:danilo.pianini@unibo.it) --- {{% today %}}

---

# Who

## Tenured

| Nice picture | Name | Role |
| ---- | ---- | ----- |
| ![](https://www.unibo.it/uniboweb/utils/UserImage.aspx?IdAnagrafica=341468&IdFoto=23233366) | [Andrea Omicini](https://www.unibo.it/sitoweb/andrea.omicini/en) | Full professor and Dean |
| ![](https://www.unibo.it/uniboweb/utils/UserImage.aspx?IdAnagrafica=355340&IdFoto=e3a7b911) | [Mirko Viroli](https://www.unibo.it/sitoweb/mirko.viroli/en) | Full professor |
| ![](https://www.unibo.it/uniboweb/utils/UserImage.aspx?IdAnagrafica=340844&IdFoto=bd99721f) | [Alessandro Ricci](https://www.unibo.it/sitoweb/a.ricci/en) | Associate professor |
| ![](https://www.unibo.it/uniboweb/utils/UserImage.aspx?IdAnagrafica=447370&IdFoto=f3c9f266) | [Andrea Roli](https://www.unibo.it/sitoweb/andrea.roli/en) | Assistant professor |

---

# Who

## Tenure track / Fixed time researchers

Danilo pianini and roberto casadei

| Nice picture | Name | Role |
| ---- | ---- | ----- |
| ![](https://www.unibo.it/uniboweb/utils/UserImage.aspx?IdAnagrafica=503326&IdFoto=e1c80103) | [Danilo Pianini](https://www.unibo.it/sitoweb/danilo.pianini/en) | Senior Assistant professor |
| ![](https://www.unibo.it/uniboweb/utils/UserImage.aspx?IdAnagrafica=649232&IdFoto=4ba13386) | [Roberto Casadei](https://www.unibo.it/sitoweb/roby.casadei/en) | Senior Assistant professor |
| ![](https://www.unibo.it/uniboweb/utils/UserImage.aspx?IdAnagrafica=758527&IdFoto=0d144755) | [Giovanni Ciatto](https://www.unibo.it/sitoweb/giovanni.ciatto/en) | Junior Assistant professor |

---

# Who

## Phd Candidates / post-docs

| Nice picture | Name | Role |
| ---- | ---- | ----- |
| ![](https://www.unibo.it/uniboweb/utils/UserImage.aspx?IdAnagrafica=979102&IdFoto=73c988ab) | [Gianluca Aguzzi](https://www.unibo.it/sitoweb/gianluca.aguzzi/en) | PhD candidate |

---

# Who

## Phd Candidates / Students

| Nice picture | Name | Role |
| ---- | ---- | ----- |
| ![](https://www.unibo.it/uniboweb/utils/UserImage.aspx?IdAnagrafica=1444563&IdFoto=cb27afa6) | [Ruslan Shaiakhmetov](https://www.unibo.it/sitoweb/ruslan.shaiakhmetov/en) | PhD student |
| ![](https://www.unibo.it/uniboweb/utils/UserImage.aspx?IdAnagrafica=1135878&IdFoto=7e5aea53) | [Martina Baiardi](https://www.unibo.it/sitoweb/m.baiardi/en) | PhD student |
| ![](https://www.unibo.it/uniboweb/utils/UserImage.aspx?IdAnagrafica=1241268&IdFoto=19a442b7) | [Davide Domini](https://www.unibo.it/sitoweb/davide.domini/en) | PhD student |
| ![](https://www.unibo.it/uniboweb/utils/UserImage.aspx?IdAnagrafica=1057398&IdFoto=d40837ab) | [Nicolas Farabegoli](https://www.unibo.it/sitoweb/nicolas.farabegoli/en) | PhD student |

---

# Who

## Research fellows

| Nice picture | Name | Role |
| ---- | ---- | ----- |
| ![](https://www.unibo.it/uniboweb/utils/UserImage.aspx?IdAnagrafica=1195649&IdFoto=a66c31ab) | [Angelo Filaseta](https://www.unibo.it/sitoweb/angelo.filaseta/en) | Research fellow |
| ![](cortecchia.jpg) | [Angela Cortecchia](mailto:angela.cortecchia@unibo.it) | Guest reseach fellow |

---

# What

Pervasive computing, full spectrum, from modelling to industrial application

![](group-act.svg)

note: seniors omitted

---

# Conceptualization

## Finding the **right** abstractions

<blockquote>
Pick the <b>right abstractions</b>, and programming will <u>flow naturally from design</u>;
modules will have small and simple interfaces;
and new functionality will more likely fit in without extensive reorganization.
<br>
Pick the <b>wrong abstractions</b>, and programming will be <u>a series of nasty surprises</u>:
interfaces will become baroque and clumsy as they are forced to accommodate unanticipated interactions,
and even the simplest of changes will be hard to make.
<cite>Edmond Lau, The Effective Engineer: How to Leverage Your Efforts In Software</cite>
</blockquote>

{{% multicol %}}{{% col %}}
#### Macroprogramming / aggregate computing
* Control multiple entities at once
* Program space and time, not devices
* **Roberto** will provide an introduction:<br>*From Macro-programming to Aggregate Computing*
{{% /col %}}{{% col %}}
#### Agent-oriented BDI programming
* Model autonomous entities with beliefs, desires, intentions
* **Martina** will show a new experimental tool<br>*Martina metti un titolo*
{{% /col %}}{{% /multicol %}}

---

# Learning

## Learning behavior **collectively**

<blockquote>
Collective wisdom is more likely to arise when sound judgment is based on the entirety of our multiple intelligences.
<cite>Alan Briskin, The Power of Collective Wisdom: And the Trap of Collective Folly</cite>
</blockquote>

{{% multicol %}}{{% col %}}
#### Multi-Agent Reinforcement Learning 
* Hybrid approach to learning -- combining learning with macroprogramming
* Focus on large-scale -- learning systems that scale to thousands of agents
* **Gianluca** will show some recent advances: <br>*Engineering Swarm Behaviours through Hybrid Aggregate Computing*</br>
{{% /col %}}{{% col %}}
#### Specialized federated learning
* Learn a joint model without sharing data
* Model peer-to-peer learning through aggregate computing
* Address data heterogeneity through opportunistic clustered federated learning
* **Davide** will provide an introduction<br>*Field Based Federated Learning*
{{% /col %}}{{% /multicol %}}

---

# Tools

## Ideas need to be brought to **practice**

<blockquote>
If the only tool you have is a hammer, it's hard to eat spaghetti.
<cite>David Allen</cite>
</blockquote>

{{% multicol %}}{{% col %}}
#### Programming Languages
* The practical tool to capture abstractions
* [Protelis](https://protelis.github.io/), a stand-alone aggregate programming language
  * legacy, maintained but no longer evolved
* [Scafi](https://scafi.github.io/), a Scala DSL for aggregate computing
  * **Gianluca** will introduce it
* [Collektive](https://github.com/Collektive/collektive), a Kotlin Multiplatform DSL for aggregate computing
  * **Angela** will introduce it
* [JaKtA](https://github.com/jakta-bdi/jakta), a Kotlin DSL for BDI Agents
  * **Martina** will introduce it
{{% /col %}}{{% col %}}
#### Simulation
* Essential tool for development and evaluation
* [Alchemist](https://alchemistsimulator.github.io/), a simulator for pervasive computing
  * I will show a few use cases
* Improvements to existing industrial simulators for race cars are ongoing
  * **Ruslan** will present<br>
  *Closing the gap between reality and simulation in motorsport*
{{% /col %}}{{% /multicol %}}

---

# Deployment

## Ideas need to be brought to **practice**

<blockquote>
Good ideas need good strategy to realize their potential.
<cite>Reid Hoffman</cite>
</blockquote>

{{% multicol %}}{{% col %}}
#### Cluster and grid computing
* Experimenting ways to control heterogeneous devices uniformly
* Two main heterogeneous clusters:
  * AlmaAI
  * Area 4.0
* **Giovanni** leads the development
{{% /col %}}{{% col %}}
#### Pulverization
* An approach to break down computation in small pieces and deploy it heterogeneous devices
* Bridge the gap between homo- and heterogeneity
  * **Nicolas** designed a pulverization platform
{{% /col %}}{{% /multicol %}}

---

# Industry

## Ideas need to be brought to **practice**

<blockquote>
Every once in a while, a new technology, an old problem, and a big idea turn into an innovation.
<cite>Dean Kamen</cite>
</blockquote>

{{% multicol %}}{{% col %}}
#### Wood 4.0
* Collaboration with SCM Group
* Software updates in large woodwork industrial machines
* Business-critical
* Heterogeneous machinery
* **Angelo** will discuss it
{{% /col %}}{{% col %}}
#### Racecar simulation reality gap
* Collaboration with Dallara Automobili
* Essential tool for top tier racing
* Correlation between track and simulation is central
* The ability to mimic a human driver is paramount
* **Ruslan** is working on them
{{% /col %}}{{% /multicol %}}

---

# The plan

1. **Roberto Casadei**: *From Macro-programming to Aggregate Computing*
1. **Gianluca Aguzzi**: *Gianluca write a title and send me a PR*
1. **Davide Domini**: *Field Based Federated Learning*
1. **Danilo Pianini**: *Simulation and software process engineering in pervasive computing*
1. **Angela Cortecchia**: *Aggregate Programming in Kotlin Multiplatform with Collektive*
1. **Martina Baiardi**: *Martina write a title and send me a PR*
1. **Nicolas Farabegoli**: *Davide write a title and send me a PR*
1. **Giovanni Ciatto**: *Giovanni write a title and send me a PR*
1. **Angelo Filaseta**: *Angelo write a title and send me a PR*
1. **Ruslan Shaiakhmetov**: *Closing the gap between reality and simulation in motorsport*
