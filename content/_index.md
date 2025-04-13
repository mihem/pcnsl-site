---
# Leave the homepage title empty to use the site title
title:
date: 2024-12-12
type: landing

sections:
  - block: hero
    content:
      title: Welcome to the <br> PCNSL dataset.
      image:
        filename: manuscript_scheme.png
      text:

  - block: markdown
    content:
      title:
      text: |
        This is the corresponding website to the publication [Intratumor heterogeneity and T cell exhaustion in primary CNS lymphoma](https://doi.org/10.1186/s13073-022-01110-1) by Heming et al., *Genome Medicine* 2022.
        We present single cell RNA-sequencing data of biopsy fluid, blood and CSF from patients with primary CNS B cell lymphoma.
        The raw sequencing are available via [GEO GSE203552](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE203552).

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
