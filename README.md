# Bioinformatics Bootcamp 2017
**Biomedical Sciences Program - University of California San Diego (UCSD)**  

### Contact us:
Instructor: [Emily Wheeler](mailto:ecwheele@ucsd.edu) (ecwheele@ucsd.edu)  
Instructor: [Ryan Marina](mailto:rmarina@ucsd.edu) (rmarina@ucsd.edu)  

Lecturer: [Dave Gorkin](mailto:dgorkin@ucsd.edu) (dgorkin@ucsd.edu)  
Lecturer: [Eric Van Nostrand](mailto:elvannostrand@ucsd.edu) (elvannostrand@ucsd.edu)  

### Lecture Location
Lectures will all be held in CMME room 2047. See below for daily schedule.

## Schedule

| Day | Date | Time | Topic | Lecture |
| --- | ---- | ---- | ----- | ------- |
| **0** | Pre-CLASS |  | Setup TSCC accounts |  |
| **Wednesday** | 9/27/17 | 9A - 1P | Sequencing Applications Lecture (Dave Gorkin) and Intro to Unix |  |
| **Thursday** | 9/28/27 | 9A - 1P | Downloading Data, Fastqc, Alignment |  |
| **Friday** | 9/29/17 | 9A - 1P | Alignment Recap, Samtools, Gene Quantification |  |
| **Monday** | 10/2/17 | 9A - 1P | Jupyter Notebooks, DESeq2 |  |
| **Tuesday** | 10/3/17 | 9A - 1P | RNA Applications Lecutre (Eric Van Nostrand) and Python Demo |  |
| **Wednesday** | 10/4/17 | 9A - 1P | Gene Pattern  |  |

## Office Hours

| Day | Date | Time | Location | Hosting |
| --- | ---- | ---- | ----- | ------- |
| **Thursday** | 9/28/27 | 4P - 6P | The Lounge (old Cafe Vita) | Ryan M |
| **Sunday** | 10/1/17 | 1P - 3P | Mesa Nueva (Cresta Study Rooms) | Emily + Krystyna |
| **Tuesday** | 10/3/17 | 6P - 8P | SCRM meetings | Emily |
| **Thursday** | 10/5/17 | 3P - 5P | Leichtag Lobby | Josh + Ryan G |
| **Sunday** | 10/8/17 | 1P - 3P | Mesa Nueva | Krystyna |

## Group Project

**Group Assignments**
 
| Group 1 | Group 2 | Group 3 | Group 4 | Group 5 | Group 6 |
| ------ | ------ | ------ | ------ | ------ | ------ |
| Helen | Spencer | Matthew | Dominic | Tom | Erin |
| Derrick | Bernadette | Josh B. | Alex | Gabby | Melinda |
| Celeste | Margaret | Juan | Ryan | Phoebe | Carter |
| Josh L. | Brian | Rebecca | Alanna | Yilan | Noor |
| Ila | Tiani | | | | Emily| 


**Proposal**

* Assigned Friday 9/29


* Due to Emily and Ryan via email Sunday 10/1 at 11:59 PM 


* Work together on your teams to generate an interesting biological question that can be answered with publically available datasets. You can use the ENCODE website, or other sources that you find. You can even use things that have been published and uploaded to the GEO repository, we will help you download any datasets that you find particularly interesting!
 
 
* Your question must incorporate the integration of data from two different assays, one of which must be RNA-Seq, and the second must be something other than RNA-Seq (CHIP-Seq, CLIP-Seq, ATAC-Seq, exome sequencing, genome sequencing). The RNA-Seq must have at least two conditions and two replicates per condition (3 replicates is even better!) Explain why you chose the datasets you did and how they will be used to answer your question. What particular features of that type of assay make it the best choice in order to answer your particular question? Make sure that for your second dataset, you can download processed data (a list of peaks, or DNA variants that were called).


* Write up a proposal (half page, single spaced) explaining your question and computational approach. Feel free to use the literature to draw inspiration for your proposal (you will need to include literature citations in your final report). 


**Final Report**

* Assigned Wednesday 10/4, Due to Emily and Ryan via email by Sunday 10/8 at 11:59 PM


* Minimum 2 page report to address the question proposed in part 1. This report will have 4 sections, be sure to include all literature citations used.  

    * Introduction - Background to why this is an important question
    
    * Question - The specific biological question that will be addressed using the datasets that you have chosen. 
    
    * Results - What analyses did you do on these datasets? What are your results? This section will be supported with figures and figure legends. 
    
    * Discussion - What are the implications of your results? Did you answer your question? Where would you take this analysis next? 
  
  
* Analyses required:

    * Download Fastq, run fastqc, STAR, samtools, featureCounts, DESeq2. Include the full path to the results of these analyses on TSCC in an appendix to your report. 
    
    * Calculate TPM and make a seaborn pairplot on the log2(TPM) from your counts matrix. See notebook8. 
    
    * Use bedtools in some fashion to incorporate your binding dataset and make a venn diagram of your result. Include an explanation of the analysis you performed using bedtools in your results/discussion section(s).
    
    * Run GSEA on your dataset. Include a screenshot of your most interesting results from the html file. Include a discussion of interesting gene sets in your results/discussion section(s). 
    