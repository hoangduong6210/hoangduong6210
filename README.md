# Duong Viet Hoang

I work on machine learning for electronic design automation, with an emphasis on geometry-aware graph models and parasitic-aware physical design.

I am currently an M.Sc. student in Computer Science at Da-Yeh University, Taiwan. Before graduate study, I worked on analog/mixed-signal physical design at Synopsys and power-magnetics R&D at Premo. That experience shapes the questions I care about: how to make learned EDA models fast enough for design loops without hiding the physics, solver assumptions, or failure modes.

## Current work

### [Fast parasitic extraction for PCB-embedded planar magnetics](https://github.com/hoangduong6210/pcb-parasitic-gnn)

A pure-PyTorch message-passing model for four lumped parasitics. On the released evaluation, inference takes 1.17 ms. Median errors are 2.8% / 3.8% / 2.6% for `L_p` / `L_s` / `M` against FastHenry and 3.2% for `C_ps` against electrostatic FEM. The repository includes the experiment drivers, result artifacts, negative results, and known limitations.

### [ConfScan](https://github.com/hoangduong6210/Conference-Journal-Management)

A small research tool for finding and comparing conferences and journals from public sources. It provides a Streamlit interface, command-line workflows, exports, and a test suite.

Other public repositories document exploratory graph-learning and reproducibility
work. They are kept separate from the EDA research direction above.

## Research direction

My next step is to move from surrogate prediction to decision-making: parasitic-aware placement, routing, and multi-objective optimization under manufacturability and reliability constraints. I am particularly interested in evaluation protocols that separate interpolation from genuine geometric generalization.

## Contact

- Email: [duongviethuy6210@gmail.com](mailto:duongviethuy6210@gmail.com)
- Location: Taiwan

I welcome technical discussion about ML for EDA, physical design, graph learning, and reproducible evaluation.
