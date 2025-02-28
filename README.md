# fraser-pinks
Fraser River pink salmon spawner recruitment analysis with state-space model to account for time varying observation error in estimates of spawning escapement and harvest. The ultimate goal of analysis is to derive biological benchmarks to inform a Limit Reference Point for the Stock Management Unit and associated harvest control rule. The current working document is available [here](https://pacific-salmon-assess.github.io/fraser-pinks/doc/tech-memo.html).

If you want to tinker with the analysis, begin by cloning the repo then run [fit-sr-stan.R](https://github.com/Pacific-salmon-assess/fraser-pinks/blob/main/analysis/fit-sr-stan.R) to generate model outputs befor running/knitting the [tech-memo document](https://github.com/Pacific-salmon-assess/fraser-pinks/blob/main/doc/tech-memo.Rmd).  

## Folders and files
- `reproduce.R`: source to load required libraries and reproduce analysis
- `data`: Data model is fit to
- `analysis`: Code to fit state-space spawner recruit model in Stan
- `document`: Code to render Rmd summary of data sources, model structure and fitting, and inference
- `misc`: Bits and pieces of original files provided with a summary of methods that describes why certain CVs were chosen for observation errors.   
