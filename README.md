# Clade-Specific-Marker-Analysis-of-Shotgun-Metagenomic-Data
Clade Specific Marker Analysis of Shotgun Metagenomic Data of Mouse Models of Alzheimer Disease using MetaPhlan4

# Introduction
Every child, before being born and while within the safe confines of a mother's womb, is considered to have a relatively sterile gut microbiome (Tanaka & Nakayama, 2017). After birth, the microbiota is slowly formed, and different microbes colonize different body sites and establish niches that eventually make up the individual's microbiome (Turroni et al., 2020). These early interactions with the environment play a very important role in the establishment and development of an individual’s gut microbiota. The mammalian gut is home to a diverse population of microbial communities (Parfrey et al., 2014). Over the years, the role of the gut microbiota in health and disease has been well documented in literature. 

Before we can study microbial populations and communities, we first need to sample them. Culturing microorganisms forms the basis of the field of microbiology. Researchers have historically relied on culture-based methods for studying microbes for centuries. However, our ability to study these microbial populations has always been limited by our own ability to cultivate them in the laboratory under specific conditions. It has now been well established that only a very small percentage of microbes can be cultured and the term "the great plate count anomaly" (Staley and Konopka, 1985) describes this phenomenon. Over the past few decades, we've gone a bit further in our studies and understanding of microbial life. Innovative high throughput sequencing technologies developed over the past few decades, have ushered us into the world of "big data" and granted us a way to capture complete genomes of microbial communities directly from their natural habitats and bypass the limitation of culture-based methods.  
Next Generation sequencing techniques have enabled impressive scientific discoveries and found utility in clinical practice and in academic research by allowing for high-throughput sequencing of millions of DNA fragments at a relatively lower cost compared to Sanger based sequencing methods which are only capable of sequencing single DNA fragments. In a typical NGS sequencing run, 105 - 109 individual reads (sequenced DNA fragments that reflect the order of nucleotides) may be produced depending on the approach used. These reads may then be assembled using computational tools into longer contiguous fragments called "contigs" or aligned to a reference genome for identification (Dulanto Chiang & Dekker, 2019). Metagenomics refers to the utilization of genomic based methodologies for investigating microbial communities directly within their natural habitats thereby eliminating the necessity of culturing organisms (Chen & Pachter, 2005). In metagenomic research, two approaches may be considered – a targeted approach or an untargeted approach. 

In the targeted approach, the ~1500 base pair 16s rRNA gene composed of both variable and conserved regions, is sequenced. Previous studies have shown that comparing a stable part of the genetic code could be used to infer the phylogenetic relationships of bacteria and other life forms. The use of the 16s rRNA gene for bacterial identification and taxonomy was pioneered by Woese and colleagues (Woese, 1987). For most metagenomic analysis, sequencing only a section of the 1500 bp 16rRNA region (500 bp) provides enough differentiation for identification and is relatively easier and cheaper than sequencing the entire 1500 bp 16s rRNA gene (Claridge, 2004). However, in some cases, sequencing the entirety of the 16s rRNA gene may be necessary to properly differentiate taxa or strains. Unfortunately, 16s rRNA sequencing can only give us an idea as to which microbial populations are present in a sample but is unable to help predict functional profiles since the method only characterizes the 16s gene. It is worth noting that, some methods such PICRUSt (Phylogenetic Investigations of Communities by Reconstruction of Unobserved States) (Langille et al., 2013)  and Tax4Fun (Wemheuer et al., 2020), have used to attempt to functionally annotate microbial communities within samples based on 16s rRNA data (Wensel et al., 2022). However, these methods are limited in their approach and do not provide as much insight when compared to shotgun metagenomics. 

Conversely, in the untargeted approach, shotgun metagenomic sequencing and RNA sequencing analyze all the DNA or RNA in each sample, respectively. It is an unbiased approach and targets the entire microbial nucleic acids isolated from a sample. This approach produces large amounts of data and provides in-depth knowledge of the microbial community composition of any sample including bacterial, fungal, protozoal, and viral communities (Ferravante et al., 2021). In summary, when compared to 16s rRNA sequencing approach, shotgun metagenomics offers more resolution and higher sensitivity. Ultimately, the approach the approach chosen will depend on several factors including the research goals, cost, and technical overhead.

Two decades after the Human project launched, researchers have conducted numerous studies to explore and investigate the role of the gut microbiota on health and disease. What role does the community composition of our gut play in disease onset and progression? What role do these populations and their relative abundance and composition play in host treatment response? And finally, how can we leverage the insights and knowledge obtained from studying the gut microbiota, to guide preventive strategies, treatment decisions, and manage disease progression? Dysbiosis of the gut and its role in neurodegenerative disease progression is receiving significant research interests and developing at a fast pace. In Alzheimer's disease, there is growing evidence of association of alternance of the gut microbiota and Alzheimer's disease progression. In this study, we employed a shotgun metagenomics approach to profile the gut microbial community composition of transgenic 3xTg-AD mouse models of Alzheimer's disease sampled at 2 months, 6 months and 12 months using clade specific marker genes using the MetaPhAn4 computational profiling tool (Blanco-Miguez et al., 2022).  We examined how the bacterial communities profiles evolve over time in Wild Type (WT) mice and Alzheimer's Disease (AD) mice at different time points. 

# Methods

TODO







# References
1.	Tanaka, M., &amp; Nakayama, J. (2017). Development of the gut microbiota in infancy and its impact on health in later life. Allergology International, 66(4), 515–522. https://doi.org/10.1016/j.alit.2017.07.010
2.	Turroni, F., Milani, C., Duranti, S. et al. The infant gut microbiome as a microbial organ influencing host well-being. Ital J Pediatr 46, 16 (2020). https://doi.org/10.1186/s13052-020-0781-0

3.	Parfrey, L. W., Walters, W. A., Lauber, C. L., Clemente, J. C., Berg-Lyons, D., Teiling, C., Kodira, C., Mohiuddin, M., Brunelle, J., Driscoll, M., Fierer, N., Gilbert, J. A., &amp; Knight, R. (2014). Communities of microbial eukaryotes in the mammalian gut within the context of environmental eukaryotic diversity. Frontiers in Microbiology, 5. https://doi.org/10.3389/fmicb.2014.00298
4.	Chen, K., & Pachter, L. (2005). Bioinformatics for whole-genome shotgun sequencing of Microbial Communities. PLoS Computational Biology, 1(2). https://doi.org/10.1371/journal.pcbi.0010024 
5.	Clarridge, J. E. (2004). IMPACT OF 16S rrna gene sequence analysis for identification of bacteria on clinical microbiology and infectious diseases. Clinical Microbiology Reviews, 17(4), 840–862. https://doi.org/10.1128/cmr.17.4.840-862.2004 
6.	Woese, C. R. (1987). Bacterial evolution. Microbiological Reviews, 51(2), 221–271. https://doi.org/10.1128/mr.51.2.221-271.1987 
7.	Langille, M. G., Zaneveld, J., Caporaso, J. G., McDonald, D., Knights, D., Reyes, J. A., Clemente, J. C., Burkepile, D. E., Vega Thurber, R. L., Knight, R., Beiko, R. G., & Huttenhower, C. (2013). Predictive functional profiling of microbial communities using 16S rrna marker gene sequences. Nature Biotechnology, 31(9), 814–821. https://doi.org/10.1038/nbt.2676 
8.	Wemheuer, F., Taylor, J. A., Daniel, R., Johnston, E., Meinicke, P., Thomas, T., & Wemheuer, B. (2020). Tax4Fun2: Prediction of habitat-specific functional profiles and functional redundancy based on 16S rrna gene sequences. Environmental Microbiome, 15(1). https://doi.org/10.1186/s40793-020-00358-7 
9.	Wensel, C. R., Pluznick, J. L., Salzberg, S. L., & Sears, C. L. (2022). Next-generation sequencing: Insights to advance clinical investigations of the microbiome. Journal of Clinical Investigation, 132(7). https://doi.org/10.1172/jci154944 
10.	Ferravante, C., Memoli, D., Palumbo, D. et al. HOME-BIO (sHOtgun MEtagenomic analysis of BIOlogical entities): a specific and comprehensive pipeline for metagenomic shotgun sequencing data analysis. BMC Bioinformatics 22 (Suppl 7), 106 (2021). https://doi.org/10.1186/s12859-021-04004-y
11.	Blanco-Miguez, A., Beghini, F., Cumbo, F., McIver, L. J., Thompson, K. N., Zolfo, M., Manghi, P., Dubois, L., Huang, K. D., Thomas, A. M., Piccinno, G., Piperni, E., Punčochář, M., Valles-Colomer, M., Tett, A., Giordano, F., Davies, R., Wolf, J., Berry, S. E., … Segata, N. (2022). Extending and Improving Metagenomic Taxonomic Profiling with Uncharacterized Species with Metaphlan 4. https://doi.org/10.1101/2022.08.22.504593







