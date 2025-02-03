# Adults hold a causal explanatory framework that connects understanding of other people’s minds, actions and bodies

Heads-up: This repository has been anonymized for peer review.

This repository contains data and scripts for the project "Adults hold a causal explanatory framework that connects understanding of other people’s minds, actions and bodies" by (redacted). If you have any questions about this repository, please contact (redacted).

This is the repository structure and breakdown: 

```
.
├── code
│   ├── codebooks
│   │   └── codebook-generation-scripts
│   ├── study1
│   │   ├── data
│   │   ├── embeddings
│   │   ├── figure
│   │   ├── figures
│   │   ├── snapshots_study1_final_analysis
│   │   └── snapshots_study1_preprocessing_analysis
│   └── study2
│       ├── data
│       └── figures
└── docs
    ├── images
    │   └── items-circles
    ├── jspsych
    │   ├── dist
    │   ├── examples
    │   └── plugin-survey-slider
    └── video

```
## Folder contents

### Code
This folder contains the R analysis scripts for study 1 and study 2. Each study folder contains an `.Rmd` analysis file with a knitted `.html` report, a data subfolder (`/data/`), a figures subfolder with figures used in the manuscript (`/figures/`), and some subfolders containing intermediate files created by the analysis scripts (i.e. `snapshots_study1_preprocessing_analysis` and `snapshots_study1_final_analysis`. 

Feel free to download the repository (button on top right) and look through the files. If you would like to quickly view the analysis reports, you can download just the .html report for the corresponding study, and double-click to open it on your browser (i.e. go to `/code/study1/` and download `/study1_analysis.html`). 

### Docs
This folder contains the experimental stimuli. Both experiments was implemented using jsPsych, and are available at the html files `docs/study1.html`, `docs/study2_inference.html` and `docs/study2_intervention.html`. The `/images`, `video`, and `/jspsych` folders contain supporting materials for the experiments. 

## Supplementary Information
In the home directory is a pdf document containing Supplementary Information for the cogsci paper. 

## Bonus: The analysis pipeline

The following is a flowchart depicting the analysis pipeline:

![pipeline_guide](https://github.com/user-attachments/assets/9b5ee686-98c6-498a-ab1f-ef4730f9041c)

The flowchart above describes the steps in the analysis: The raw experiment data from study 1 (top left, in red) was read into the r markdown pre-processing script, and analyzed. In the process, two csv files were generated, which were passed as inputs to the main analysis script (top right). One csv was generated from this analysis, which was used as an input to the study 2 analysis, alongside a raw data file from the experiment.

Across the two studies, there are 3 analysis scripts, and 5 relevant data csvs. There is a codebook for all 5 data files in the `code/codebooks/` folder. These codebooks consist of knitted `.html` reports generated using the `codebook` package from Arslan (2019), and contain description of the header columns of each dataset. The names of the codebooks correspond to the names of the datasets they describe. All codebooks can be directly downloaded and double-clicked for viewing.

Thank you for accessing these materials!






