# obscurinDB
Database of obscurin single amino-acid variants and mapping to sequence and structural information

- This is a resource for collecting and easily finding relevant data on specific obscurin SNVs		
- Please use the interactable sheet to quickly search for SNV or SNVs required		
	- Use Filters to search for SNVs - Click on drop-down arrow, enter search terms in search bar and	select SNVs desired by ticking the respective box; multiple SNVs can be selected if desired	
		- Variant ID allows you to search by ID if you already know it (e.g. rs# for dbSNP)
		- Chr:bp allows you to search by chromosomal position of genetic locus
		- AA coord allows you to search at a specific protein sequence position (N.B. transcripts)
		- Conseq. Type allows you to filter by category (e.g. missense, synonymous etc.)
		- Canon Domain allows you to find all alleles within an individual domain or domains
		- Transcript allows you to specify transcript if particular isoform is of interest
		- Clin. Sig. allows you to find all clinically significant SNVs (e.g. pathogenic, etc.)
	- Information provided by default for chosen SNVs is the domain, protein sequence position (obscurin-IC), variant ID, RefSeq transcript, allele change, amino acid change, global minor allele frequency (where available), and pathogenicity metrics (PROVEAN, PolyPhen2 HDiv, Condel, SIFT, CADD, and mCSM)	
		- You can add additional information using the Pivot Table functions
		- Click anywhere on the table and use PivotTable Tools -> PivotTable Fields and then check the box for any information field needed (please ensure that said field is under Rows so that it formats correctly)
	- Main raw data source can be found on Ensembl_Exon_SNV_Export tab. Data sources not contributing to the main table are still provided (gnomAD_data, ExAC_data)	
	- Raw outputs of computation of PolyPhen-2, PROVEAN, Condel and mCSM are available; please do not edit as these feed into the Ensembl database	
	- Domains by Transcript and Domain Architecture sheets give the domain boundaries used by the main database; they are available for viewing	
