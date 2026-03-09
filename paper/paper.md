---
title: "Taxopy: A Python package for obtaining complete lineages and the lowest common ancestor (LCA) from a set of taxonomic identifiers"
tags:
  - Python
  - biology
  - evolution
  - computational mechanics

authors:
  - name: Antonio Pedro Camargo
    orcid: 0000-0003-3913-2484
    affiliation: "1, 2"
    corresponding: true
  - name: Mateus B. Fiamenghi
    orcid: 0000-0003-4535-8594
    affiliation: 1
    corresponding: true
affiliations:
  - name: DOE Joint Genome Institute, Lawrence Berkeley National Laboratory, Berkeley, United States
    index: 1
  - name: Department of Biochemistry, Institute of Chemistry, University of São Paulo, São Paulo, Brazil
    index: 2
date: 26 February 2026
bibliography: references.bib
---

# Summary

Dobzhansky once famously said, "Nothing in biology makes sense except in the light of evolution". Indeed, without an evolutionary perspective, hypothesis testing of biological systems would be severely limited into simple data analysis. This is especially true in the age of big data, where large datasets of genomic, transcriptomic, and proteomic information are being generated at an unprecedented rate.

Taxonomic classifications provide a framework for organizing this diversity and allow comparative evolutionary studies across different species. However, obtaining complete lineages and the lowest common ancestor (LCA) from a set of taxonomic identifiers has been historically a complex task, especially when dealing with large datasets. Furthermore, there are different standards for taxonomic classification, such as NCBI taxonomy and GTDB (for prokaryotes), which can lead to inconsistencies and difficulties in data integration.

Here we present Taxopy [Taxopy](https://github.com/apcamargo/taxopy), a Python package designed to simplify the process of obtaining taxonomic ranks and lineages by providing an easy-to-use interface for retrieving information from various databases. Taxopy allows users to obtain complete lineages by mapping against taxdump files, a format implemented by several taxonomic databases, either through a numeric identifier, or by using the taxa name. Furthermore, the package contains helper functions to retrieve the LCA from a list of taxonomic identifiers, as well as compute the majority vote when comparing between taxa where a subset is more distantly related. Taxopy is particularly useful for researchers working with large datasets, as it streamlines the process of taxonomic classification and facilitates comparative evolutionary analyses.

# Statement of need

# Acknowledgements

A.P.C wrote the software and revised the manuscript
M.B.F revised the software and wrote the manuscript

# References
