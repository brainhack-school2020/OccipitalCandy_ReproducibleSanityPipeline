# OccipitalCandy_ReproducibleSanityPipeline

## Summary 

I would like to create a pipeline to combine different aspects of MRI data processing and analysis in a way that can be shared easily across labs, with reproducibilty being a primary concern.

## Project definition 

### Background

Working with large, multi-site databases, I found that one of the biggest challenges was organizing the data. The next challenge, was making sure that the data was pre-processed and analyzed in a way that direct comparisons could be made, combining the data for mega or meta-analysis frameworks. Providing all sites with the same tools to use, would have made the process not only easier, but also would have resulted in more reliable data. As large datasets, with data sharing across sites, becaomes increasingly the norm, uhderstanding how to develop the tools that will facilitate this type of research is an essential skill.

### Tools 

For this project, I will concentrate on gaining competencies in the following general areas using the following tools:

  * Datasharing, Open Science
      * BIDS (e.g. Pybids)
      * Github
      * Docker or Singularity
      
  * Streamlining and combining pipelines for multimodal MRI data pre-processing and analysis 
      * Integration (wrapping) of other processing programs to be called within python (e.g. FSL, CAT12)
      * Python (pandas, NumPy , DyPy, etc.) 
      * Parallelization (Nextflow)
      
  * Standaridized visualization pipeline for easy comparison across groups
      * matplotlib  

### Data

Previously collected, preprocessed and analyzed structural and diffusion MRI data will provide the base test dataset to ensure the proper functining of the proprosed scripts.

### Deliverables

At the end of this project, workinig scripts will have been developed, allowing for the processing, anaylsis and visulazation of sMRI and dMRI datasets in a colloberative evironment across multiple sites.

