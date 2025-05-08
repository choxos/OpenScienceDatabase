# Open Science Best Practices

## Table of Contents
- [Introduction](#introduction)
- [Preprint Servers](#preprint-servers)
- [Protocol Sharing](#protocol-sharing)
- [Data Sharing](#data-sharing)
  - [FAIR Principles](#fair-principles)
- [Code Sharing](#code-sharing)
- [Licenses](#licenses)
- [Conclusion](#conclusion)

## Introduction

Open science represents a movement to make scientific research, data, and dissemination accessible to all levels of society, from researchers to citizens. By promoting transparency and collaboration, open science accelerates scientific progress, enhances reproducibility, and democratizes access to knowledge. This document outlines best practices across key dimensions of open science, providing researchers with practical guidance to make their work more open, accessible, and impactful.

## Preprint Servers

### What are Preprint Servers?

Preprint servers are online platforms where researchers can share manuscript drafts before they undergo formal peer review and publication in traditional journals. By depositing preprints, researchers can:

- Rapidly disseminate findings, accelerating scientific progress
- Establish priority for discoveries
- Receive early feedback from a broader community
- Make research accessible to all, regardless of journal subscription status
- Create a permanent, citable record of their work at an early stage

Preprints have become an essential component of open science, particularly in fields where rapid communication of results is crucial, such as during public health emergencies.

### Available Preprint Servers

| Server | Disciplines | Features | File Types | DOI Provided | Moderation Level |
|--------|------------|----------|------------|--------------|------------------|
| [arXiv](https://arxiv.org/) | Physics, Mathematics, Computer Science, Quantitative Biology, Quantitative Finance, Statistics, Electrical Engineering, Economics | Comments, versions tracking, API | PDF | Yes (via CrossRef) | Basic screening |
| [bioRxiv](https://www.biorxiv.org/) | Biology | Commenting, versions, transfer to journals | PDF | Yes (via CrossRef) | Content screening |
| [medRxiv](https://www.medrxiv.org/) | Medicine, Clinical research | Similar to bioRxiv, journal transfer | PDF | Yes | Strict screening |
| [ChemRxiv](https://chemrxiv.org/) | Chemistry, Chemical Engineering | Metrics, journal transfer | PDF | Yes (via DataCite) | Content screening |
| [PsyArXiv](https://psyarxiv.com/) | Psychology | Commenting, metrics, versioning | PDF | Yes (via OSF) | Basic screening |
| [SocArXiv](https://osf.io/preprints/socarxiv) | Social Sciences | Commenting, versioning | PDF | Yes (via OSF) | Basic screening |
| [EarthArXiv](https://eartharxiv.org/) | Earth Sciences | Commenting, versioning | PDF | Yes | Moderate screening |
| [EcoEvoRxiv](https://ecoevorxiv.org/) | Ecology, Evolution, Conservation | Commenting, metrics | PDF | Yes | Moderate screening |
| [EngrXiv](https://engrxiv.org/) | Engineering | Community feedback | PDF | Yes | Basic screening |
| [ESSOAr](https://www.essoar.org/) | Earth and Space Sciences | Journal transfer, commenting | PDF | Yes | Moderate screening |
| [LawArXiv](https://osf.io/preprints/lawarxiv) | Legal Studies | Commenting | PDF | Yes (via OSF) | Basic screening |
| [MetaArXiv](https://osf.io/preprints/metaarxiv/) | Meta-science, Research Methods | Commenting | PDF | Yes (via OSF) | Basic screening |
| [MindRxiv](https://mindrxiv.org/) | Mind and Contemplative Sciences | Commenting | PDF | Yes | Basic screening |
| [SportRxiv](https://sportrxiv.org/) | Sports science, Exercise science | Commenting | PDF | Yes | Basic screening |
| [AfricArXiv](https://info.africarxiv.org/) | All disciplines (focus on African research) | Multilingual, commenting | PDF | Yes | Moderate screening |
| [Research Square](https://www.researchsquare.com/) | All disciplines | Commenting, journal transfer, integrity checks | PDF | Yes | Advanced screening |
| [SSRN](https://www.ssrn.com/) | Social Sciences, Economics, Law | Analytics, discipline-specific networks | PDF | No (uses own ID system) | Moderate screening |
| [Preprints.org](https://www.preprints.org/) | All disciplines | Commenting, versioning, metrics | PDF | Yes (via Crossref) | Moderate screening |
| [OSF Preprints](https://osf.io/preprints/) | All disciplines | Commenting, project integration | PDF | Yes | Basic screening |
| [HAL](https://hal.science/) | All disciplines (popular in France) | Versioning, metadata | Multiple | Yes | Basic screening |
| [Zenodo](https://zenodo.org/) | All disciplines | Dataset integration, versioning | Multiple | Yes (via DataCite) | Minimal screening |

## Protocol Sharing

### Why Share Protocols?

Scientific protocols are detailed procedures for experiments, data collection, or analysis. Sharing protocols enhances:

- Reproducibility: Other researchers can replicate studies with the same methods
- Transparency: The scientific community can evaluate the methodology's rigor
- Efficiency: Researchers can build upon established, validated procedures
- Education: Students and early-career scientists can learn standardized techniques
- Collaboration: Research teams can harmonize methods across sites or studies

Detailed protocols fill the gap between the abbreviated methods sections in published papers and the practical knowledge needed to successfully implement techniques.

### Protocol Sharing Platforms

| Platform | Features | Disciplines | Peer Review | DOI/Citation | Integration |
|----------|----------|-------------|------------|--------------|-------------|
| [protocols.io](https://www.protocols.io/) | Version control, collaborative editing, DOI assignment, reagent linking, video embedding | All life sciences | Optional community review | Yes | GitHub, ORCID |
| [Protocol Exchange (Nature)](https://protocolexchange.researchsquare.com/) | Direct submission from Nature journals, community commenting | Life sciences | No formal review | Yes | Nature journals |
| [JoVE (Journal of Visualized Experiments)](https://www.jove.com/) | Video protocols, professional production | Multiple disciplines | Formal peer review | Yes | PubMed |
| [Bio-protocol](https://bio-protocol.org/) | Detailed step-by-step protocols | Biology | Formal peer review | Yes | PubMed, CrossRef |
| [Current Protocols](https://currentprotocols.onlinelibrary.wiley.com/) | Expert-written, regularly updated | Life sciences | Formal peer review | Yes | Wiley journals |
| [STAR Protocols (Cell Press)](https://www.cell.com/star-protocols/home) | Structured transparency, reproducibility | Life sciences | Formal peer review | Yes | Cell Press journals |
| [MethodsX](https://www.journals.elsevier.com/methodsx) | Method modifications and improvements | All disciplines | Peer reviewed | Yes | Elsevier journals |
| [Open Science Framework (OSF)](https://osf.io/) | Protocol registration, materials sharing | All disciplines | No formal review | Yes | Many integrations |
| [Protocol Registry](https://www.protocols.io/registry) | Searchable index of published protocols | Life sciences | No | Yes | Multiple |
| [Zenodo](https://zenodo.org/) | Repository for protocols and materials | All disciplines | No | Yes | GitHub, ORCID |
| [Science Exchange](https://www.scienceexchange.com/) | Experimental services and protocols | Life sciences | Vendor validation | No | CRO/service providers |
| [Benchling](https://www.benchling.com/) | Molecular biology protocols, inventory | Life sciences | No | No | Lab notebooks |
| [GitHub](https://github.com/) | Version control for computational protocols | Computational sciences | No formal review | No direct DOI | Many integrations |
| [Addgene](https://www.addgene.org/protocols/) | Molecular biology protocols | Life sciences | Basic verification | No | Reagent repository |
| [Berkeley Protocol Collection](https://mcb.berkeley.edu/labs/krantz/mcb112/protocols.html) | Teaching protocols | Molecular biology | Faculty reviewed | No | Educational |

## Data Sharing

### The Importance of Data Sharing

Data sharing is a cornerstone of open science, providing numerous benefits to the scientific community and broader society:

- Validation: Enables verification of published findings
- Reuse: Allows data to be analyzed in new ways or combined with other datasets
- Efficiency: Reduces duplication of effort in data collection
- Collaboration: Facilitates cross-disciplinary and international research
- Impact: Increases citation rates and research visibility
- Education: Provides real-world datasets for teaching and learning
- Value: Maximizes return on research investment
- Transparency: Builds public trust in scientific findings

Despite these benefits, data sharing faces challenges including privacy concerns, competitive disadvantages, lack of infrastructure, and insufficient recognition for data creators. The FAIR principles (discussed below) aim to address these challenges.

### FAIR Principles

The FAIR principles provide guidelines to improve the **F**indability, **A**ccessibility, **I**nteroperability, and **R**eusability of digital assets. Developed in 2016, these principles have become a cornerstone of open science data practices:

#### Findable
- Data should be easy to discover by both humans and machines
- Requires rich metadata, unique and persistent identifiers (PIDs)
- Data should be indexed in searchable resources
- Example practices: Using DOIs, rich descriptive metadata, registering in repositories

#### Accessible
- Data should be retrievable using standardized protocols
- Authentication and authorization procedures should be clear
- Metadata should remain accessible even when data is not
- Example practices: HTTP/FTP access, clear licensing, preservation planning

#### Interoperable
- Data should use formal, accessible, shared, and broadly applicable languages
- Vocabularies should follow FAIR principles
- Include qualified references to other data
- Example practices: Using standard formats (CSV, JSON), controlled vocabularies, ontologies

#### Reusable
- Clear and accessible data usage licenses
- Detailed provenance information
- Meet domain-relevant community standards
- Example practices: Using standard licenses, detailed documentation, following field-specific standards

Implementing FAIR principles is not binary but exists on a spectrum. Tools like the [FAIR Evaluation Service](https://fairsharing.github.io/FAIR-Evaluator-FrontEnd/) can help assess dataset FAIRness.

### Data Repositories and Sharing Platforms

| Repository | Disciplines | Storage Limit | Features | Cost | DOI Provided | FAIR Compliance |
|------------|-------------|---------------|----------|------|--------------|-----------------|
| [Zenodo](https://zenodo.org/) | All | 50GB per dataset | Versioning, GitHub integration, communities | Free (larger deposits negotiable) | Yes | High |
| [Dryad](https://datadryad.org/) | All | No fixed limit | Curation, journal integration | $120 per dataset (waivers available) | Yes | High |
| [Figshare](https://figshare.com/) | All | 5GB per file, unlimited files | Private/public spaces, metrics | Free for individuals | Yes | High |
| [Harvard Dataverse](https://dataverse.harvard.edu/) | All | No fixed limit | Versioning, customizable metadata | Free | Yes | High |
| [Open Science Framework (OSF)](https://osf.io/) | All | 5GB per file, 50GB per project | Project management, collaboration | Free | Yes | High |
| [NCBI GEO](https://www.ncbi.nlm.nih.gov/geo/) | Genomics | No fixed limit | Integration with other NCBI resources | Free | No (uses accession numbers) | High |
| [European Nucleotide Archive](https://www.ebi.ac.uk/ena/) | Genomics | No fixed limit | Standardized submission | Free | No (uses accession numbers) | High |
| [Gene Expression Omnibus (GEO)](https://www.ncbi.nlm.nih.gov/geo/) | Genomics | No fixed limit | Data analysis tools | Free | No (uses accession numbers) | High |
| [ArrayExpress](https://www.ebi.ac.uk/arrayexpress/) | Functional genomics | No fixed limit | Cross-references to other databases | Free | No (uses accession numbers) | High |
| [Protein Data Bank (PDB)](https://www.rcsb.org/) | Structural biology | NA | Visualization tools, validation | Free | No (uses accession numbers) | High |
| [OpenNeuro](https://openneuro.org/) | Neuroscience | 5TB | BIDS-compliant, analysis pipelines | Free | Yes | High |
| [ICPSR](https://www.icpsr.umich.edu/) | Social sciences | No fixed limit | Curation, restricted access options | Free to affiliated institutions | Yes | High |
| [UK Data Service](https://ukdataservice.ac.uk/) | Social sciences | No fixed limit | Training, controlled access levels | Free | Yes | High |
| [GenBank](https://www.ncbi.nlm.nih.gov/genbank/) | Genetic sequences | No fixed limit | Integration with other NCBI resources | Free | No (uses accession numbers) | High |
| [NASA Earth Data](https://earthdata.nasa.gov/) | Earth sciences | No fixed limit | Analysis tools, visualization | Free | Yes | High |
| [PANGAEA](https://www.pangaea.de/) | Earth & environmental sciences | No fixed limit | Georeferencing, visualization | Free | Yes | High |
| [Mendeley Data](https://data.mendeley.com/) | All | 10GB per dataset | Private/public options, versioning | Free | Yes | Medium-High |
| [CERN Open Data Portal](http://opendata.cern.ch/) | Particle physics | No fixed limit | Analysis tools, documentation | Free | Yes | High |
| [Synapse](https://www.synapse.org/) | Biomedical | No fixed limit | Collaborative features, controlled access | Free | Yes | High |
| [NIH Common Fund Data Ecosystem](https://nih-cfde.org/) | Biomedical | Varies by program | Integrated search across datasets | Free | Varies | High |
| [Google Dataset Search](https://datasetsearch.research.google.com/) | All (search engine) | NA | Discovery of datasets across repositories | Free | No | NA (discovery tool) |
| [DANS EASY](https://easy.dans.knaw.nl/) | All (focus on Netherlands) | No fixed limit | Long-term preservation | Free for academic use | Yes | High |
| [4TU.ResearchData](https://data.4tu.nl/) | Engineering, technical sciences | 1TB (more negotiable) | Preservation focus | Free for contributing institutions | Yes | High |
| [SEANOE](https://www.seanoe.org/) | Marine science | 10GB (more negotiable) | Embargo options | Free | Yes | High |

## Code Sharing

### The Value of Sharing Scientific Code

Sharing the code used in research is essential for computational reproducibility and has become a fundamental aspect of open science:

- Reproducibility: Enables others to recreate analyses exactly
- Transparency: Shows the exact implementation of methods and algorithms
- Collaboration: Allows others to build upon and improve methods
- Quality: Encourages better coding practices through public scrutiny
- Credit: Provides recognition for software development in science
- Sustainability: Helps maintain code beyond single projects or individuals
- Education: Teaches real-world scientific computing practices

Code sharing complements data sharing and protocol publication to create a complete picture of scientific methodology. Many journals and funders now require or strongly encourage code availability.

### Code Sharing Platforms

| Platform | Focus | Features | Integration | DOI/Citation | Private Repositories | Cost |
|----------|-------|----------|-------------|--------------|----------------------|------|
| [GitHub](https://github.com/) | General code hosting | Version control, issue tracking, pull requests, pages | Many | Via Zenodo integration | Yes (unlimited for academia) | Free for public/basic, paid tiers |
| [GitLab](https://gitlab.com/) | DevOps platform | CI/CD, project management, security | Many | Via Zenodo integration | Yes | Free for public/basic, paid tiers |
| [Bitbucket](https://bitbucket.org/) | Code collaboration | CI/CD, Jira integration | Atlassian products | No direct DOI | Yes | Free for small teams, paid tiers |
| [Zenodo](https://zenodo.org/) | Research outputs | Long-term preservation, GitHub integration | GitHub | Yes | Yes | Free |
| [Software Heritage](https://www.softwareheritage.org/) | Software preservation | Long-term archiving, universal identifiers | Many | Yes (SWHID) | No | Free |
| [Code Ocean](https://codeocean.com/) | Computational reproducibility | Containerization, cloud compute, published capsules | Many | Yes | Yes | Free tier, paid options |
| [Gigantum](https://gigantum.com/) | Data science environment | Environment packaging, versioning | GitHub | No | Yes | Free tier, paid options |
| [Binder/MyBinder](https://mybinder.org/) | Interactive notebooks | Run Jupyter notebooks from repositories | GitHub, GitLab | No | No | Free |
| [Open Science Framework (OSF)](https://osf.io/) | Project management | Integrated with storage providers | Many | Yes | Yes | Free |
| [Jupyter Notebook Viewer](https://nbviewer.jupyter.org/) | Notebook rendering | Static display of notebooks | GitHub, URLs | No | No | Free |
| [Renku](https://renkulab.io/) | Reproducible workflows | Knowledge graph, environment management | GitLab | Yes | Yes | Free |
| [DagsHub](https://dagshub.com/) | ML workflow | Data versioning, model registry, experiments | GitHub | No | Yes | Free for public, paid for private |
| [CyVerse](https://cyverse.org/) | Life sciences computing | Data storage, analysis, visualization | Many | Yes (via DOI service) | Yes | Free |
| [Whole Tale](https://wholetale.org/) | Computational narratives | Interactive computing, preservation | Many | Yes | Yes | Free |
| [CERN Gitlab](https://gitlab.cern.ch/) | Physics, HEP | Standard GitLab with CERN authentication | CERN services | No direct DOI | Yes | Free for CERN |
| [institutional repositories](https://v2.sherpa.ac.uk/opendoar/) | Various | Varies by institution | Varies | Usually yes | Varies | Usually free for affiliates |

## Licenses

### Why Licensing Matters in Open Science

Licensing is a critical but often overlooked aspect of open science. Without clear licensing, the legal default is "all rights reserved," which can prevent others from using, modifying, or redistributing research outputs—even when shared publicly. Proper licensing:

- Clarifies permissions: Explicitly states what others can and cannot do with your work
- Enables reuse: Legally allows others to build upon your research
- Protects attribution: Ensures you receive credit for your work
- Sets expectations: Communicates your intentions regarding reuse
- Promotes sustainability: Ensures work remains available even if platforms change
- Supports reproducibility: Allows methods, data, and code to be freely examined and reused
- Prevents legal ambiguity: Reduces uncertainty about permissible uses

Different types of research outputs (papers, data, code, materials) may require different licenses to best serve open science goals.

### Open Science Compatible Licenses

#### For Publications and Documentation

| License | Openness Level | Permissions | Attribution Required | Commercial Use | Derivative Works | Notable Features |
|---------|---------------|-------------|---------------------|----------------|------------------|------------------|
| [CC0 (Public Domain Dedication)](https://creativecommons.org/publicdomain/zero/1.0/) | Highest | No restrictions | No | Yes | Yes | Waives all rights, closest to public domain |
| [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) | Very High | Use, share, adapt | Yes | Yes | Yes | Most permissive with attribution requirement |
| [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) | High | Use, share, adapt | Yes | Yes | Yes (with share-alike) | Ensures derivatives remain open (copyleft) |
| [CC BY-ND 4.0](https://creativecommons.org/licenses/by-nd/4.0/) | Medium | Use, share | Yes | Yes | No | Prevents modification, less open science compatible |
| [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/) | Medium | Use, share, adapt (non-commercial) | Yes | No | Yes | Limits commercial use, less open science compatible |
| [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) | Medium-Low | Use, share, adapt (non-commercial) | Yes | No | Yes (with share-alike) | Combines non-commercial and share-alike |
| [CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/) | Low | Use, share (non-commercial) | Yes | No | No | Most restrictive CC license, not ideal for open science |

**Most Open Science Compatible: CC0, CC BY**

#### For Software and Code

| License | Openness Level | Permissions | Attribution Required | Patent Grant | Copyleft | Notable Features |
|---------|---------------|-------------|---------------------|-------------|----------|------------------|
| [MIT License](https://opensource.org/licenses/MIT) | Very High | Use, modify, distribute | Yes | No | No | Simple, permissive, widely used |
| [Apache 2.0](https://opensource.org/licenses/Apache-2.0) | Very High | Use, modify, distribute | Yes | Yes | No | Includes patent grant, good for corporate use |
| [BSD 3-Clause](https://opensource.org/licenses/BSD-3-Clause) | Very High | Use, modify, distribute | Yes | No | No | Similar to MIT, but with non-endorsement clause |
| [BSD 2-Clause](https://opensource.org/licenses/BSD-2-Clause) | Very High | Use, modify, distribute | Yes | No | No | Simpler version of BSD 3-Clause |
| [GNU GPL v3](https://www.gnu.org/licenses/gpl-3.0.en.html) | High | Use, modify, distribute | Yes | Yes | Yes (strong) | Ensures derivatives stay open source |
| [GNU LGPL v3](https://www.gnu.org/licenses/lgpl-3.0.en.html) | High | Use, modify, distribute | Yes | Yes | Yes (weak) | Allows linking with non-open software |
| [Mozilla Public License 2.0](https://www.mozilla.org/en-US/MPL/2.0/) | High | Use, modify, distribute | Yes | Yes | Yes (file-level) | File-level copyleft, compatible with GPL |
| [GNU AGPL v3](https://www.gnu.org/licenses/agpl-3.0.en.html) | High | Use, modify, distribute | Yes | Yes | Yes (strongest) | Covers network use, strongest copyleft |
| [Unlicense](https://unlicense.org/) | Highest | Use, modify, distribute | No | No | No | Public domain dedication for code |

**Most Open Science Compatible: MIT, Apache 2.0, BSD licenses for maximum reuse; GPL family for ensuring derivatives remain open**

#### For Data

| License | Openness Level | Permissions | Attribution Required | Commercial Use | Share-Alike | Notable Features |
|---------|---------------|-------------|---------------------|----------------|-------------|------------------|
| [CC0](https://creativecommons.org/publicdomain/zero/1.0/) | Highest | No restrictions | No | Yes | No | Recommended for most scientific data |
| [PDDL (Open Data Commons)](https://opendatacommons.org/licenses/pddl/) | Highest | No restrictions | No | Yes | No | Similar to CC0, specifically for data |
| [ODC-BY](https://opendatacommons.org/licenses/by/) | Very High | Use, share, adapt | Yes | Yes | No | Similar to CC BY, specifically for data |
| [ODC-ODbL](https://opendatacommons.org/licenses/odbl/) | High | Use, share, adapt | Yes | Yes | Yes | Share-alike provision for databases |
| [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) | Very High | Use, share, adapt | Yes | Yes | No | Works well for data, widely recognized |

**Most Open Science Compatible: CC0, PDDL for maximum reuse; ODC-BY or CC BY if attribution is important**

### Licensing Recommendations for Open Science

For truly open science, consider these best practices:

1. **Publications**: Use CC BY or CC0
   - Enables maximum reuse while ensuring attribution
   - Complies with most open access journal and funder requirements
   - Facilitates text and data mining

2. **Code**: Use MIT, Apache 2.0, or BSD
   - Permissive licenses enable widest adoption
   - Consider GPL family if you want to ensure derivatives remain open
   - Include a CITATION file to specify how users should cite your code

3. **Data**: Use CC0 or PDDL
   - Facts themselves are not copyrightable (in many jurisdictions)
   - Attribution can be required through community norms rather than legal terms
   - Simplifies data integration from multiple sources

4. **Protocols and Methods**: Use CC BY
   - Ensures attribution while allowing adaptation
   - Facilitates translation and improvement

5. **General Recommendations**:
   - Choose the least restrictive license that meets your needs
   - Consider compatibility between licenses if combining works
   - Clearly display license information with your work
   - Include a plain-language summary of permissions
   - Consider providing citation information separate from licensing

## Conclusion

Open science practices are transforming research through increased transparency, collaboration, and accessibility. By adopting the comprehensive approaches detailed in this guide—sharing preprints, protocols, data according to FAIR principles, code, and using appropriate open licenses—researchers can maximize their work's impact, accelerate scientific progress, and contribute to a more inclusive scientific ecosystem.

The transition to open science requires both individual commitment and systemic change. While individual researchers can implement many of these practices immediately, institutional support, funder mandates, and recognition systems that reward openness are equally important for sustaining this transformation.

By following these best practices, you contribute not only to the advancement of your field but also to a broader cultural shift toward science that is more collaborative, efficient, and accessible to all.
