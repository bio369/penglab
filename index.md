---
---

# ABOUT US

We are a dynamic research group dedicated to unraveling the mysteries of cellular lineage, the blueprint of life that defines how cells originate, evolve, and function across time and space. Rooted in the fundamental principles of the cell theory, our lab focuses on decoding the precise mechanisms underlying cellular identity, lineage commitment, and fate transitions. By capturing and manipulating the multidimensional information of cell lineages, we aim to uncover the logic of development, disease, aging, and regeneration.


{%
  include button.html
  type="docs"
  link="https://greene-lab.gitbook.io/lab-website-template-docs"
%}
{%
  include button.html
  type="github"
  text="On GitHub"
  link="greenelab/lab-website-template"
%}

{% include section.html %}

## Highlights

{% capture text %}

Our research integrates cutting-edge single-cell multi-omics, lineage tracing, spatial transcriptomics, bioinformatics, artificial intelligence, and organoid technologies. We are driven by the goal to map and model the functional and regulatory dynamics of cells within living systems—from embryos to adult tissues—and to translate these insights into novel strategies for tissue repair, organ reconstruction, and regenerative medicine.

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/research.jpg"
  link="research"
  title="Research"
  text=text
%}

{% capture text %}

Our lab has developed innovative spatial omics methods and generated high-resolution spatiotemporal molecular atlases of post-implantation mouse embryogenesis and brain development. We have uncovered key regulatory networks in pluripotent stem cells and identified novel tissue stem cells with potential for organ regeneration. Our work has been published in leading journals including Nature, Nature Methods, Nature Genetics, Nature Communications, and Cell Reports, and has been recognized among the “Top 10 Advances in Life Sciences in China (2019)” and the “Top 10 Advances in Bioinformatics in China (2019).”

{%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/achievements.jpg"
  link="projects"
  title="Achievements"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  title="Our Team"
  text=text
%}
