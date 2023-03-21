## Development of Kaptive databases for Vibrio parahaemolyticus O- and K-antigen serotyping

Linda van der Graaf – van Bloois<sup>1,2</sup>, Hongyou Chen<sup>3</sup>, Jaap A. Wagenaar<sup>1,2,4</sup> and Aldert L. Zomer<sup>1,2</sup>

<sup>1</sup> Department of Infectious Diseases and Immunology, Faculty of Veterinary Medicine, Utrecht University, the Netherlands<p>
<sup>2</sup> WHO Collaborating Centre for Campylobacter / OIE Reference Laboratory for Campylobacteriosis<p>
<sup>3</sup> Shanghai Municipal Center for Disease Control and Prevention, No. 1380, Zhong Shan Xi Rd., Shanghai 200336, PR China<p>
<sup>4</sup> Wageningen Bioveterinary Research, Lelystad, the Netherlands<p>

Running title: Development of V. parahaemolyticus O- and K-antigen Kaptive databases
Corresponding author: Aldert Zomer

## Impact Statement
Serotyping is one of the most used methods for identification and epidemiology of pathogens. Agglutination tests are still the gold standard for serotyping V. parahaemolyticus isolates, however these tests are costly and time consuming. An alternative is using genome sequences for molecular epidemiology through sequence typing, however the sequence type does not always translate directly to serotype. An alternative for agglutination tests is genotyping; predicting the serotype from whole genome sequencing data. In our study we manually curated genotyping databases for V. parahaemolyticus for all known and several novel O- and K-loci. By using the genotyping tool Kaptive we could genotype the O- and K-locus of 98% and 93% of the genomes respectively with a Kaptive confidence score higher than “None”. The newly developed Kaptive databases with the identified V. parahaemolyticus O- and K -loci can be used to identify the O- and K-genotypes of V. parahaemolyticus isolates from genome sequences. 

## Abstract
Vibrio parahaemolyticus is an important food-borne human pathogen and presents immunogenic surface polysaccharides, which can be used to distinguish problematic and disease-causing lineages. V. parahaemolyticus is divided in 16 O-serotypes (O-antigen) and 71 K-serotypes (K-antigen). Agglutination tests are still the gold standard for serotyping, but many V. parahaemolyticus isolates are not typable by agglutination. An alternative for agglutination tests is genotyping using whole genome sequencing data, by which K- and O- genotypes have been curated and identified previously for other clinically relevant organisms with the software tool Kaptive. In this study, V. parahaemolyticus isolates are serotyped and sequenced, and all known and several novel O- and K-loci are identified. We developed Kaptive databases for all O- and K-loci after manual curation of the loci. In our study, we could genotype the O- and K-locus of 98% and 93% of the genomes respectively with a Kaptive confidence score higher than “None”. The newly developed Kaptive databases with the identified V. parahaemolyticus O- and K -loci can be used to identify the O- and K-genotypes of V. parahaemolyticus isolates from genome sequences. 

## Getting Kaptive
Download Kaptive from https://github.com/katholt/Kaptive and install the software following the instructions on that page

## Using the Vibrio parahaemolyticus database
```
$ git clone https://github.com/aldertzomer/vibrio_parahaemolyticus_genomoserotyping.git
$ kaptive -k vibrio_parahaemolyticus_genomoserotyping.git/VibrioPara_Kaptivedb_K.gbk -a path/to/assemblies/*.fasta -o output
$ kaptive -k vibrio_parahaemolyticus_genomoserotyping.git/VibrioPara_Kaptivedb_O.gbk -a path/to/assemblies/*.fasta -o output
```

## Link to published manuscripts

###Biorxiv
https://www.biorxiv.org/content/10.1101/2021.07.06.451262v2

###Microbial Genomics
TBA



