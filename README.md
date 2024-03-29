# *Lachnellula willkommii* Genome Sequencing, Assembly and Annotation     
**Whole genome sequencing for identification of molecular markers to develop diagnostic detection tools for the regulated plant pathogen *Lachnellula willkommii***     
      
## Abstract     
The filamentous ascomycete fungus *Lachnellula willkommii* is the causal agent of European Larch Canker (ELC), one of the most destructive diseases of larch in Europe and a regulated plant pathogen of quarantine significance in Canada and the United States.  *L. willkommii* was first detected in Massachusetts, North America in 1927 on a larch (*L. decidua*) plantation built years earlier using nursery stock imported from Great Britain.  Despite the decades of sanitation practices aimed at eliminating the pathogen, it has reappeared in coastal areas of Canada and the United States.  There is the concern ELC could spread throughout the range of eastern larch, a transcontinental species typical of the Boreal forest which spans the North American landscape.  Several non-pathogenic saprophytic species of the *Lachnellula* genus are indigenous to North America and inhabit ecozones overlapping regions *L. willkommii* has been detected.  Morphological and biological methods applied to distinguish *L. willkommii* are often inadequate as the fungus does not always produce the structures that distinguish it from other *Lachnellula* species.  Whole genome sequencing technologies were used to obtain the draft genome sequences of *L. willkommii* and six other *Lachnellula* species.  Molecular markers mined from the genomic data can be used to discriminate *L. willkommii* from its non-pathogenic relatives.     
     
## Introduction     
*Lachnellula* species are filamentous ascomycete fungi within the Hyaloscyphaceae family (Dharne, 1965).  Most *Lachnellula* species are saprophytic or weakly parasitic, but some cause cankers on conifers with a narrow host range (Hahn and Ayers, 1934; Hahn and Ayers, 1943; Horst, 2013; Yde‐Andersen, 1979).  Within the genus *Lachnellula*, *L. willkommii* is the most pathogenic species and causes European Larch Canker (ELC) of *Larix* and *Pseudolarix* species.  Young trees infected with this pathogen may become girdled or killed and permanent cankers on the trunks of older trees cause stem distortion and breakage, with significant impact on natural or planted stands of native larch and on plantations of exotic larch species (Lohwag, 1963).  *L. willkommi* appears to have spread from Asia to across Europe, infecting various species of larch and devastating larch plantations (Yde‐Andersen, 1979).  *L. willkommii* was first reported in North America in 1927 in Massachusetts by members of the Harvard Forest School who identified the pathogen on Japanese and European larch nursery stock imported from Scotland in the early 1900s (Spaulding and Siggers, 1927).  Since its introduction to North America, *L. willkommii* has been a fungal disease of plant quarantine significance and a regulated pathogen in Canada and the United States (Agency, 2018; Horst, 2013; USDA/APHIS, 2012; Yde‐Andersen, 1979).  Decades of sanitation efforts involving quarantine and the destruction of infected trees and branches were believed to have eradicated the disease from the area, however, the disease has since reappeared in coastal areas in Maine, and has been detected in Canada in the Maritimes on Prince Edward Island, Nova Scotia and New Brunswick and remains under official control and quarantine in these provinces (Brandt, 1997; Magasi and Pond, 1982; Miller-Weeks and Stark, 1983; Ostaff, 1985; Simpson and Harrison, 1993).  While ELC caused by *Lachnellula willkommii* appears to be restricted to the mild-wintered Maritime regions, there is the potential for ELC to spread throughout the range of eastern Larch, which is a transcontinental species typical of the Boreal forest which spans the North American landscape.  Several saprophytic *Lachnellula* species native to North America share overlapping geographical distributions with *L. willkommii*. *L. willkommii* is almost indistinguishable morphologically from its non-pathogenic sister species, *L. occidentalis*, and the two are often found together on dead plant debris (Baral, 1984; Hahn and Ayers, 1934).  Because samples sent to diagnostic labs for testing are often taken from dead tree material, culturing the fungi for morphological identification isn’t possible.  When live samples are available, the two fungi do not always produce the morphological structures that may distinguish them when cultured in the lab.  Genomic data obtained from whole-genome sequencing is a valuable resource for developing molecular diagnostic testing tools.  Comparative genomic analysis of *L. willkommii* and its close relatives will allow researchers to develop molecular markers that can distinguish it from its non-pathogenic sister species.  In this study we performed whole-genome sequencing, *de novo* assembly and annotation of *Lachnellula willkommii* and six other *Lachnellula* species: *L. arida*, *L. cervina*, *L. hyalina*, *L. occidentalis*, *L. subtilissima*, and *L. suecica*.     

## Methods     
Agar-culture plugs preserved in glycerol were retrieved from liquid-nitrogen storage and transferred as hyphal masses onto 2% potato dextrose agar (PDA) plates.  The inoculated plates were incubated in the dark for two weeks at 20⁰C.  Thereafter, agar plugs were taken from advancing colony edges and transferred to fresh PDA plates overlain with single sheets of porous cellophane (Fisher Scientific, ThermoFisher Scientific, 13 100 3953).  The inoculated plates were placed in plastic box trays to prevent accumulation of excess humidity, and incubated for two more weeks under the same conditions.  Mat tissue growing over cellophane on PDA plates was scraped off and rinsed with water in a clean petri dish, then collected into 2-mL Eppendorf™ Snap-Cap Microcentrifuge Safe-Lock™ Tubes (Eppendorf™ by Fisher Scientific, ThermoFisher Scientific, 022363352).  Mat tissue was collected from three plates per cultured species.  DNA extraction was performed according to the CTAB method described by Moller et al., (1992), with the following modifications:  mat tissue samples were flash-frozen in liquid nitrogen and put into 500 µL of TES buffer in tubes containing a garnet matrix and a single ¼-inch ceramic sphere (Lysing Matrix A, MP Biomedicals, Solon, OH, USA, 6910-500).  Sample material was homogenised in a FastPrep®-24 (MP Biomedicals, Solon, OH, USA) tissue and cell homogeniser for 45 s with the speed set to 5.0.  Lysates were treated with 4 µL Proteinase K (~20 µg/µL)(Millipore-Sigma, P2308), and then clarified by centrifugation at 16,000 *x g* for 5 min at room temperature.  The supernatant was transferred to new 2-mL Safe-Lock™ tubes for adjustment of salt concentration and incubation with 10% CTAB treatment, as per protocol.  Sample incubation time with chloroform:isoamyl alcohol (24:1)(Millipore-Sigma, C0549) was increased to 4.5 hours at room temperature, while subsequent centrifugation was performed at 18,000 *x g* for 5 min at room temperature.  Chloroform extraction was performed twice on each sample due to excess cloudiness remaining in samples after the first extractions were performed.  Following chloroform extraction, samples were transferred to fresh 1.5-mL tubes and treated with 3 µL (10 µg/µL) RNase-A (Millipore-Sigma, R4642) with a 30-min incubation at 37⁰C.  Sample tubes were centrifuged at 18,000 *x g* for 1 min and the supernatant was transferred to a fresh 1.5-mL tube where treatment with 150 µL of ammonium acetate (3M) and 500 µL of ice-cold isopropanol for DNA precipitation were combined into a single step, with overnight incubation at -20⁰C.  Sample tubes were centrifuged at 18,000 x g for 5 min at 4⁰C in a pre-cooled centrifuge rotor and the supernatant was aspirated off the pellet which was then washed with 300 µL of ice-cold 75% ethanol by dislodging the pellets from the sides of the tubes and vortexing the mixture for 1 min.  Sample tubes were centrifuged at 14,000 *x g* for 15 min at 4⁰C and then allowed to air-dry for 30 min at room temperature before being re-suspended in 50-100 µL TE buffer.  DNA concentration was estimated by spectrophotometry using the NanoDrop ND-1000 (ThermoScientific, Wilmington, USA) with optical density ratios (OD=A260/A280) and the Qubit® DNA BR assay kit (Invitrogen™ by LifeTechnologies, ThermoFisher Scientific, Q32853) on a Qubit® fluorometer (Invitrogen™ by LifeTechnologies, ThermoFisher Scientific).      
For sequencing library preparation, DNA samples were sheared using the Covaris M220 ultrasonicator (Covaris, Inc., Woburn, MA, USA) to 400 bp.  Sequencing libraries were prepared using the Ion Xpress™ gDNA Fragment Library Kit (ThermoFisher Scientific, cat. no.: 4471269) on the Ion PGM™ System (ThermoFisher Scientific, 4462921).  The libraries were size selected (300-450 bp) on the PippinPrep automated size selection system (Sage Science, Beverly, MA, USA, PIP0001) and 2% DF Marker L cassette type (BDF2010).  Libraries were quantified prior to library bead-template preparation using the Ion Library TaqMan™ Quantitation Kit (Ion Torrent™, ThermoFisher Scientific, cat. no.: 4468802).  Sample library bead-template preparation and enrichment was conducted using the OneTouch™ system coupled with the Ion OneTouch™ ES instrument (Ion Torrent™, ThermoFisher Scientific, 4474779) to prepare template-positive Ion PGM™ Template OT2 400 Ion Sphere™ Particles (Ion Torrent™, ThermoFisher Scientific, cat. no.: 4479880), using 16 pM library dilutions as input.  Quality assessment of the unenriched template-positive Ion Spheres was performed on aliquots of bead-template preparations prior to the enrichment step using the Ion Sphere™ Quality Control Kit (cat. no.: 4468656).  The enriched template-positive sample libraries were loaded 318v2 chips (Ion Torrent™, ThermoFisher Scientific, cat. no.: 4488146).      
Sequencing reads were processed using PrinSeq (Schmieder and Edwards, 2011) and genome assembly was performed using Newbler (v. 2.6)(Margulies et al., 2005).  De novo repetitive element libraries were created for each of the Lachnellula assemblies with RepeatModeler (v.1.0.11)(Smit and Hubley, 2017) using the RMBlast-NCBI search engine.  The derived repeat consensi for each species were combined and sequences classified as “unknown” repeats were queried for conserved domains against the NCBI nucleotide collection database (BLASTx) and RFAM (BLASTn).  Consensus sequences producing significant alignments (E-value > 1e-5) to predicted genes, gene families, or RNA features were removed.  RepeatMasker (RepBase RepeatMasker Edition, v.4.0.7)(Smit et al., 2016) was used to soft-mask the genomes using the RepBase and DFam databases (releases 20170127)(Bao et al., 2015; Hubley et al., 2015), then using the known followed by unknown elements of the custom-created repeat library, each time using as input for RepeatMasker the previously masked output.  Results from each round were then analysed together to produce a final repeat annotation and then formatted to work with MAKER.      
MAKER version 2.31.9 (Campbell et al., 2014a; Campbell et al., 2014b; Cantarel et al., 2008) was used to annotate genes using protein-homology-based and ab initio predictions.  A total of three iterations of MAKER were run.  Initial predictions were generated from MAKER using, as input 1) *Botrytis cinerea* as the species model for Augustus version 3.2.3 (Stanke et al., 2008; Stanke and Waack, 2003) gene prediction, 2) the protein sets of the related species listed in Table S1 for protein-homology-based prediction (est2genome =1, protein2genome =1), 3) and the custom-created repeat library for repeat masking.  Gene models from the first iteration of MAKER were used to train Augustus using the Benchmarking Universal Single-Copy Orthologs (BUSCO) version 3 program (Simão et al., 2015) as well as to train the Semi-HMM-based Nucleic Acid Parser (SNAP) program (version 2006-07-28)(Korf, 2004).  For SNAP, confident gene models generated in the first iteration of MAKER (AED = 0.25, length = 50 amino acids) were used to create a new parameter file to be used by SNAP with the fathom parameters -categorize and -export set to 1000 and default settings for the forge and the hmm-assembler elements of the SNAP package.      
Regions that contained mRNA annotations plus 1000 bp of flanking sequence were excised from the gene models generated from the first iteration of MAKER using BEDTools (v2.27.1)(Quinlan and Hall, 2010) and used as input for optimisation of Augustus gene model parameters using the BUSCO pipeline (Waterhouse et al., 2017).  BUSCO was used to optimise the HMM search model to re-train Augustus and produce a trained, species-specific HMM model for subsequent use with MAKER using the genome mode, --long option, pezizomycotina_odb9 BUSCO dataset as lineage option and pre-trained Augustus gene prediction parameters for Botrytis cinerea.  In parallel, GeneMark-ES (version 3.54)(Ter-Hovhannisyan et al., 2008) was trained on the unmasked genome assemblies to produce ab initio gene models, using fungal settings, which were provided to MAKER for the second and third iterations.     
Repeat annotations generated from the first MAKER iteration, as well as the optimised Augustus gene models, SNAP HMM file, and GeneMark-ES predictions were incorporated into a second iteration of MAKER, with the parameters est2genome and protein2genome set to 0 and tRNA predictions enabled (tRNAscan-SE version 1.3.1)(Lowe and Eddy, 1997).  The results from the second MAKER iteration were then used to train Augustus and SNAP again, before running the final round of MAKER.  The model_org, max_DNA_length and min_contig options were adjusted from simple, 100,000 and 1,000 to default, 300,000 and 1, respectively for the second and third MAKER iterations.     
The Annotation Edit Distance (AED) distribution of MAKER-generated gene models was used to assess the quality of the gene predictions (using the AED_cdf_generator.pl script).  Genome annotation files were fed into the Genome Annotation Generator (GAG) version 2.0.1 (Geib et al., 2018) to remove short introns (<10 bp) and add missing start and stop features, while invalid gene features such as proteins with internal stops flagged by GAG were manually corrected.  Error detection and correction of annotation files using GAG was performed iteratively until error-free.  The GAG-generated protein files were used in subsequent functional annotation.  Additional ab initio gene predictions not overlapping MAKER annotations were scanned for protein domains using InterProScan 5.24-63.0 (Jones et al., 2014) with PFAM Models 31.0 and Lookup Service 5.24-63.0 while putative functions were assigned using BLASTP (E-value > 1e-6)(Altschul et al., 1990) to identify the best homologs from the UniProt/Swiss-Prot protein database (version 2/21/2018)(Consortium, 2018).  The program Annie (version 1.0)(Tate et al., 2014) was used to convert InterProScan and BLAST annotations into three column tables so that GAG could be used to update genome annotation files.  Renaming and integration of annotation features in GFF, protein, BLAST and InterProScan output files was performed using scripts included in the MAKER package.  GAG was used along with NCBI’s command line tool tbl2asn (NCBI, 2011) to create the GenBank submission files.  We assessed the completeness of the genome assemblies using BUSCO in combination with the pezizomycotina_odb9 dataset (created 2016-02-13)(Simão et al., 2015).     
      
## Results
Genome assemblies and the gene and protein model complements for the *Lachnellula* species sequenced are available on NCBI under the genome assembly accession numbers listed in Table 1.  The genome assembly metrics varied for each of the *Lachnellula* species sequenced Table 2.  An average of 4.52 (±1.12) million reads and 1.21 (±0.33) billion bases were sequenced per species.  The average GC content was 43.65 (±2.96)%.  Coverage averaged 28.43 (±9.72) across the *Lachnellula* species sequenced.  In addition to having the greatest coverage (43.7X), the *L. hyalina* assembly had the smallest estimated genome size (33.8 Mb), the lowest number of contigs (685), with the lowest contig L50 (66) and highest contig N50 (161,844 bp) and longest maximum contig length (531,425 bp), as well as the most complete BUSCO coverage (94.5%).  In contrast, *L. willkommii* had the most fragmented assembly, with the lowest sequencing coverage (12.7X), the second largest estimated genome size (51.0 Mb), the highest number of contigs (20,879) and contig L50 (1,668), lowest contig N50 (8,078), shortest maximum contig length (80,405 bp), as well as the lowest BUSCO coverage (80.0%).     
 
 
Table 1.  Lachnellula species and isolates sequenced.
Species	Isolate	Host	Origin	Genome Assembly Accession
Lachnellula arida	CBS 203.66	Pinus cembra	Switzerland	QGMF00000000
L. cervina	CBS 625.97	Alnus rubra	Oregon, USA	QGMG00000000
L. hyalina	CBS 185.66	Pinus montana	Switzerland	QGMH00000000
L. occidentalis	CBS 160.35	Larix decidua	Massachusetts, USA	QGMI00000000
L. subtilissima	CBS 197.66	Picea abies	Switzerland	QGMJ00000000
L. suecica	CBS 268.59	Larix decidua	France	QGMK00000000
L. willkommii	CBS 172.35	Larix spp. 	Massachusetts, USA	QGML00000000

Table 2.  Lachnellula species draft genome assembly and completeness summary statistics.
Genome	L. arida	L. cervina	L. hyalina	L. occidentalis	L. subtilissima	L. suecica	L. willkommii
Genome assembly metrics
Estimated Genome Size (Mb)	42.7	51.4	33.8	48.3	35.2	43.4	51.0
GC (%)	46.3±11.6	41.4±10.9	47.1±11.2	41.8±11.3	47.0±9.0	48.6±5.9	42.0±10.9
Coverage	33.7	23.6	43.7	33.0	27.6	24.7	12.7
Contigs	4,119	12,510	685	4,247	2,317	4,891	20,879
Contig N50	37,853	22,497	161,844	31,262	34,087	19,034	8,078
Contig L50	339	625	66	430	320	672	1,668
Longest contig (bases)	187,565	135,220	531,425	252,529	189,346	115,910	80,405
Genome completeness metrics
BUSCO (%)	92.7	90.8	94.5	89.8	85.0	82.1	80.0
Predicted Gene Models 	9,660	9,494	9,248	8,984	9,027	10,393	9,047
Mean gene length (bp) 	1,672	1,646	1,665	1,650	1,620	1,605	1,614
% genome covered by genes 	37.8	30.4	45.5	30.7	41.5	38.4	28.6
Predicted complete CDS 	8,702	8,367	8,530	7,983	7,834	8,458	6,973

 
 
Literature Cited

	Agency, C. F. I. (2018). List of Pests Regulated by Canada, vol. 2018.     
	     
	Altschul, S. F., Gish, W., Miller, W., Myers, E. W. and Lipman, D. J. (1990). Basic local alignment search tool. Journal of molecular biology 215, 403-410.    
	     
	Bao, W., Kojima, K. K. and Kohany, O. (2015). Repbase Update, a database of repetitive elements in eukaryotic genomes. Mobile DNA 6, 11.          
	Baral, H. (1984). Taxonomische und ökologische Studien über die Koniferen bewohnenden europäischen Arten der Gattung *Lachnellula* Karsten. Beiträge zur Kenntnis der Pilze Mitteleuropas 1, 143-156.     
	     
	Brandt, J. P. (1997). Forest health monitoring in west-central Canada in 1996.     
	     
	Campbell, M. S., Holt, C., Moore, B. and Yandell, M. (2014a). Genome annotation and curation using MAKER and MAKER‐P. Current Protocols in Bioinformatics 48, 4.11. 1-4.11. 39.     
	     
	Campbell, M. S., Law, M., Holt, C., Stein, J. C., Moghe, G. D., Hufnagel, D. E., Lei, J., Achawanantakun, R., Jiao, D. and Lawrence, C. J. (2014b). MAKER-P: a tool kit for the rapid creation, management, and quality control of plant genome annotations. Plant physiology 164, 513-524.     
	     
	Cantarel, B. L., Korf, I., Robb, S. M., Parra, G., Ross, E., Moore, B., Holt, C., Alvarado, A. S. and Yandell, M. (2008). MAKER: an easy-to-use annotation pipeline designed for emerging model organism genomes. Genome research 18, 188-196.     
	     
	Consortium, U. (2018). UniProt: the universal protein knowledgebase. Nucleic acids research 46, 2699.     
	     
	Dharne, C. G. (1965). Taxonomic Investigations on the *Discomycetous* Genus *Lachnellula* Karst. Journal of Phytopathology 53, 101-144.     
	     
	Geib, S. M., Hall, B., Derego, T., Bremer, F. T., Cannoles, K. and Sim, S. B. (2018). Genome Annotation Generator: a simple tool for generating and correcting WGS annotation tables for NCBI submission. GigaScience 7, giy018.     
	     
	Hahn, G. G. and Ayers, T. T. (1934). *Dasyscyphae* on conifers in North America. I. The large-spored, white-excipled species. Mycologia 26, 73-101.     
	     
	Hahn, G. G. and Ayers, T. T. (1943). Role of *Dasyscypha willkommii* and related fungi in the production of canker and die-back of larches. Journal of Forestry 41, 483-495.     
	     
	Horst, R. K. (2013). Cankers and Diebacks. In Westcott's Plant Disease Handbook, pp. 149-173: Springer.     
	     
	Hubley, R., Finn, R. D., Clements, J., Eddy, S. R., Jones, T. A., Bao, W., Smit, A. F. and Wheeler, T. J. (2015). The Dfam database of repetitive DNA families. Nucleic acids research 44, D81-D89.     
	     
	Jones, P., Binns, D., Chang, H.-Y., Fraser, M., Li, W., McAnulla, C., McWilliam, H., Maslen, J., Mitchell, A. and Nuka, G. (2014). InterProScan 5: genome-scale protein function classification. Bioinformatics 30, 1236-1240.     
	     
	Korf, I. (2004). Gene finding in novel genomes. BMC bioinformatics 5, 59.     
	     
	Lohwag, K. (1963). Dangerous forest diseases in Austria. Miscellaneous Publication, 66.     
	     
	Lowe, T. M. and Eddy, S. R. (1997). tRNAscan-SE: a program for improved detection of transfer RNA genes in genomic sequence. Nucleic acids research 25, 955.     
	     
	Magasi, L. and Pond, S. (1982). European larch canker: a new disease in Canada and a new North American host record. Plant Disease 66.     
	     
	Margulies, M., Egholm, M., Altman, W. E., Attiya, S., Bader, J. S., Bemben, L. A., Berka, J., Braverman, M. S., Chen, Y.-J. and Chen, Z. (2005). Genome sequencing in microfabricated high-density picolitre reactors. Nature 437, 376.     
	     
	Miller-Weeks, M. and Stark, D. (1983). European larch canker in Maine. Plant Disease 67.     
	     
	Möller, E., Bahnweg, G., Sandermann, H. and Geiger, H. (1992). A simple and efficient protocol for isolation of high molecular weight DNA from filamentous fungi, fruit bodies, and infected plant tissues. Nucleic acids research 20, 6115.     
	     
	NCBI. (2011). The GenBank Submissions Handbook [Internet]. In Submitting Sequences using Specific NCBI Submission Tools. Bethesda (MD): National Center for Biotechnology Information (US).     
	     
	Ostaff, D. (1985). Age distribution of European larch canker in New Brunswick. Plant Disease 69, 796-798.     
	     
	Quinlan, A. R. and Hall, I. M. (2010). BEDTools: a flexible suite of utilities for comparing genomic features. Bioinformatics 26, 841-842.     
	     
	Schmieder, R. and Edwards, R. (2011). Quality control and preprocessing of metagenomic datasets. Bioinformatics 27, 863-864.     
	     
	Simão, F. A., Waterhouse, R. M., Ioannidis, P., Kriventseva, E. V. and Zdobnov, E. M. (2015). BUSCO: assessing genome assembly and annotation completeness with single-copy orthologs. Bioinformatics 31, 3210-3212.     
	     
	Simpson, R. A. and Harrison, K. J. (1993). First report of European larch canker on Prince Edward Island, Canada. Plant Disease 77, 1264.     
	     
	Smit, A. and Hubley, R. (2017). RepeatModeler Open-1.0.11. Available fom http://www.repeatmasker.org.     
	     
	Smit, A., Hubley, R. and Green, P. (2016). RepeatMasker Open-4.0. 2015. Google Scholar.     
	     
	Stanke, M., Diekhans, M., Baertsch, R. and Haussler, D. (2008). Using native and syntenically mapped cDNA alignments to improve *de novo* gene finding. Bioinformatics 24, 637-644.     
	     
	Stanke, M. and Waack, S. (2003). Gene prediction with a hidden Markov model and a new intron submodel. Bioinformatics 19, ii215-ii225.     
	     
	Tate, R., Hall, B. and DeRego, T. (2014). Annie: The ANNotation Information Extractor (Version 1.0).     
	     
	Ter-Hovhannisyan, V., Lomsadze, A., Chernoff, Y. O. and Borodovsky, M. (2008). Gene prediction in novel fungal genomes using an *ab initio* algorithm with unsupervised training. Genome research, gr. 081612.108.     
	     
	USDA/APHIS. (2012). Supporting Document: Plants for Planting Quarantine Pest Evaluation Data Sheet. Washington, DC.    
	     
	Waterhouse, R. M., Seppey, M., Simão, F. A., Manni, M., Ioannidis, P., Klioutchnikov, G., Kriventseva, E. V. and Zdobnov, E. M. (2017). BUSCO applications from quality assessments to gene prediction and phylogenomics. Molecular biology and evolution 35, 543-548.     
	     
	Yde‐Andersen, A. (1979). Host spectrum, host morphology and geographic distribution of larch canker, *Lachnellula willkommii*. Forest Pathology 9, 211-219.     
