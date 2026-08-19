# Duong Viet Hoang

I am an M.Sc. student in Computer Science at Da-Yeh University, Taiwan, working at the intersection of machine learning, electronic design automation, and scientific computing.

Before graduate study, I worked on analog/mixed-signal physical design at Synopsys and power-magnetics R&D at PREMO. Those experiences motivate my current research: building learning and decision-support methods for expensive electronic-design and physical-simulation workflows, while keeping the underlying assumptions, numerical fidelity, and failure modes visible.

## Selected research

### [Geometry-aware GNNs for parasitic extraction](https://github.com/hoangduong6210/pcb-parasitic-gnn)

A pure-PyTorch research pipeline for predicting four lumped parasitics of PCB-embedded planar-magnetic winding abstractions. The project integrates graph construction, FastHenry and electrostatic FEM workflows, geometry validation, multi-fidelity evidence, and reproducible experiment contracts.

**Current status:** active validation. A post hoc audit quarantined the superseded v2 accuracy results. The replacement v3 corpus contains 1,500 geometry-valid layouts with validated refine-3 FEM artifacts; higher-resolution capacitance validation and the new model evaluation are in progress. The repository makes this evidence boundary explicit and reports no current accuracy headline.

### [Bayesian calibration and sequential design for magnetic-core models](https://github.com/hoangduong6210/EIG-bayesian-for-Recover-potential-Physical-Parameter-of-MagComponent)

An auditable Bayesian workflow for joint calibration of Steinmetz core-loss and Cole--Cole complex-permeability models. It includes MCMC inference, expected information gain, estimator qualification, paired acquisition-policy benchmarks, measured-data model checks, and frozen evidence.

**Main finding:** in the prespecified 30-paired-seed matched-model benchmark, EIG tied predictive variance and Laplace D-optimality on measurement count; its cost-normalized form lost to predictive variance and tied Laplace D-optimality on modeled cost. The result identifies a setting in which cheaper acquisition criteria are sufficient, with the negative finding retained alongside trajectory diagnostics, claim limits, and reproducible evidence.

## Research interests

- Machine learning for EDA and physical design
- Graph representations for circuits, layouts, and electromagnetic structures
- Parasitic-aware optimization and design-space exploration
- Bayesian inference, uncertainty quantification, and sequential experimental design
- Reproducible evaluation of scientific machine-learning systems

## Research practice

My public research repositories separate exploratory records from admitted evidence. They include explicit claim boundaries, versioned protocols, automated validation, and provenance for the numerical results reported in manuscripts and documentation.

## Contact

- Email: [Hoangduong4316@icloud.com](mailto:Hoangduong4316@icloud.com)
- Location: Taiwan

I welcome technical discussion and research collaboration in ML for EDA, graph learning, magnetic-component modeling, and Bayesian experimental design.
