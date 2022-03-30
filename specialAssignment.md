## special assignment

[PBS browwser](http://popgen.dk:3838/anders/popgen2016/selectionScan/)
Let see if we can do better than the Tajima’s D by using the PBS statistics. First select 3 populations from 
  - NAT - Native Americans (PERU+Mexico)
  - CHB – East Asian - Han Chinese
  - CEU – Central Europeans
  - YRI – African - Nigerians
  
The first population is the one which branch you are investigating. The two others are the one you are comparing to. Chose CEU as the first and choose CHB and YRI as the two others. 

First lets get an overview of the whole genome by making a manhattan plot
  - Press “Run analysis”. 

Note which chromosomes have extreme values. A high value of PBS means a long branch length. 
To view a single chromosome – go to PBS region

Chose the chromosome with the highest PBS value and set the starting position to -1 to get the whole chromosome

Zoom in to the peak by changing start and end position. 

  - Locate the most extreme regions of the genome and zoom in
  - Identify the Gene with the highest PBS value.  
  - What does the gene do?
  
If you have time you can try other genes. Here are the top ones for Humans. You can find the find the location of the genes using for example the ucsc browser https://genome-euro.ucsc.edu/cgi-bin/hgGateway   (choose human GRCh37/hg19 genome). Note that there are some population that you cannot test because the populations are not represented in the data e.g. Tibetan, Ethiopian , Inuit, Siberians.