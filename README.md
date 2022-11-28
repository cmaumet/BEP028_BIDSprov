# BEP028
provenance framework for BIDS
This repository contains **BIDS Extension Proposal 028 : BIDS-prov, a provenance framework for BIDS**

## Our goal
**Interpreting and comparing scientific results** and enabling reusable data and analysis output require understanding provenance, i.e. how the data were generated and processed. To be useful, the provenance must be understandable, easily communicated, and captured automatically in machine accessible form. Provenance records are thus used to encode transformations between digital objects

### Who is building BEP 028

Camille Maumet ([@cmaumet](https://github.com/cmaumet)) and Satrajit Ghosh ([@satra](https://github.com/satra)) are the BEP co-moderators.

List of all contributors

- Camille Maumet ([@cmaumet](https://github.com/cmaumet))
- Satrajit Ghosh ([@satra](https://github.com/satra))
- Stefan Appelhoff ([@sappelhoff](https://github.com/sappelhoff))
- Chris Markiewicz ([@effigies](https://github.com/effigies))
- Yaroslav Halchenko ([@yarikoptic](https://github.com/yarikoptic))
- Jean-Baptiste Poline ([@jbpoline](https://github.com/jbpoline))
- Rémi Adon ([@remiadon](https://github.com/remiadon))

### BIDS-prov in the NIDM project

The Neuroimaging Data Model (NIDM) is a collection of specification documents that define extensions the `W3C PROV` standard for the domain of human brain mapping

<p align="center">
  <img width="50%" src="img/nidm-layer-cake.png">
</p>

BIDS-prov is a BIDS extension that is compatible with NIDM.



## How to help
[Our goal](#our-goal) is to extends BIDS to be able to track provenance at every stage of an experiment.

For this purpose we have to **propose changes to the BIDS specification**

The BIDS specification is *rendered* as a webpage at https://bids-specification.readthedocs.io.

The website is built from a GitHub repository that consists of mostly markdown files at https://github.com/bids-standard/bids-specification.
If you don't know much about markdown, here's a [good intro guide](https://guides.github.com/features/mastering-markdown/)

The file that you are most likely to propose changes to is [src/03-modality-agnostic-files.md](https://github.com/bids-standard/bids-specification/blob/master/src/03-modality-agnostic-files.md), although there may be additional changes that have to happen in other pars of the repository


## Finding information and getting in touch

### Google doc
The BEP028 is in a [google doc](https://docs.google.com/document/d/1vw3VNDof5cecv2PkFp7Lw_pNUTUo8-m8V4SIdtGJVKs/edit?usp=sharing)

### BIDS-Prov calls
We meet every two weeks by videoconference on Mondays at 7-8am PDT / 10am-11am EDT / 3-4pm BST. The group is always open to new contributors interested in neuroimaging data sharing. To join the call or to ask any question, please email us at incf-nidash-nidm@googlegroups.com.  

## Additional resources
Mature building blocks of NIDM:
* [NIDM-terms](https://github.com/incf-nidash/nidm-terms)
* [NIDM-results](http://nidm.nidash.org/specs/nidm-results_130.html)


[New features (to be included)](new_features.md)


## Code of conduct
We are committed to building a welcoming and harrasement free experience for all our contributors. As a contributor to the BIDS-Prov specification, we ask you to follow our [code of conduct](code_of_conduct.md)


_Credits: This README was build based on the [BEP001 README](https://github.com/bids-standard/bep001/blob/master/README.md)._
