# Scientific-AI

Datasets for chemistry, proteins, materials, scientific literature, and reaction prediction.

[中文说明](README_ZH.md) | [Back to Home](../README.md)

| # | Dataset | Language | Link | License | Best For | Paper/Docs | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | PubChem | Molecules | [Site](https://pubchem.ncbi.nlm.nih.gov/) | Public domain | Molecular property lookup and cheminformatics pretraining | [Docs](https://pubchem.ncbi.nlm.nih.gov/) | One of the largest public chemistry resources for compounds and assays. |
| 2 | ChEMBL | Molecules | [Site](https://www.ebi.ac.uk/chembl/) | CC BY-SA 3.0 | Bioactivity prediction and drug discovery | [Docs](https://www.ebi.ac.uk/chembl/) | A core medicinal chemistry database used in molecular ML benchmarks. |
| 3 | UniProt | Protein sequences | [Site](https://www.uniprot.org/) | CC BY 4.0 | Protein sequence modeling and annotation | [Docs](https://www.uniprot.org/) | Canonical protein knowledgebase for sequence-centric biological ML. |
| 4 | RCSB PDB | Biomolecular structures | [Site](https://www.rcsb.org/) | CC0 1.0 | Experimental protein structure modeling | [Docs](https://www.rcsb.org/) | The standard public archive for experimentally determined biomolecular structures. |
| 5 | AlphaFold Protein Structure Database | Protein structures | [Site](https://alphafold.ebi.ac.uk/) | CC BY 4.0 | Predicted protein structure retrieval and structural ML | [Docs](https://alphafold.ebi.ac.uk/) | Massive predicted-structure resource widely used after AlphaFold. |
| 6 | PDBBind | Protein-ligand complexes | [Site](http://www.pdbbind.org.cn/) | Custom / registration | Binding affinity prediction | [Docs](http://www.pdbbind.org.cn/) | A long-running benchmark for protein-ligand binding tasks. |
| 7 | Materials Project | Materials structures | [Site](https://materialsproject.org/) | Unknown | Materials property prediction | [Docs](https://materialsproject.org/) | Foundational open database for crystal structures and computed properties. |
| 8 | Open Catalyst 2020 | Atomic structures | [Site](https://opencatalystproject.org/) | CC BY 4.0 | Catalyst surface modeling and adsorption energies | [Docs](https://opencatalystproject.org/) | A major benchmark family for large-scale atomistic learning. |
| 9 | Open Reaction Database | Reactions | [Site](https://open-reaction-database.org/) | CC BY-SA | Reaction prediction and synthesis planning | [Docs](https://open-reaction-database.org/) | Open structured reaction records designed for chemistry ML. |
| 10 | S2ORC | English | [Site](https://allenai.org/data/s2orc) | Mixed / source-specific | Scientific literature pretraining and citation analysis | [Docs](https://allenai.org/data/s2orc) | Large scholarly corpus useful for scientific NLP and retrieval. |
| 11 | ZINC | Molecules | [Site](https://zinc.docking.org/) | Unknown | Molecular generation and virtual screening | [Paper](https://pubs.acs.org/doi/10.1021/acs.jcim.0c00675) | A canonical small-molecule catalog for graph generative modeling and drug-discovery ML. |
| 12 | QM9 | Molecules + 3D structures | [Site](https://figshare.com/collections/Quantum_chemistry_structures_and_properties_of_134_kilo_molecules/978904) | Unknown | Quantum-chemistry property prediction | [Paper](https://www.nature.com/articles/sdata201422) | Still the default small-molecule quantum benchmark in many geometric deep learning papers. |
| 13 | ProteinNet | Protein sequences + structures | [GitHub](https://github.com/aqlaboratory/proteinnet) | Unknown | Protein structure prediction benchmarking | [Paper](https://arxiv.org/abs/1902.00249) | One of the most cited standardized datasets for protein sequence-to-structure learning. |
| 14 | Open Quantum Materials Database (OQMD) | Materials structures | [Site](https://oqmd.org/) | Unknown | Materials discovery and crystal property prediction | [Paper](https://www.nature.com/articles/npjcompumats201510) | A canonical large-scale materials database in computational materials ML. |
| 15 | JARVIS | Materials + atomistic data | [Site](https://jarvis.nist.gov/) | Unknown | Materials property modeling across modalities | [Docs](https://pages.nist.gov/jarvis/databases/) | NIST's open platform is widely used for atomistic, electronic, and materials AI tasks. |
| 16 | CATH | Protein structures | [Site](https://www.cathdb.info/) | CC BY 4.0 | Protein fold and structure classification | [Docs](https://www.cathdb.info/) | A canonical protein structure classification database used in structural biology ML. |
| 17 | BindingDB | Protein-ligand interactions | [Site](https://www.bindingdb.org/rwd/bind/index.jsp) | Unknown | Drug-target interaction and affinity modeling | [Docs](https://www.bindingdb.org/rwd/bind/aboutus.jsp) | One of the canonical public sources for measured binding affinities in drug-discovery ML. |
| 18 | MD17 | Molecules + forces | [Site](https://www.quantum-machine.org/datasets/) | Unknown | Molecular dynamics force-field learning | [Docs](https://www.quantum-machine.org/datasets/) | A default benchmark family for energy-and-force prediction in atomistic ML. |
| 19 | Therapeutics Data Commons | Multimodal therapeutics data | [Site](https://tdcommons.ai/) | Platform / dataset-specific | Unified therapeutics ML tasks and benchmarks | [Paper](https://arxiv.org/abs/2206.08534) | A high-signal platform spanning molecular property prediction, DTI, ADME, toxicity, and generation tasks. |
| 20 | Gene Expression Omnibus (GEO) | Omics / gene expression | [Site](https://www.ncbi.nlm.nih.gov/geo/) | Mixed / submitter-specific | Transcriptomics and functional genomics modeling | [Docs](https://www.ncbi.nlm.nih.gov/geo/info/overview.html) | The canonical public archive for gene-expression and functional-genomics datasets. |
| 21 | Human Cell Atlas | Single-cell omics | [Site](https://data.humancellatlas.org/) | Platform / source-specific | Single-cell representation learning and atlas-scale biology | [Docs](https://www.humancellatlas.org/) | A flagship global resource for single-cell transcriptomics and atlas-scale cell biology data. |
| 22 | Open Targets Platform | Genetics + targets + diseases | [Site](https://platform.opentargets.org/) | Platform / source-specific | Target identification and drug-discovery ML | [Docs](https://platform-docs.opentargets.org/) | Widely used for integrating genetics, disease associations, and evidence-backed target discovery. |
| 23 | STRING Database | Protein interaction networks | [Site](https://string-db.org/) | Unknown | Protein-protein interaction modeling and network biology | [Docs](https://string-db.org/cgi/about) | One of the most widely used public interaction-network resources in systems biology and biological graph learning. |

## Related Benchmarks

- [Benchmarks overview](../Benchmarks/README.md)
- [Therapeutics Data Commons](https://tdcommons.ai/)
- [MoleculeNet](https://moleculenet.org/)
- [Open Catalyst Challenge](https://opencatalystproject.org/challenge)
- [CATH](https://www.cathdb.info/)

## Selection Note

- This page prioritizes datasets and scientific resources that remain common in chemistry, protein, materials, and scientific-document ML papers.
- Large knowledgebases and structured scientific registries are included when they function as the canonical public data source for a field.
