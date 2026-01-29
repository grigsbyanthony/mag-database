# MAG Database Explorer

A searchable, static web interface for exploring metagenome-assembled genomes (MAGs) from human decomposition research.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) ![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-222222?style=flat&logo=github&logoColor=white) ![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)

------

## About

This database provides an interactive interface to explore **277 MAGs** across **569 samples** with **649 metabolic genes** annotated. The site is designed as a static, client-side application suitable for hosting on GitHub Pages.

### Features

- **Taxonomy Browser** — Search and filter MAGs by taxonomic classification
- **Abundance Profiles** — Visualize MAG distribution across samples
- **Metabolism Summary** — Explore metabolic pathway annotations and gene presence/absence
- **Methodology** — Understand the experimentation, processing and analyses that went into this dataset

------

## Data Source

Data derived from:

> Burcham, Z.M., Belk, A.D., McGivern, B.B. *et al.* A conserved interdomain microbial network underpins cadaver decomposition despite environmental variables. *Nat Microbiol* **9**, 595–613 (2024).
>  https://doi.org/10.1038/s41564-023-01580-y

The MAG library was generated from soils associated with 36 human cadavers at three U.S. anthropological research facilities spanning temperate and semi-arid climates. The study identified a universal microbial decomposer network with applications in forensic science for estimating postmortem interval.

------

## Structure

```bash
mag-database/
├── index.html          
├── README.md
├── favicon.ico
└── data/
    ├── taxonomy_data.json
    ├── abundance_data.json
    ├── metabolism_data.json
    ├── pathway_summary.json
    ├── sample_names.json
    └── metabolic_headers.json
```

------

## License

MIT License. See [LICENSE](https://claude.ai/chat/LICENSE) for details.

Data usage should cite the original publication (Burcham *et al.*, 2024).