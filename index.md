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

Plasma aims at providing an authentic experience of the actual bioinformatic analyses performed in research labs. Jupyter notebooks are used to describe, implement and teach such analyses. These notebooks are interactive numerical notebooks that integrate computer code in several programming languages (Python, R, Bash, C++...), text, mathematical equations and the visualization of analysis results in the form of graphics or tables. This technology is now a standard for data analysis, as evidenced by the millions of notebooks available on the GitHub collaborative development platform.

We also wanted a web-based solution that could be easily deployed on bare-metal servers or virtual machines, able to handle numerous, simultaneous and specific analysis environments (supporting any programming languages), with a simple and intuitive management interface.

This project is carried out in collaboration with [QuantStack](https://quantstack.net/), a company strongly involved in the development of the Jupyter ecosystem. Notebooks are hosted on high-performance computer servers using the JupyterHub open source and highly customizable technology. Students are able to connect remotely and carry out their analysis in a user-friendly and powerful environment. Data are centralized on the servers and readily available for analysis.

The first instance of Plasma was designed for the needs of teachers and students of the [European Master of Genetics](http://www.magisteregenet.univ-paris-diderot.fr/) at Université Paris Cité. It and was fully operational in september 2020. Since then, it has been used by more then 250 life-science and medical students and 20 teachers at Université Paris Cité.

The first stage of this project, Plasma 1.0, was a proof of concept. The implemented solution is fully documented and freely available to the community. It has been already successfully deployed at the [Université de Rouen Normandie](https://www.univ-rouen.fr/) for 1st-year medical students. tljh-repo2docker, the core part of Plasma, is also being used by the [CNAM](https://www.cnam.fr/) for 40 courses reaching more than 1000 students.

Thanks to the success of Plasma 1.0, we are currently expanding the project and we are working on a future version, Plasma 2.0, for massive teaching including an automated management of user accounts and an automatic grading of notebooks. These new developments will notably be implemented for genomics teaching at the [National University of Singapore (NUS)](https://www.nus.edu.sg/).



## PlasmaBio

PlasmaBio is the leading organization of the Plasma project. It is composed of three associate professors at Université Paris Cité:


##### Claire Vandiedonck

- Research interests: genetics of autoimmune and inflammatory diseases, regulation of immune gene expression
- Teaching: human genetics, genomics, biostatistics, bioinformatics for students in medical school and biology department of Université Paris Cité
- <a href="https://twitter.com/CVandiedonck">Twitter</a> ~ <a href="https://github.com/CVandiedonck">GitHub</a>


##### Pierre Poulain

- Research interests: proteomics, molecular dynamics, open data, scientific software development
- Teaching: Python programming, Unix, data management
- <a href="https://twitter.com/pierrepo">Twitter</a> ~ <a href="https://github.com/pierrepo">GitHub</a> ~ <a href="https://cupnet.net">website</a>


##### Sandrine Caburet

- Research interests: genetics of human infertility
- Teaching: genomics, human genetics, bioinformatics
- <a href="https://twitter.com/Scaburet">Twitter</a> ~ <a href="https://github.com/Scaburet">GitHub</a>
  

## Partners

- [QuantStack](https://quantstack.net/) is a team of developers and contributors of major open-source projects for scientific computing, who are passionate about science and technology.
- Greg Tucker-Kellogg, is the director of the Computer Biology Program at the Faculty of Science in [National University of Singapore (NUS)](https://www.nus.edu.sg/).


## Governance

In addition to the leading organization of Plasma, a boarding committee meets twice a year. This board includes a representative of the graduate school on Genetics and Epigenetics [G.E.N.E.](https://eur-gene.u-paris.fr/), an associate professor at [Université Sorbonne Paris Nord](https://en.univ-paris13.fr/), two students at the master and doctoral levels, a representative of the Région Île-de-France, the co-head of the National Network of Computational Resources at the [French Institute of Bioinformatics](https://en.univ-paris13.fr/) and the CEO of our partner [QuantStack](https://quantstack.net/).


## Sponsors

Sponsors to the Plasma initiative include:

- For Plasma 1.0 (2019-2022):

  - [Région Île-de-France](https://twitter.com/iledefrance), via the “Trophées franciliens de l’innovation numérique dans le supérieur” ([EdTech 2018](https://www.iledefrance.fr/trophees-franciliens-de-linnovation-numerique-dans-le-superieur-les-laureats-2018)) grant program,
  - [Université de Paris](https://u-paris.fr/en/), via the [Initiative of Excellence (IdEx) Label](https://u-paris.fr/en/the-initiative-of-excellence-idex-label/) and its "innovating teaching" grant program,
  - [EUR G.E.N.E.](https://eur-gene.u-paris.fr/), the graduate school on Genetics and Epigenetics,
  - the university training "Création, analyse et valorisation de données biologiques omiques" ([DU Omiques](https://omics-school.net/)).

- For Plasma 2.0 (2022-):

  - [Université Paris Cité](https://u-paris.fr/en/), via via the Paris-NUS call for Innovative Projects in Higher Education (2022-2023) - ANR-18-IDEX-0001
  - [National University of Singapore (NUS)](https://www.nus.edu.sg/) via the Paris-NUS call for Innovative Projects in Higher Education (2022-2023) 

The overall budget of the project is 180 k€.


## Developments & achievements

### Plasma

The core of Plasma is [tljh-repo2docker](https://github.com/plasmabio/tljh-repo2docker), a repo2docker plugin for The Littlest JupyterHub.

The first release of Plasma has been released in May 2020: [Plasma: A learning platform powered by Jupyter](https://blog.jupyter.org/plasma-a-learning-platform-powered-by-jupyter-1b850fcd8624).
- code: <https://github.com/plasmabio/plasma>
- documentation: <https://docs.plasmabio.org/>

### Other developments

Beyond the e-learning platform itself, the project includes a number of scientific developments to expand the Jupyter ecosystem in genomics and pedagogy.

#### ipycytoscape

[ipycytoscape](https://github.com/QuantStack/ipycytoscape) brings interactive graph visualization in Jupyter. See also the blog post [Interactive Graph Visualization in Jupyter with ipycytoscape](https://blog.jupyter.org/interactive-graph-visualization-in-jupyter-with-ipycytoscape-a8828a54ab63)

#### ipyigv

[ipyigv](https://github.com/QuantStack/ipyigv) is a Jupyter widget to render genomics data. See also the blog post [Genomic data visualization in Jupyter](https://blog.jupyter.org/genomic-data-representation-in-jupyter-c57a5bb518d6)


### Resources and communication

The Plasma project has been presented in scientific and computer science conferences:

- JupyterCon 2020. [Plasma: versatile e-learning platform powered by The Littlest JupyterHub](https://www.youtube.com/watch?v=0KIMSPTMzVY) (2' video)
- European Society of Human Genetics (ESHG) 2021. [*P17.038.A* Plasma: a versatile e-learning platform for teaching interactively genomic and genetic data analysis with Jupyter notebooks](https://www.nature.com/articles/s41431-021-01026-1#Sec2123)
- Journées Réseaux de l'Enseignement Supérieur (JRES) 2021 (in French). Plasma : plateforme d’e-learning pour l’analyse interactive de données. ([21' vidéo](https://replay.jres.org/w/f1rZTkh84cNimWf4aXHxN1) + [paper](https://hal.archives-ouvertes.fr/hal-03563658)).