#****************************************** 
#**          Module 5 Challenge          **
#** last edited by Justin Bein, 03/11/24 **
#**                                      **
#****************************************** 

#********************************************************************* 
#** In this assignment, I'll obtain summary statics and create      **
#** various charts of the results of drug regimens.                 **
#**                                                                 **
# * The scenario: I've just joined Pymaceuticals, Inc., a new       **
# * pharmaceutical company that specializes in anti-cancer          **
# * medications. Recently, it began screening for potential         **
# * treatments for squamous cell carcinoma (SCC), a commonly        **
# * occurring form of skin cancer.                                  **
# *                                                                 **
# * As a senior data analyst at the company, you've been given      **
# * access to the complete data from their most recent animal study.**
# * In this study, 249 mice who were identified with SCC tumors     **
# * received treatment with a range of drug regimens. Over the      **
# * course of 45 days, tumor development was observed and measured. **
# * The purpose of this study was to compare the performance of     **
# * Pymaceuticals’ drug of interest, Capomulin, against the other   **
# * treatment regimens.                                             **
# *                                                                 **
# * My anlaysis will begin with obtain the two datasets, combining  **
# *    them, and cleanging them. Then, I'll create a series of      **
# *   descriptive statisctics for each drug regimen. Then, I'll     **
# *    create summary charts including bar, pie, and line. Lastly,  **
# *    I'll createa  scatter plot and fit a regression through the  **
# *   data.                                                         **
#*********************************************************************

#*********************************************************************
#**                           Source Data                           **
#** The source data for this challenging is contained within two    **
#** files:                                                          ** 
#**                                                                 **
#** Mouse_metadata.csv (249 rows and 5 columns + a header row)      **
#** Study_results.csv (1,893 rows and 4 columns + a header row)     **
#*********************************************************************