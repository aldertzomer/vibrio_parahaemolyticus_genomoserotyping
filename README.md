## Development of Kaptive databases for Vibrio parahaemolyticus O- and K-antigen serotyping

Linda van der Graaf – van Bloois<sup>1,2</sup>, Hongyou Chen<sup>3</sup>, Jaap A. Wagenaar<sup>1,2,4</sup> and Aldert L. Zomer<sup>1,2</sup>

<sup>1</sup> Department of Infectious Diseases and Immunology, Faculty of Veterinary Medicine, Utrecht University, the Netherlands<p>
<sup>2</sup> WHO Collaborating Centre for Campylobacter / OIE Reference Laboratory for Campylobacteriosis<p>
<sup>3</sup> Shanghai Municipal Center for Disease Control and Prevention, No. 1380, Zhong Shan Xi Rd., Shanghai 200336, PR China<p>
<sup>4</sup> Wageningen Bioveterinary Research, Lelystad, the Netherlands<p>


Running title: Development of V. parahaemolyticus O- and K-antigen Kaptive databases

Corresponding author: Aldert Zomer
 
## Abstract

Vibrio parahaemolyticus is an important food-borne human pathogen and is divided in 16 O-serotypes and 71 K-serotypes. Agglutination tests are still the gold standard for serotyping, but many V. parahaemolyticus isolates are not typable by agglutination. An alternative for agglutination tests is serotyping using genome sequences. In this study, we manually identified all O- and K-loci from publicly available genomes and in-house sequenced V. parahaemolyticus isolates which we serotyped, and developed Kaptive databases for all O- and K-loci. These Kaptive databases with the identified V. parahaemolyticus O- and K -loci can be used to identify the O- and K-serotypes of V. parahaemolyticus isolates from whole genome sequencing data. 


## Getting Kaptive
Download Kaptive from https://github.com/katholt/Kaptive and install the software following the instructions on that page

## Using the Vibrio parahaemolyticus database
```
$ git clone https://github.com/aldertzomer/vibrio_parahaemolyticus_genomoserotyping.git
$ kaptive -k vibrio_parahaemolyticus_genomoserotyping.git/vibriopara_K_kaptivedb_v3.gbk -a path/to/assemblies/*.fasta -o output
$ kaptive -k vibrio_parahaemolyticus_genomoserotyping.git/vibriopara_O_kaptivedb_v2.gbk -a path/to/assemblies/*.fasta -o output
```


