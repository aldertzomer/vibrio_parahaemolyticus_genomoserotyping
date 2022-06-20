## Development of Kaptive databases for Vibrio parahaemolyticus O- and K-antigen serotyping

Linda van der Graaf – van Bloois<sup>1,2</sup>, Hongyou Chen<sup>3</sup>, Jaap A. Wagenaar<sup>1,2,4</sup> and Aldert L. Zomer<sup>1,2</sup>

<sup>1</sup> Department of Infectious Diseases and Immunology, Faculty of Veterinary Medicine, Utrecht University, the Netherlands<p>
<sup>2</sup> WHO Collaborating Centre for Campylobacter / OIE Reference Laboratory for Campylobacteriosis<p>
<sup>3</sup> Shanghai Municipal Center for Disease Control and Prevention, No. 1380, Zhong Shan Xi Rd., Shanghai 200336, PR China<p>
<sup>4</sup> Wageningen Bioveterinary Research, Lelystad, the Netherlands<p>


Running title: Development of V. parahaemolyticus O- and K-antigen Kaptive databases

Corresponding author: Aldert Zomer
 
## Abstract

Vibrio parahaemolyticus is an important food-borne human pathogen and is divided in 16 O-serotypes and 71 K-serotypes. Agglutination tests are still the gold standard for serotyping, but many V. parahaemolyticus isolates are not typable by agglutination. An alternative for agglutination tests is serotyping using whole genome sequencing data. In this study, V. parahaemolyticus isolates are serotyped and sequenced, and all known and several novel O- and K-loci are identified. We developed Kaptive databases for all O- and K-loci after manual curation of the loci. These Kaptive databases with the identified V. parahaemolyticus O- and K -loci can be used to identify the O- and K-serotypes of V. parahaemolyticus isolates from genome sequences. 


## Getting Kaptive
Download Kaptive from https://github.com/katholt/Kaptive and install the software following the instructions on that page

## Using the Vibrio parahaemolyticus database
```
$ git clone https://github.com/aldertzomer/vibrio_parahaemolyticus_genomoserotyping.git
$ kaptive -k vibrio_parahaemolyticus_genomoserotyping.git/VibrioPara_Kaptivedb_K.gbk -a path/to/assemblies/*.fasta -o output
$ kaptive -k vibrio_parahaemolyticus_genomoserotyping.git/VibrioPara_Kaptivedb_O.gbk -a path/to/assemblies/*.fasta -o output
```


