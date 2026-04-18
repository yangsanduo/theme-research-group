---
title: 'Multilign: An Algorithm to Predict Secondary Structures Conserved in Multiple
  RNA Sequences'

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Zhenjiang Zech Xu
- David H. Mathews

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2011-03-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2026-04-18T09:04:46.034529Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*Bioinformatics*'
publication_short: ''

doi: 10.1093/bioinformatics/btq726

abstract: '<b>Motivation:</b> With recent advances in sequencing, structural and functional
  studies of RNA lag behind the discovery of sequences. Computational analysis of
  RNA is increasingly important to reveal structure--function relationships with low
  cost and speed. The purpose of this study is to use multiple homologous sequences
  to infer a conserved RNA structure.  <b>Results:</b> A new algorithm, called Multilign,
  is presented to find the lowest free energy RNA secondary structure common to multiple
  sequences. Multilign is based on Dynalign, which is a program that simultaneously
  aligns and folds two sequences to find the lowest free energy conserved structure.
  For Multilign, Dynalign is used to progressively construct a conserved structure
  from multiple pairwise calculations, with one sequence used in all pairwise calculations.
  A base pair is predicted only if it is contained in the set of low free energy structures
  predicted by all Dynalign calculations. In this way, Multilign improves prediction
  accuracy by keeping the genuine base pairs and excluding competing false base pairs.
  Multilign has computational complexity that scales linearly in the number of sequences.
  Multilign was tested on extensive datasets of sequences with known structure and
  its prediction accuracy is among the best of available algorithms. Multilign can
  run on long sequences ($>$ 1500 nt) and an arbitrarily large number of sequences.  <b>Availability:</b>  The
  algorithm is implemented in ANSI C++ and can be downloaded as part of the RNAstructure
  package at: http://rna.urmc.rochester.edu  <b>Contact:</b> david_mathews@urmc.rochester.edu  <b>Supplementary
  information:</b> Supplementary data are available at Bioinformatics online.'

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
