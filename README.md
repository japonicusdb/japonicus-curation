## Curation issues and curated data for JaponicusDB

Raw data files for building JaponicusDB:

 - `supporting_files/uniprot_ids_names_products.tsv`: japonicus gene
   names, product and UniProtKB accession, downloaded from UniProt
 - `systematic_id_uniprot_mapping.tsv`: japonicus ID to UniProt
   mapping created from `uniprot_ids_names_products.tsv`
 - `contig/*`: EMBL files from ENA with:
   - `/locus_tag` changed to `/systematic_id`
   - gene names from UniProt added as `/primary_name=...`
 - `manual_orthologs.tsv`: manually curated japonicus<->pombe orthologs
 - `pfam_japonicus_protein_data.json`: raw data from Pfam with
   coiled-coil, low complexity and disordered regions
