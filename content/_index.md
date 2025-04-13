---
# Leave the homepage title empty to use the site title
title:
date: 2024-12-12
type: landing

sections:
  - block: hero
    content:
      title: Welcome to the <br> Neuro-COVID dataset.
      image:
        filename: covid_scheme.jpg
      text:

  - block: markdown
    content:
      title:
      text: |
        This is the corresponding website to the publication [Neurological Manifestations of COVID-19 Feature T Cell Exhaustion and Dedifferentiated Monocytes in Cerebrospinal Fluid](https://doi.org/10.1016/j.immuni.2020.12.011) by Heming et al., *Immunity* 2021.
        We present a single cell sequencing dataset of cerebrospinal fluid of patients suffering from COVID-19 with neurological manifestations.
        The raw sequencing are available via [GEO GSE163005](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE163005).

  - block: collection
    id: datasets
    content:
      title: Dataset
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: datasets
    design:
      view: showcase
      columns: '1'
      flip_alt_rows: false

  - block: markdown
    id: contact
    content:
      title: Contact
      text: |
        If you have any questions, please contact us via [mheming.com](https://www.mheming.com).
---
