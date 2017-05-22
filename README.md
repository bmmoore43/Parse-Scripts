# Parse-Scripts

This repository is a collection of scripts used to parse various files. While there is not a specific pipeline, there are small series of scripts that are meant to be used for a specific meaning. They are as follows:

# GO term scripts

Associating GO term, function, and gene

Use: parse_genegofunc.py

Need: 
1. file with Go-term and function, ie. GO_BPtermlistfromEBI
2. file with gene, associated aracyc pathways, ie. SMvsOther_classes_file.txt_SM_pathways_names2.txt.parsed.txt_genefile.txt
3. file with gene, class of gene (SM, PM), ie. combined_class-GO-aracyc_SMvsPM_allgenes.txt
4. file with gene and Go-term identifier, ie. gene_association_tair_modified.txt

        python parse_genegofunc.py <file1: GO-term:function> <file2: gene:genetype:pathways..> <file3: gene:genetype> <file4: gene:GO-term>
        
