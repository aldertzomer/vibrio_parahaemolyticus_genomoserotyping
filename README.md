## Development of Kaptive databases for Vibrio parahaemolyticus O- and K-antigen serotyping

Linda van der Graaf – van Bloois<sup>1,2</sup>, Hongyou Chen<sup>3</sup>, Jaap A. Wagenaar<sup>1,2,4</sup> and Aldert L. Zomer<sup>1,2</sup>

<sup>1</sup> Department of Infectious Diseases and Immunology, Faculty of Veterinary Medicine, Utrecht University, the Netherlands<p>
<sup>2</sup> WHO Collaborating Centre for Campylobacter / OIE Reference Laboratory for Campylobacteriosis<p>
<sup>3</sup> Shanghai Municipal Center for Disease Control and Prevention, No. 1380, Zhong Shan Xi Rd., Shanghai 200336, PR China<p>
<sup>4</sup> Wageningen Bioveterinary Research, Lelystad, the Netherlands<p>

Running title: Development of V. parahaemolyticus O- and K-antigen Kaptive databases

Corresponding author: Aldert Zomer

## Vibrio parahaemolyticus serotype loci available in the database V1.0 release (see below for a table)
O: OL1, OL1-1, OL2, OL3_or_OL13, OL4, OL4-1, OL5, OL6, OL7, OL7-1, OL8, OL9, OL10, OL11, OL12, OL14, OL15, OL16, and a novel one: OL101
K: KL1, KL3, KL4, KL5, KL6, KL7, KL8, KL9, KL10, KL11, KL12, KL13, KL15, KL17, KL18, KL19, KL20-1, KL20, KL21, KL22, KL23, KL24, KL25, KL28, KL29, KL30-1, KL30, KL31, KL32, KL33, KL34, KL36, KL37, KL38, KL39, KL40, KL41, KL42, KL43, KL44, KL45, KL46, KL47, KL48, KL49, KL50, KL51, KL52, KL53, KL54, KL55, KL56, KL57, KL58, KL59, KL60, KL61, KL63, KL64, KL65, KL66, KL67, KL68, KL68-1, KL69, KL70, KL71, KLUT1, KLUT2, KLUT3, KLUT4, KLUT5, KLUT6, KLUT7, KLUT8, KLUT4-1, KL101, KL102, KL103, KL104, KL105, KL106, KL107, KL108, KL109, KL110, KL111, KL112, KL113, KL114, KL115, KL116, KL117, KL118, KL119, KL120, KL121, KL122, KL123, KL124, KL125, KL126, KL127, KL128, KL129, KL130, KL131, KL132, KL133, KL134, KL135, KL136, KL137, KL138, KL139, KL140, KL141, KL142, KL143, KL144, KL145, KL146, KL147, KL148, KL149, KL150, KL151, KL152, KL153, KL154, KL155, KL156, KL157

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

### Biorxiv
https://www.biorxiv.org/content/10.1101/2021.07.06.451262v2

### Microbial Genomics
TBA

## O loci table

| O-serotype           | O-locus name | Availability | Reference genome | Sequences obtained from | Accession number |
|----------------------|--------------|--------------|------------------|-------------------------|------------------|
| 1                    | OL1          | in database  | GCA_000430405    | NCBI                    |                  |
| 1                    | OL1-1        | in database  | 670.1382         | PATRIC                  |                  |
| 2                    | OL2          | in database  | GCA_000492075    | NCBI                    |                  |
| 3 or 13              | OL3_or_OL13  | in database  | GCA_000182345    | NCBI                    |                  |
| 4                    | OL4          | in database  | GCA_000195415    | NCBI                    |                  |
| 4                    | OL4-1        | in database  | GCA_001273555    | NCBI                    |                  |
| 5                    | OL5          | in database  | GCA_000491775    | NCBI                    |                  |
| 6                    | OL6          | in database  | GCA_001609055    | NCBI                    |                  |
| 7                    | OL7          | in database  | VP160477         | this study              |  GCA_905331675   |
| 7                    | OL7-1        | in database  | 670.2934         | PATRIC                  |                  |
| 8                    | OL8          | in database  | GCA_001006125    | NCBI                    |                  |
| 9                    | OL9          | in database  | VP160968         | this study              |  GCA_905331755   |
| 10                   | OL10         | in database  | GCA_001609715    | NCBI                    |                  |
| 11                   | OL11         | in database  | GCA_001608525    | NCBI                    |                  |
| 12                   | OL12         | in database  | VP180273         | this study              |                  |
| 14                   | OL14         | in database  | GCA_000489035    | NCBI                    |                  |
| 15                   | OL15         | in database  | GCA_002504185    | NCBI                    |                  |
| 16                   | OL16         | in database  | GCA_000489075    | NCBI                    |                  |
|                      |              |              |                  |                         |                  |
| Serotype Unknown/New |              |              |                  |                         |                  |
|                      | OL101        | in database  | 670.840          | PATRIC                  |                  |

