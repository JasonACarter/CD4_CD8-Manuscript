# CD4_CD8-Manuscript

This is the Github repository associated with Carter *et al.* (2019) "Single T cell sequencing demonstrates the functional role of αβ TCR pairing in cell lineage and antigen specificity" Front. Immunol. doi: 10.3389/fimmu.2019.01516 

**Data** 

Paired $\alpha\beta$ TCR sequences, as well as V(D)J annotations, are provided as pickled Pandas dataframes within the "Data" folder. The AbVitro TCR sequences for Subjects 1-5 were obtained from Grigaityte *et al.* (bioRxiv 213462). TCR sequences obtained in this study using the 10x Genomics platofrm (for Subjects 1,3,5,6) are provided in these dataframes. We additionally provide the VDJdb (https://vdjdb.cdr3.net) antigen specificity annotations that were used to generate Figure 5. 

**Analysis**

iPython notebooks are provided for each of the main figures in the Scripts folder. 

Dependencies: Python 3.6, numpy 1.12.1, matplotlib 2.1.1, seaborn 0.8.1, scipy 1.0.0, sklearn 0.19.1, pandas 0.22.0, statsmodels 0.8.0, xgboost 0.81, qvalue (https://github.com/nfusi/qvalue)
