This directory contains all data used to generate figures for the my dual gas sensing project.

- The rscript directory contains code which was used to generate each figure. Each file corresponds to one figure. 

- The raw_data folder contains any raw experimental data. 

- The preprocessed_data folder contains that same data, but formatted in a way that is more convenient to work with. For example, our DAQ system will add a newline and append a new header and a newline to the delim text file each time I save the data. For ease of analysis, I removed these headers. 

- The output folder contains the figures.

### To restore renv from renv.lock file:

- Enter working directory. Run R.

```
renv::restore()

```



