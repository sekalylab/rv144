# RV144: preprocessing source code #

### a. transcriptomic pilot study:
code:  
- R code: [[PDF]](pilot/20160509_RV144pilot.preprocessing.code.pdf)  

input:  
- non-normalized matrix: [[CSV]](https://storage.googleapis.com/rv144pilot_20140428/preprocessing/GA_illumina_expression.rv144pilot.matrix_non_norm.csv)  
- arrays/samples annotation: [[CSV]](https://storage.googleapis.com/rv144pilot_20140428/preprocessing/GA_illumina_expression.rv144pilot.metadata.csv)  
- features annotation: [[TSV]](https://storage.googleapis.com/rv144pilot_20140428/preprocessing/Illumina_HumanHT12_V4.hg19.chip)  

output:  
- non-normalized ExpressionSet: [[RDA]](https://storage.googleapis.com/rv144pilot_20140428/preprocessing/rv144pilot.esetRaw.RData)  
- quantile normalized ExpressionSet: [[RDA]](https://storage.googleapis.com/rv144pilot_20140428/preprocessing/rv144pilot.eset.RData)  
- DMSO-substracted ExpressionSet: [[RDA]](https://storage.googleapis.com/rv144pilot_20140428/preprocessing/rv144pilot.esetVehSubstract.RData)  
- pre-vaccination-substracted ExpressionSet: [[RDA]](https://storage.googleapis.com/rv144pilot_20140428/preprocessing/rv144pilot.esetBaselined.RData)  
- MArrayLM list: [[RDA]](https://storage.googleapis.com/rv144pilot_20140428/preprocessing/rv144pilot.fits.RData)  

### b. transcriptomic case/control study:
code:  
- R code: [[PDF]](case_control/20151007_RV144.preprocessing.code.pdf)  

input:  
- non-normalized matrix: [[CSV]](https://storage.googleapis.com/rv144_20140428/preprocessing/GA_illumina_expression.rv144.matrix_non_norm.csv)  
- arrays/samples annotation: [[CSV]](https://storage.googleapis.com/rv144_20140428/preprocessing/GA_illumina_expression.rv144.metadata.csv)  
- features annotation: [[TSV]](https://storage.googleapis.com/rv144pilot_20140428/preprocessing/Illumina_HumanHT12_V4.hg19.chip)  

output:  
- non-normalized ExpressionSet: [[RDA]](https://storage.googleapis.com/rv144_20140428/preprocessing/rv144.esetRaw.RData)  
- quantile normalized ExpressionSet: [[RDA]](https://storage.googleapis.com/rv144_20140428/preprocessing/rv144.eset.RData)  
- DMSO-substracted ExpressionSet: [[RDA]](https://storage.googleapis.com/rv144_20140428/preprocessing/rv144.esetBaselined.RData)  
- MArrayLM list: [[RDA]](https://storage.googleapis.com/rv144_20140428/preprocessing/rv144.fits.RData)


# RV144: genesets analsysis #

### a. transcriptomic pilot study:
code:  
- R code: [[PDF]](pilot/20160510_RV144pilot.geneset_analysis.code.pdf)  

input:  
- MArrayLM list: [[RDA]](https://storage.googleapis.com/rv144pilot_20140428/preprocessing/rv144pilot.fits.RData)  

output:  
- gsea result table: [[RDA]](https://storage.googleapis.com/rv144pilot_20140428/geneset_analysis/rv144pilot.gseaOutput.RData)  
- slea ExpressionSet: [[RDA]](https://storage.googleapis.com/rv144pilot_20140428/geneset_analysis/rv144pilot.gsSetVehSubstracted.RData)
