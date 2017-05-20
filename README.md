# Enriching-Bug-Report
In this project, Eclipse.zip, Mozilla.zip and GCC.zip are our original datasets. In Enrichment.xlsx, we put all of our experimental data in it. 

in order to run this project. You should do as following:
1. using NLP.py to do preprocessing, input file: stopwords.txt, and the bugreport set such as OpenOffice.xml
2. using TMT to generate topic model
3. using word_process.cpp to generate final dataset. input file: TMT's generate file, NPL.py's generate file
4. using Enrich.h and Enrich.cpp to generate final result. The input files are generate in step 3.

This code is our version 1.0. and you such set paramers by your self. We will fix this problem in next version.
