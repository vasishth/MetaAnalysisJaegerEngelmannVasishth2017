# MetaAnalysisJaegerEngelmannVasishth2017
Code and data to accompany the article by 


    Jaeger, Engelmann, Vasishth  (2017). 
	Similarity-based interference in sentence comprehension: 
	Literature review and Bayesian meta-analysis. 
	Journal of Memory and Language. [doi](10.1016/j.jml.2017.01.004)



# Directory structure 

  data

  contains summary stats used in meta-analysis 

  inst
  
  contains a purl'd output from paper, all code chunks that were in the paper
 
 R 
 
 R functions for paper				

 StanModels
 
 code for random effects meta-analysis
	
 documentation
 
 description of data extraction procedure

 vignettes
 
 Rmd and html files containing (hopefully!) reproducible code


# SessionInfo

If something doesn't work, please check that there isn't any problem with version differences in packages. 


	R version 3.3.2 (2016-10-31)
	Platform: x86_64-apple-darwin13.4.0 (64-bit)
	Running under: macOS Sierra 10.12

	locale:
	[1] en_US.UTF-8/en_US.UTF-8/en_US.UTF-8/C/en_US.UTF-8/en_US.UTF-8

	attached base packages:
	[1] grid      parallel  stats     graphics  grDevices utils     datasets 
	[8] methods   base     

	other attached packages:
	[1] xtable_1.8-2       rjags_4-6          coda_0.18-1       
	[4] dplyr_0.4.3        rstan_2.14.1       StanHeaders_2.14.0
	[7] ggplot2_2.2.0     

	loaded via a namespace (and not attached):
	 [1] Rcpp_0.12.8      knitr_1.15.1     magrittr_1.5     munsell_0.4.3   
	 [5] colorspace_1.2-6 lattice_0.20-34  R6_2.1.2         plyr_1.8.3      
	 [9] tools_3.3.2      gtable_0.2.0     DBI_0.4-1        lazyeval_0.2.0  	
	[13] assertthat_0.1   digest_0.6.9     tibble_1.2       gridExtra_2.2.1 
	[17] codetools_0.2-15 inline_0.3.14    labeling_0.3     scales_0.4.1    
	[21] stats4_3.3.2 