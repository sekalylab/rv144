# RV144: source code #

## List of figures:
 
[Fig. 2](#fig-2), [Fig. 3](#fig-3), [Fig. 4](#fig-4), [Fig. 5](#fig-5), [Fig. 6](#fig-6)

### Fig. 2
![Fig. 2](figure/20150201_RV144pilot.Fig1.png)

### Fig. 3
![Fig. 3](figure/20150201_RV144pilot.Fig2.png)

### Fig. 4
![Fig. 4](figure/20150201_RV144pilot.Fig3.png)

### Fig. 5
![Fig. 5](figure/20150201_RV144pilot.Fig4.png)

### Fig. 6
![Fig. 6](figure/20170127_RV144.Fig5.png)

## Supplemental material:

### a. transcriptomic pilot study:
code:  
- preprocessing: [[MD]](code/20160509_RV144pilot.preprocessing.code.md)  
- geneset-analysis: [[MD]](code/20160510_RV144pilot.geneset_analysis.code.md)  

input:  
- non-normalized matrix: [[CSV]](input/GA_illumina_expression.rv144pilot.matrix_non_norm.csv)  
- arrays/samples annotation: [[CSV]](input/GA_illumina_expression.rv144pilot.metadata.csv)  
- features annotation: [[TSV]](input/Illumina_HumanHT12_V4.hg19.chip)  
  
output:  
- non-normalized ExpressionSet: [[RDA]](output/rv144pilot.esetRaw.RData)  
- quantile normalized ExpressionSet: [[RDA]](output/rv144pilot.eset.RData)  
- DMSO-substracted ExpressionSet: [[RDA]](output/rv144pilot.esetVehSubstract.RData)  
- pre-vaccination-substracted ExpressionSet: [[RDA]](output/rv144pilot.esetBaselined.RData)  
- MArrayLM list: [[RDA]](output/rv144pilot.fits.RData)  
- gsea result table: [[RDA]](output/rv144pilot.gseaOutput.RData)  
- slea ExpressionSet: [[RDA]](output/rv144pilot.gsSetVehSubstracted.RData)  
