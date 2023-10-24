methclone: Detect the dynamic evolution of clonal epialleles in DNA methylation sequencing data.
version: 0.1

==Installation==
cd /path/to/methclone/src/utils/BamTools/
mkdir -p lib
make
cd /path/to/methclone/src/utils/gzstream/
make 
cd /path/to/methclone/src/
mkdir -p ../bin
make

==Usage==
./methclone stage1.bam stage2.bam output.txt.gz sampleID

==Example==
cd /path/to/methclone/
./bin/methclone example/chr22-stage1.bam example/chr22-stage2.bam example/chr22.output.txt.gz chr22-1-2


Method
Open access
Published: 27 September 2014
[Dynamic evolution of clonal epialleles revealed by methclone](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-014-0472-5)
**Sheng Li**, Francine Garrett-Bakelman, Alexander E Perl, Selina M Luger, Chao Zhang, Bik L To, Ian D Lewis, Anna L Brown, Richard J D’Andrea, M Elizabeth Ross, Ross Levine, Martin Carroll, Ari Melnick & Christopher E Mason 
Genome Biology volume 15, Article number: 472 (2014) Cite this article

7624 Accesses

55 Citations

8 Altmetric

Metricsdetails

