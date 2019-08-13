This is a tutorial for running the Costerton Biofilm Center version of nf-core/rnaseq pipeline on Computerome

To run the pipeline, you need to initialize the following modules:
```
java/1.8.0 
nextflow/19.03.0-edge 
singularity/3.2.0 
```

You also need to set up a nextflow configuration file at ~/.nextflow/config which contains:

```
singularity {
  enabled = true
  autoMounts = true
 }



