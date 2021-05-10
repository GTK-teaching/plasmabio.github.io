---
title: Plasma
feature_text: |
  ## Plasma
  #### e-learning Jupyter-based platform for massive data analysis
feature_image: "/assets/img/background-2462431_Pixabay.jpg"
layout: page
---

Plasma, aka in French "*Plateforme d'eLearning pour l'Analyse de données Scientifiques MAssives*", aims at creating an interactive tool to teach computational analysis of massive scientific data. Plasma was born out of the need to offer a reproducible and high-performance analysis environment to our students.

{% include figure.html image="/assets/img/logo_PLASMA.png" alt="Plasma logo" %}

Our previous experiences of teaching genomics were not satisfying. Because of the limited availability of computational resources, studied samples were restricted to very small datasets, far from what is nowadays routinely analyzed in research labs. Furthermore, remote access to computational resources was not always possible and the user experience provided by the classical Unix terminal was somewhat intimidating for the students.

Plasma aims at providing an authentic experience of the actual bioinformatic analyses performed in research labs. Jupyter notebooks will be used to describe, implement and teach such analyses. These notebooks are interactive numerical notebooks that integrate computer code in several programming languages (Python, R, Bash, C++...), text, mathematical equations and the visualization of analysis results in the form of graphics or tables. This technology is gradually becoming a standard for data analysis, as evidenced by the millions of notebooks available on the GitHub collaborative development platform.

We also wanted a web-based solution that could be easily deployed on bare-metal servers or virtual machines, able to handle numerous, simultaneous and specific analysis environments (supporting any programming languages), with a simple and intuitive management interface.

This project is carried out in collaboration with QuantStack, a company strongly involved in the development of the Jupyter ecosystem. Notebooks will be hosted on high-performance computer servers using the JupyterHub open source and highly customizable technology. Students will be able to connect remotely and carry out their analysis in a user-friendly and powerful environment. Data will be centralized on the servers and readily available for analysis.

The first instance of Plasma is designed for the needs of teachers and students of the [European Master of Genetics](http://www.magisteregenet.univ-paris-diderot.fr/) at Université de Paris.

Ultimately, this project is a proof of concept and the implemented solution is fully documented and freely available to the community.


## PlasmaBio

PlasmaBio is the leading organization of the Plasma project. It is composed of three associate professors at Université de Paris:


##### Claire Vandiedonck

- Research interests: genetics of autoimmune and inflammatory diseases, regulation of immune gene expression
- Teaching: human genetics, genomics, biostatistics, bioinformatics for students in medical school and biology department of Université de Paris
- <a href="https://twitter.com/CVandiedonck">Twitter</a> ~ <a href="https://github.com/CVandiedonck">GitHub</a>


##### Pierre Poulain

- Research interests: isotope labeling in proteomics, scientific software development
- Teaching: Python programming, Unix, proteomics
- <a href="https://twitter.com/pierrepo">Twitter</a> ~ <a href="https://github.com/pierrepo">GitHub</a> ~ <a href="https://cupnet.net">website</a>


##### Sandrine Caburet

- Research interests: genetics of human infertility
- Teaching: genomics, human genetics, bioinformatics
- <a href="https://twitter.com/Scaburet">Twitter</a> ~ <a href="https://github.com/Scaburet">GitHub</a>
  

## Partners

[QuantStack](https://quantstack.net/) is a team of developers and contributors of major open-source projects for scientific computing, who are passionate about science and technology.


## Sponsors

Sponsors to the Plasma initiative include:
- [Région Île-de-France](https://twitter.com/iledefrance), via the “Trophées franciliens de l’innovation numérique dans le supérieur” ([EdTech 2018](https://www.iledefrance.fr/trophees-franciliens-de-linnovation-numerique-dans-le-superieur-les-laureats-2018)) grant program,
- [Université de Paris](https://u-paris.fr/en/), via the [Initiative of Excellence (IdEx) Label](https://u-paris.fr/en/the-initiative-of-excellence-idex-label/) and its "innovating teaching" grant program,
- [EUR G.E.N.E.](https://eur-gene.u-paris.fr/), the graduate school on Genetics and Epigenetics,
- the university training "Création, analyse et valorisation de données biologiques omiques" ([DU Omiques](https://omics-school.net/)).

The overall budget of the project is 140 k€.


## Developments & achievements

### Plasma
- public announcement [Plasma: A learning platform powered by Jupyter](https://blog.jupyter.org/plasma-a-learning-platform-powered-by-jupyter-1b850fcd8624)
- code: <https://github.com/plasmabio/plasma>
- documentation: <https://docs.plasmabio.org/>
- [2' video](https://www.youtube.com/watch?v=0KIMSPTMzVY) of the project presented at JupyterCon 2020

Plasma utilizes [tljh-repo2docker](https://github.com/plasmabio/tljh-repo2docker), a repo2docker plugin for The Littlest JupyterHub


### ipycytoscape

Also part of the Plasma project, the new [ipycytoscape](https://github.com/QuantStack/ipycytoscape) package for interactive graph visualization in Jupyter: <https://blog.jupyter.org/interactive-graph-visualization-in-jupyter-with-ipycytoscape-a8828a54ab63>




