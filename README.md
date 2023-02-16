# Time series analysis of temporal networks

by Kaloyan Danovski [kaloyan.danovski@gmail.com]

The code in this repository was used for the *MFS3 11928 Data Analysis and Machine Learning* project as part of the Master in Physics of Complex Systems at IFISC.

File | Description
---  | ---
`wrangling_arena.ipynb` | transforming 'raw' data into edgelist format (with timesteps and timepoint)
`synthetic.ipynb` | generation and analysis of noisy periodic networks
`tsa.ipynb` | analysis of empirical networks

The `data_sources` folder contains the empirical data in its original format (see below for details on the datasets). The `networks` folder contains the empirical data transformed ("wrangled") into a network edgelist format, as used by the analysis. Most of the plots used in the report are in the notebooks as well.