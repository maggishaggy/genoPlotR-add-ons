#README for genoPlotR r package add-on functions

##Note:
#####All of these functions take dna_seg or lists of dna_seg objects as one of their arguments.
#####They also require the genoPlotR package to run.

##flip
#####flip(dna_seg)
#####flip takes a segment of DNA and flips its orientation

##color
#####color(list of dna_segs, annotation to search via regex, desired color)
#####color changes the color of any genes with the given annotation
#####including partial matches.
#####Saves the output to a list.

##delete_genes
#####delete_genes(list of dna_segs, gene_index)
#####Removes unwanted genes from dna_seg objects.


