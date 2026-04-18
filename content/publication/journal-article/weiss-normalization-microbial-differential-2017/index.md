---
title: Normalization and Microbial Differential Abundance Strategies Depend upon Data
  Characteristics

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Sophie Weiss
- Zhenjiang Zech Xu
- Shyamal Peddada
- Amnon Amir
- Kyle Bittinger
- Antonio Gonzalez
- Catherine Lozupone
- Jesse R. Zaneveld
- Yoshiki Vázquez-Baeza
- Amanda Birmingham
- Embriette R. Hyde
- Rob Knight

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2017-01-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2026-04-18T09:04:46.170762Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*Microbiome*'
publication_short: ''

doi: 10.1186/s40168-017-0237-y

abstract: '<b>Background:</b> Data from 16S ribosomal RNA (rRNA) amplicon sequencing
  present challenges to ecological and statistical interpretation. In particular,
  library sizes often vary over several ranges of magnitude, and the data contains
  many zeros. Although we are typically interested in comparing relative abundance
  of taxa in the ecosystem of two or more groups, we can only measure the taxon relative
  abundance in specimens obtained from the ecosystems. Because the comparison of taxon
  relative abundance in the specimen is not equivalent to the comparison of taxon
  relative abundance in the ecosystems, this presents a special challenge. Second,
  because the relative abundance of taxa in the specimen (as well as in the ecosystem)
  sum to 1, these are compositional data. Because the compositional data are constrained
  by the simplex (sum to 1) and are not unconstrained in the Euclidean space, many
  standard methods of analysis are not applicable. Here, we evaluate how these challenges
  impact the performance of existing normalization methods and differential abundance
  analyses.  <b>Results:</b> Effects on normalization: Most normalization methods
  enable successful clustering of samples according to biological origin when the
  groups differ substantially in their overall microbial composition. Rarefying more
  clearly clusters samples according to biological origin than other normalization
  techniques do for ordination metrics based on presence or absence. Alternate normalization
  measures are potentially vulnerable to artifacts due to library size. Effects on
  differential abundance testing: We build on a previous work to evaluate seven proposed
  statistical methods using rarefied as well as raw data. Our simulation studies suggest
  that the false discovery rates of many differential abundance-testing methods are
  not increased by rarefying itself, although of course rarefying results in a loss
  of sensitivity due to elimination of a portion of available data. For groups with
  large (~10×) differences in the average library size, rarefying lowers the false
  discovery rate. DESeq2, without addition of a constant, increased sensitivity on
  smaller datasets (<20 samples per group) but tends towards a higher false discovery
  rate with more samples, very uneven (~10×) library sizes, and/or compositional effects.
  For drawing inferences regarding taxon abundance in the ecosystem, analysis of composition
  of microbiomes (ANCOM) is not only very sensitive (for >20 samples per group) but
  also critically the only method tested that has a good control of false discovery
  rate.  <b>Conclusions:</b> These findings guide which normalization and differential
  abundance techniques to use based on the data characteristics of a given study.'

# Summary. An optional shortened abstract.
summary: ''

tags: []

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# Publication image
# Add an image named `featured.jpg/png` to your page's folder then add a caption below.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects: ['internal-project']` links to `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
