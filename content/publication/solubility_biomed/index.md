---
title: "Solubility-Aware Protein Binding Peptide Design Using AlphaFold"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Masahito Ohue

# Author notes (optional)
author_notes:
  - ""
  - "Corresponding Author"

date: "2022-07-07T00:00:00Z"
doi: "10.3390/biomedicines10071626"

# Schedule page publish date (NOT publication's date).
# publishDate: "2021-08-13T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: _Biomedicines_
publication_short: _Biomedicines_

abstract: New protein&ndash;protein interactions (PPIs) are identified, but PPIs have different physicochemical properties compared with conventional targets, making it difficult to use small molecules. Peptides offer a new modality to target PPIs, but designing appropriate peptide sequences by computation is challenging. Recently, AlphaFold and RoseTTAFold have made it possible to predict protein structures from amino acid sequences with ultra-high accuracy, enabling de novo protein design. We designed peptides likely to have PPI as the target protein using the &ldquo;binder hallucination&rdquo; protocol of AfDesign, a de novo protein design method using AlphaFold. However, the solubility of the peptides tended to be low. Therefore, we designed a solubility loss function using solubility indices for amino acids and developed a solubility-aware AfDesign binder hallucination protocol. The peptide solubility in sequences designed using the new protocol increased with the weight of the solubility loss function; moreover, they captured the characteristics of the solubility indices. Moreover, the new protocol sequences tended to have higher affinity than random or single residue substitution sequences when evaluated by docking binding affinity. Our approach shows that it is possible to design peptide sequences that can bind to the interface of PPI while controlling solubility.

# Summary. An optional shortened abstract.
summary: Our approach shows that it is possible to design peptide sequences that can bind to the interface of PPI while controlling solubility. Code and easy-to-use environment on Google Colaboratory of solubility-aware AfDesign binder hallucination protocol are available at https://github.com/ohuelab/Solubility_AfDesign
tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.mdpi.com/2227-9059/10/7/1626/pdf'
url_code: 'https://github.com/ohuelab/Solubility_AfDesign'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
