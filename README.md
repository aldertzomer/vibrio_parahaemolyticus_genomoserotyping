## Development of Kaptive databases for Vibrio parahaemolyticus O- and K-antigen serotyping

Linda van der Graaf – van Bloois<sup>1,2</sup>, Hongyou Chen<sup>3</sup>, Jaap A. Wagenaar<sup>1,2,4</sup> and Aldert L. Zomer<sup>1,2</sup>

<sup>1</sup> Department of Infectious Diseases and Immunology, Faculty of Veterinary Medicine, Utrecht University, the Netherlands<p>
<sup>2</sup> WHO Collaborating Centre for Campylobacter / OIE Reference Laboratory for Campylobacteriosis<p>
<sup>3</sup> Shanghai Municipal Center for Disease Control and Prevention, No. 1380, Zhong Shan Xi Rd., Shanghai 200336, PR China<p>
<sup>4</sup> Wageningen Bioveterinary Research, Lelystad, the Netherlands<p>

Running title: Development of V. parahaemolyticus O- and K-antigen Kaptive databases

Corresponding author: Aldert Zomer

## Vibrio parahaemolyticus loci available in V1.0 release (see below for a table)
O: OL1, OL1-1, OL2, OL3-or-OL13, OL4, OL4-1, OL5, OL6, OL7, OL7-1, OL8, OL9, OL10, OL11, OL12, OL14, OL15, OL16, and a novel one: OL101

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
https://www.microbiologyresearch.org/content/journal/mgen/10.1099/mgen.0.001007

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

 
## K Loci table
  
| K-serotype           | K-locus name | Availability                           | Reference genome | Sequences obtained from | Accession number |
|----------------------|--------------|----------------------------------------|------------------|-------------------------|------------------|
| 1                    | KL1          | in database                            | GCA_001558495    | NCBI                    |                  |
| 2                    |              | does not exist                         |                  |                         |                  |
| 3                    | KL3          | in database                            | VP161550         | this study              |  GCA_905331795   |
| 4                    | KL4          | in database                            | GCA_001728085    | NCBI                    |                  |
| 5                    | KL5          | in database                            | GCA_001727055    | NCBI                    |                  |
| 6                    | KL6          | in database                            | VP910044         | this study              |  GCA_905332005   |
| 7                    | KL7          | in database                            | VP160417         | this study              |  GCA_905331685   |
| 8                    | KL8          | in database                            | VP830010         | this study              |  GCA_905331985   |
| 9                    | KL9          | in database                            | VP161972         | this study              |  GCA_905331865   |
| 10                   | KL10         | in database                            | GCA_000491695    | NCBI                    |                  |
| 11                   | KL11         | in database                            | GCA_000490055    | NCBI                    |                  |
| 12                   | KL12         | in database                            | VP840119         | this study              |  GCA_905331995   |
| 13                   | KL13         | in database                            | GCA_000491895    | NCBI                    |                  |
| 14                   |              | does not exist                         |                  |                         |                  |
| 15                   | KL15         | in database                            | GCA_000491775    | NCBI                    |                  |
| 16                   |              | does not exist                         |                  |                         |                  |
| 17                   | KL17         | in database                            | VP170142         | this study              |  GCA_905331935   |
| 18                   | KL18         | in database                            | VP160919         | this study              |  GCA_905331745   |
| 19                   | KL19         | in database                            | GCA_000958655.1  | NCBI                    |                  |
| 20                   | KL20-1       | in database                            | GCA_001727405    | NCBI                    |                  |
| 20                   | KL20         | in database                            | VP161621         | this study              |  GCA_905331805   |
| 21                   | KL21         | in database                            | GCA_000454245    | NCBI                    |                  |
| 22                   | KL22         | in database                            | VP180431         | this study              |  GCA_905331925   |
| 23                   | KL23         | in database                            | GCA_001728345    | NCBI                    |                  |
| 24                   | KL24         | in database                            | 20521            | this study              |  GCA_905331545   |
| 25                   | KL25         | in database                            | VP860051         | this study              |  GCA_905331975   |
| 26                   |              | no isolate/genome with this K serotype |                  |                         |                  |
| 27                   |              | does not exist                         |                  |                         |                  |
| 28                   | KL28         | in database                            | VP160534         | this study              |  GCA_905331725   |
| 29                   | KL29         | in database                            | VP170038         | this study              |  GCA_905331875   |
| 30                   | KL30-1       | in database                            | GCA_001726685    | NCBI                    |                  |
| 30                   | KL30         | in database                            | GCA_001728725    | NCBI                    |                  |
| 31                   | KL31         | in database                            | VP100010         | this study              |  GCA_905331655   |
| 32                   | KL32         | in database                            | 20528            | this study              |  GCA_905331555   |
| 33                   | KL33         | in database                            | GCA_002153875    | NCBI                    |                  |
| 34                   | KL34         | in database                            | GCA_000707705    | NCBI                    |                  |
| 35                   |              | does not exist                         |                  |                         |                  |
| 36                   | KL36         | in database                            | VP161613         | this study              |  GCA_905331785   |
| 37                   | KL37         | in database                            | GCA_001975475    | NCBI                    |                  |
| 38                   | KL38         | in database                            | VP180960         | this study              |  GCA_905331965   |
| 39                   | KL39         | in database                            | GCA_001727735    | NCBI                    |                  |
| 40                   | KL40         | in database                            | 20535            | this study              |  GCA_905331575   |
| 41                   | KL41         | in database                            | VP180363         | this study              |  GCA_905331945   |
| 42                   | KL42         | in database                            | GCA_001727105    | NCBI                    |                  |
| 43                   | KL43         | in database                            | 20538            | this study              |  GCA_905331585   |
| 44                   | KL44         | in database                            | VP160968         | this study              |  GCA_905331755   |
| 45                   | KL45         | in database                            | VP180089         | this study              |  GCA_905331955   |
| 46                   | KL46         | in database                            | VP160552         | this study              |  GCA_905331715   |
| 47                   | KL47         | in database                            | 20542            | this study              |  GCA_905331615   |
| 48                   | KL48         | in database                            | VP120269         | this study              |  GCA_905331665   |
| 49                   | KL49         | in database                            | GCA_002154055    | NCBI                    |                  |
| 50                   | KL50         | in database                            | 20545            | this study              |  GCA_905331595   |
| 51                   | KL51         | in database                            | VP120841         | this study              |  GCA_905331695   |
| 52                   | KL52         | in database                            | VP180273         | this study              |  GCA_905331905   |
| 53                   | KL53         | in database                            | GCA_001728135    | NCBI                    |                  |
| 54                   | KL54         | in database                            | GCA_000958585    | NCBI                    |                  |
| 55                   | KL55         | in database                            | VP180179         | this study              |  GCA_905331915   |
| 56                   | KL56         | in database                            | VP161624         | this study              |  GCA_905331825   |
| 57                   | KL57         | in database                            | GCA_002150155    | NCBI                    |                  |
| 58                   | KL58         | in database                            | GCA_001609345    | NCBI                    |                  |
| 59                   | KL59         | in database                            | VP162119         | this study              |  GCA_905331845   |
| 60                   | KL60         | in database                            | VP161546         | this study              |  GCA_905331765   |
| 61                   | KL61         | in database                            | 20556            | this study              |  GCA_905331605   |
| 62                   |              | does not exist                         |                  |                         |                  |
| 63                   | KL63         | in database                            | VP162129         | this study              |  GCA_905331855   |
| 64                   | KL64         | in database                            | GCA_001856035    | NCBI                    |                  |
| 65                   | KL65         | in database                            | 20564            | this study              |  GCA_905331625   |
| 66                   | KL66         | in database                            | 20565            | this study              |  GCA_905331645   |
| 67                   | KL67         | in database                            | 20566            | this study              |  GCA_905331635   |
| 68                   | KL68         | in database                            | GCA_001273575    | NCBI                    |                  |
| 68                   | KL68-1       | in database                            | GCA_001728625    | NCBI                    |                  |
| 69                   | KL69         | in database                            | GCA_000491275    | NCBI                    |                  |
| 70                   | KL70         | in database                            | GCA_001726855    | NCBI                    |                  |
| 71                   | KL71         | in database                            | VP32             | CNGB                    | CNA0007063       |
| KUT1                 | KLUT1        | in database                            | GCA_001584415    | NCBI                    |                  |
| KUT2                 | KLUT2        | in database                            | GCA_001609575    | NCBI                    |                  |
| KUT3                 | KLUT3        | in database                            | VP162105         | this study              | GCA_905331815.1  |
| KUT4                 | KLUT4        | in database                            | VP162125         | this study              | GCA_905331835.1  |
| KUT5                 | KLUT5        | in database                            | VP162180         | this study              | GCA_905331885.1  |
| KUT6                 | KLUT6        | in database                            | VP161168         | this study              | GCA_905331775.1  |
| KUT7                 | KLUT7        | in database                            | VP160744         | this study              | GCA_905331735.1  |
| KUT8                 | KLUT8        | in database                            | VP160152         | this study              | GCA_905331705.1  |
| Serotype UnTypable   |              |                                        |                  |                         |                  |
|                      | KLUT4-1      | in database                            | GCA_001726495    | NCBI                    |                  |
|                      |              |                                        |                  |                         |                  |
|                      |              |                                        |                  |                         |                  |
| Serotype Unknown/New |              |                                        |                  |                         |                  |
|                      | KL101        | in database                            | GCA_000489655    | NCBI                    |                  |
|                      | KL102        | in database                            | GCA_002221185    | NCBI                    |                  |
|                      | KL103        | in database                            | GCA_000490115    | NCBI                    |                  |
|                      | KL104        | in database                            | GCA_000500545    | NCBI                    |                  |
|                      | KL105        | in database                            | GCA_000523375    | NCBI                    |                  |
|                      | KL106        | in database                            | GCA_000591555    | NCBI                    |                  |
|                      | KL107        | in database                            | GCA_000707085    | NCBI                    |                  |
|                      | KL108        | in database                            | GCA_000732995    | NCBI                    |                  |
|                      | KL109        | in database                            | GCA_000786835    | NCBI                    |                  |
|                      | KL110        | in database                            | GCA_000877625    | NCBI                    |                  |
|                      | KL111        | in database                            | GCA_000972025    | NCBI                    |                  |
|                      | KL112        | in database                            | GCA_001268005    | NCBI                    |                  |
|                      | KL113        | in database                            | GCA_001726435    | NCBI                    |                  |
|                      | KL114        | in database                            | GCA_001268015    | NCBI                    |                  |
|                      | KL115        | in database                            | GCA_001610595    | NCBI                    |                  |
|                      | KL116        | in database                            | GCA_001273635    | NCBI                    |                  |
|                      | KL117        | in database                            | GCA_001433415    | NCBI                    |                  |
|                      | KL118        | in database                            | GCA_001608855    | NCBI                    |                  |
|                      | KL119        | in database                            | GCA_001727295    | NCBI                    |                  |
|                      | KL120        | in database                            | GCA_001727345    | NCBI                    |                  |
|                      | KL121        | in database                            | GCA_001727045    | NCBI                    |                  |
|                      | KL122        | in database                            | GCA_001727155    | NCBI                    |                  |
|                      | KL123        | in database                            | GCA_001727645    | NCBI                    |                  |
|                      | KL124        | in database                            | GCA_002018725    | NCBI                    |                  |
|                      | KL125        | in database                            | GCA_002150335    | NCBI                    |                  |
|                      | KL126        | in database                            | GCA_002153895    | NCBI                    |                  |
|                      | KL127        | in database                            | GCA_002153975    | NCBI                    |                  |
|                      | KL128        | in database                            | GCA_002154015    | NCBI                    |                  |
|                      | KL129        | in database                            | GCA_002018535    | NCBI                    |                  |
|                      | KL130        | in database                            | GCA_002144585    | NCBI                    |                  |
|                      | KL131        | in database                            | GCA_002221065    | NCBI                    |                  |
|                      | KL132        | in database                            | GCA_002221165    | NCBI                    |                  |
|                      | KL133        | in database                            | 670.938          | PATRIC                  |                  |
|                      | KL134        | in database                            | 670.90           | PATRIC                  |                  |
|                      | KL135        | in database                            | 670.812          | PATRIC                  |                  |
|                      | KL136        | in database                            | 1620393.3        | PATRIC                  |                  |
|                      | KL137        | in database                            | 670.467          | PATRIC                  |                  |
|                      | KL138        | in database                            | 670.466          | PATRIC                  |                  |
|                      | KL139        | in database                            | 670.2224         | PATRIC                  |                  |
|                      | KL140        | in database                            | 670.2093         | PATRIC                  |                  |
|                      | KL141        | in database                            | 670.2085         | PATRIC                  |                  |
|                      | KL142        | in database                            | 670.2080         | PATRIC                  |                  |
|                      | KL143        | in database                            | 670.2053         | PATRIC                  |                  |
|                      | KL144        | in database                            | 670.2033         | PATRIC                  |                  |
|                      | KL145        | in database                            | 670.1966         | PATRIC                  |                  |
|                      | KL146        | in database                            | 670.1961         | PATRIC                  |                  |
|                      | KL147        | in database                            | 670.1931         | PATRIC                  |                  |
|                      | KL148        | in database                            | 670.1914         | PATRIC                  |                  |
|                      | KL149        | in database                            | 670.1676         | PATRIC                  |                  |
|                      | KL150        | in database                            | 670.1673         | PATRIC                  |                  |
|                      | KL151        | in database                            | 670.1672         | PATRIC                  |                  |
|                      | KL152        | in database                            | 670.1657         | PATRIC                  |                  |
|                      | KL153        | in database                            | 670.1645         | PATRIC                  |                  |
|                      | KL154        | in database                            | 670.1383         | PATRIC                  |                  |
|                      | KL155        | in database                            | 670.1377         | PATRIC                  |                  |
|                      | KL156        | in database                            | 670.1351         | PATRIC                  |                  |
|                      | KL157        | in database                            | 670.1111         | PATRIC                  |                  |
