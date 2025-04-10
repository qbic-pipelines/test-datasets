# test-datasets
This holds test datasets specific for pipelines developed at QBiC

- `annotated.vcf.gz`: VEP annotated VCF file for filtering test of [qbic-pipelines/vcftocounts](https://github.com/qbic-pipelines/vcftocounts)
- `variantconsensus`: Holds VEP annotated VCF files for testing [qbic-pipelines/variantconsensus](https://github.com/qbic-pipelines/variantconsensus)
    - `tumor_5_vs_normal_5.muse_VEP.ann.vcf.gz`: SNPs & INDELs called with MuSE
    - `tumor_5_vs_normal_5.muse_VEP.ann.vcf.gz.tbi`: Corresponding Index
    - `tumor_5_vs_normal_5.strelka.somatic_indels_VEP.ann.vcf.gz`: INDELs called with Strelka
    - `tumor_5_vs_normal_5.strelka.somatic_indels_VEP.ann.vcf.gz.tbi`: Corresponding Index
    - `tumor_5_vs_normal_5.strelka.somatic_snvs_VEP.ann.vcf.gz`: SNPs called with Strelka
    - `tumor_5_vs_normal_5.strelka.somatic_snvs_VEP.ann.vcf.gz.tbi`: Corresponding Index
