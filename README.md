# lncRNA-Identification-Pipeline-main
This repository is predominantly a collection of scripts used to identify lncRNA <br>
It also houses a pdf of a plain language tutorial written for the identification of lncRNA from RNASeq data.<br>

Although I did compile the resources and write the tutorial, I did not create any of the scripts in this repository. They have been created and gathered by other researchers and passed along to me.
Each script has the original author in the file, I implore you to read the preamble to understand who the script came from originally.

The scripts are as follows:<br>
codon.txt : a text based file containing codons corresponding to sequence triplets<br>
get_intergenic.pl : a pearl script used to get intergenic transcript information<br>
get_intergenicLoci_list.pl : a pearl script used to get a transcripts list of intergenic transcripts based on class_code "u"<br>
sixFrameTranslate.pl : a pearl script used to translate sequence information into amino acid sequence information for all 6 frames<br>
summary_gtf.pl : a pearl script that processes gtf files, summarizing them<br>

There usage is as follows: <br>
get_intergenic.pl : perl get_intergenic.pl -g [gtf] -l [loci] -o [output]<br>
get_intergenicLoci_list.pl : perl get_intergenic.pl -g1 [ens_gtf] -g2 [ref_gtf] -o [output]<br>
sixFrameTranslate.pl : sixFrameTranslate.pl -i [input] -o [output] -l [min_length]<br>
summary_gtf.pl : perl summary_gtf.pl -i [filein.gtf] -o [fileout.txt]<br>
