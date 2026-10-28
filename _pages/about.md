---
layout: about
title: About
permalink: /
# subtitle: <a href='#'>Affiliations</a>. Address. Contacts. Moto. Etc.

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>Fred Hutchinson Cancer Center</p>
    <p>Seattle, WA USA</p>

news: true  # includes a list of news items
latest_posts: false  # includes a list of the newest posts
selected_papers: true # includes a list of papers marked as "selected={true}"
social: true  # includes social icons at the bottom of the page
---

I develop statistical and machine learning methods to understand cellular regulation from single-cell, spatial, and sequence data. I am a postdoctoral researcher in the [Matsen Lab](https://matsen.fhcrc.org/) at Fred Hutch Cancer Center and the Howard Hughes Medical Institute. My current work combines antibody language models with explicit models of mutation and selection to study B-cell receptor evolution.

I received my PhD in Genomics and Computational Biology and my MA in Statistics and Data Science from the University of Pennsylvania in 2024. I worked with [Junhyong Kim](https://kim.bio.upenn.edu/) and [Nancy Zhang](https://nzhanglab.github.io/) and continued at Penn as a postdoctoral researcher through 2025.

My research connects models of biological variation with models of how assays measure it:

- **Spatial coordination.** [CoPro](https://doi.org/10.64898/2026.04.17.719309) identifies gene programs that vary together across neighboring cells and tissue sections. My [recent theory paper](https://arxiv.org/abs/2610.17830) studies the population targets, identifiability, and stability of spatial kernel restricted canonical correlation analysis.
- **Chromatin accessibility.** [Paired-Insertion Counting (PIC)](https://www.nature.com/articles/s41592-023-02103-7) provides consistent quantification of single-nucleus ATAC-seq data. [PACS](https://www.nature.com/articles/s41467-024-55580-5) tests the effects of multiple biological factors on accessibility while accounting for incomplete capture.
- **Development and disease.** I apply these methods to understand cell-state changes and tissue organization, including kidney development and repair. With collaborators, I helped map the [single-cell regulatory landscape of the mouse kidney](https://www.nature.com/articles/s41467-021-22266-1).

My software is available on [GitHub](https://github.com/Zhen-Miao). You can find my [CV]({{ '/cv/' | relative_url }}) and [publications]({{ '/publications/' | relative_url }}) here.
