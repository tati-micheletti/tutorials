Overall BAM Modelling Workflow
=====================

Adapted from Peter Solymos' [description](https://github.com/borealbirds/foam/blob/master/README.md).

![BAM Model Workflow](https://github.com/borealbirds/tutorials/blob/master/overall-bam-modelling-workflow/Fig.BAMModelBuildingWorkflow-overall.png  "BAM Model Workflow")


Core BAM modelling approach consists of the following steps
(described in [onomatopoetic](https://en.wikipedia.org/wiki/Onomatopoeia)
words to follow the tradition of the BAM acronym itself):

1. **A**: data processing to create normalized _long_ format tables by integrating various data bases and resources.
2. **B**: estimate detectability (QPAD) offsets based on **Aargh** output.
3. **C**: create a _wide_ formatted and all-inclusive data package based on **A** and **B** for downstream analyses.
4. **D**: model building based on **C** or some subset of it.
5. **E**: summarizing and visualizing model output from **D**
6. **F**: data processing for predicions over a prediction grid/raster by integrating various data bases and resources.
7. **G**: visualizating predictions (maps) and calculating derives summaries of those (population size, trend, uncertainty) based on **D** and **F**.

