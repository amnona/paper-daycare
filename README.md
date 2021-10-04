# paper-daycare
Analysis scripts associated with the day-care microbiome paper

The jupyter notebooks are written for python 3.6 and require [Calour](https://github.com/biocore/calour) and [calour_utils](https://github.com/amnona/calour_utils)

The analysis pipeline begins with the kg-preprocess notebook. Biom table are located in the data/ folder, resulting figures in the figures/ folder and supplementary figures in the supplementary/ folder

## Notebooks description:
* kg-preprocess.ipynb - used to merge the samples from the 2 runs, add taxonomy and normalize/rarify the data.
* age-heatmap.ipynb - create the heatmap for age-dependent ASVs (Fig 1C)
* kg-twins.ipynb - analyse same/different day care age-matched samples (Fig 2A)
* daycare-home.ipynb - compare daycare to homecare matched samples, and draw heatmap and venn diagrams (Fig 3E,F)
* kg-alphadiv.ipynb - the effect of age and daycare vs. homecare on the number of ASVs (Sup Fig S2 A,B,C)
