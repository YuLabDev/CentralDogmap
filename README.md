# CentralDogmap

![Schema](schema.png?raw=true "Schema")

### Data Sources
- UniProt x RefSeq Protein: ftp://ftp.uniprot.org/pub/databases/uniprot/current_release/knowledgebase/idmapping/by_organism/HUMAN_9606_idmapping.dat.gz and ftp://ftp.uniprot.org/pub/databases/uniprot/current_release/knowledgebase/idmapping/by_organism/HUMAN_9606_idmapping_selected.tab.gz
- UniProt x Ensembl: *ftp://ftp.uniprot.org/pub/databases/uniprot/current_release/knowledgebase/taxonomic_divisions/uniprot_sprot_human.dat.gz and ftp://ftp.uniprot.org/pub/databases/uniprot/current_release/knowledgebase/taxonomic_divisions/uniprot_trembl_human.dat.gz
- UniProt x PDB: [split_xml directory](ftp://ftp.ebi.ac.uk/pub/databases/msd/sifts/split_xml/)
- GRCh38 x dbSNP: [ASN1_flat directory](ftp://ftp.ncbi.nih.gov/snp/organisms/human_9606_b151_GRCh38p7/ASN1_flat/)
- Ensembl Protein x Ensembl Transcript: [Homo_sapiens.GRCh38.pep.all.fa.gz](ftp://ftp.ensembl.org/pub/current_fasta/homo_sapiens/pep/Homo_sapiens.GRCh38.pep.all.fa.gz)
- Ensembl Transcript x Ensembl Gene: [Homo_sapiens.GRCh38.cds.all.fa.gz](ftp://ftp.ensembl.org/pub/current_fasta/homo_sapiens/cds/Homo_sapiens.GRCh38.cds.all.fa.gz)
- Ensembl x RefSeq: [gene2ensembl.gz](ftp://ftp.ncbi.nlm.nih.gov/gene/DATA/gene2ensembl.gz)
- RefSeq Protein x RefSeq Transcript: [protein.gbk.gz](ftp://ftp.ncbi.nlm.nih.gov/refseq/H_sapiens/H_sapiens/protein/protein.gbk.gz)
- Ensembl Identifiers x GRCh38: [Homo_sapiens.GRCh38.92.gtf.gz](ftp://ftp.ensembl.org/pub/current_gtf/homo_sapiens/Homo_sapiens.GRCh38.92.gtf.gz)

- UniProt Sequences: [uniprot_sprot_human.dat.gz](ftp://ftp.uniprot.org/pub/databases/uniprot/current_release/knowledgebase/taxonomic_divisions/uniprot_sprot_human.dat.gz) and [uniprot_trembl_human.dat.gz](ftp://ftp.uniprot.org/pub/databases/uniprot/current_release/knowledgebase/taxonomic_divisions/uniprot_trembl_human.dat.gz)
- Ensembl Protein Sequences: [Homo_sapiens.GRCh38.pep.all.fa.gz](ftp://ftp.ensembl.org/pub/current_fasta/homo_sapiens/pep/Homo_sapiens.GRCh38.pep.all.fa.gz)
- Ensembl Transcript Sequences: [Homo_sapiens.GRCh38.cds.all.fa.gz](ftp://ftp.ensembl.org/pub/current_fasta/homo_sapiens/cds/Homo_sapiens.GRCh38.cds.all.fa.gz)
- RefSeq Protein Sequences: [protein.gbk.gz](ftp://ftp.ncbi.nlm.nih.gov/refseq/H_sapiens/H_sapiens/protein/protein.gbk.gz)
- Refseq Transcript Sequences: [rna.fa.gz](ftp://ftp.ncbi.nlm.nih.gov/refseq/H_sapiens/H_sapiens/RNA/rna.fa.gz)

- Ensembl Chromosomal Positions: [Homo_sapiens.GRCh38.92.gtf.gz](ftp://ftp.ensembl.org/pub/current_gtf/homo_sapiens/Homo_sapiens.GRCh38.92.gtf.gz)
- RefSeq Transcript Chromosomal Positions: [ref_GRCh38.p12_top_level.gff3.gz](ftp://ftp.ncbi.nlm.nih.gov/refseq/H_sapiens/H_sapiens/GFF/ref_GRCh38.p12_top_level.gff3.gz)