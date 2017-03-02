#metagenome single copy genes

This script uses AMPHORA2 to call open reading frames and then produces a table with the amount of single copy genes present in the bin

You will need to modify this script to call up the scripts from AMPHORA2 (See line 103-106) and the dependent script provided here.

Dependencies

AMPHORA2 https://github.com/martinwu/AMPHORA2

Other dependent scripts:

single_copy_genes_make_table.py

-i --input_file (required)
-o --output_file (required)
-e --evalue (required) -t --type (required) -p --processors (required) -s --seq_type (required) -c --OSC (optional)

Run this script as follows python single_copy_genes.py -i -o -e -t -s -p
