# NCBI2Lineage
Converting taxids into homogeneous lineages for NCBI can be tricky as there can be gaps as well as several "no rank" taxids within a lineage.


<br>This  python script constructs homogeneous lineages from ncbi taxdump files names.dmp and nodes.dmp. 
<br>The script is tested in pyhon 3.9 and run in spyder 5.1.5
<br>The required inputs are the full filepaths to nodes.dmp and names.dmp, which can be downloaded from ncbi taxdump ftp.
<br>Additionally, the desired ranks of the lineage are supplied.
<br>The script outputs two tsv files, with a lineage per row for each taxon in NCBI.
<br>The taxon is present in the idx column and can be used to easily convert ncbi taxids into rank normalized lineages.
