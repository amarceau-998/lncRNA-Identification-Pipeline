# lncRNA-Identification-Pipeline-main
Collection of scripts used to identify lncRNA 

I did not create any of the scripts in this repository, they have been created and gathered by other researchers and passed along to me.
Each script has the original author in the file, I implore you to read the preamble to understand who the script came from originally.

The scripts are as follows:
#codon.txt : a text based file containing codons corresponding to sequence triplets
#get_intergenic.pl : a pearl script used to get intergenic transcript information
#get_intergenicLoci_list.pl : a pearl script used to get a transcripts list of intergenic transcripts based on class_code "u"
#sixFrameTranslate.pl : a pearl script used to translate sequence information into amino acid sequence information for all 6 frames
#summary_gtf.pl : a pearl script that processes gtf files, summarizing them

There usage is as follows: 
#get_intergenic.pl : perl get_intergenic.pl -g [gtf] -l [loci] -o [output]
#get_intergenicLoci_list.pl : perl get_intergenic.pl -g1 [ens_gtf] -g2 [ref_gtf] -o [output]
#sixFrameTranslate.pl : sixFrameTranslate.pl -i [input] -o [output] -l [min_length]
#summary_gtf.pl : perl summary_gtf.pl -i [filein.gtf] -o [fileout.txt]
