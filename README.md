# svfindermanual 
### A guide to installing, using, and interpreting structural variant discovery tools

### BACKGROUND
<p>
<img src=https://media.nature.com/m685/nature-assets/nmeth/journal/v9/n2/images/nmeth.1858-F1.jpg alt="structural variants" width=300 align="right">
</p>
Structural variants are genetic mutations that occur at more than one nucleotide (which would be a <a href="https://ghr.nlm.nih.gov/primer/genomicresearch/snp">SNP</a>). They include deletions, insertions, duplications, copy number variants (CNVs), inversions, translocations, and large chromosomal rearrangements. Definitions may vary as some geneticists define a true structural variant as a mutation affecting from 1 kilobase to 3 megabases, which is the general range the tools described herein affect.
<br>
<br>
I've done quite a bit of work on structural variant detection from whole genome sequence data and found the tools among some of the most difficult programs to work with that I've encountered as a bioinformatician. Therefore, I've created this resource for other researchers that explains in simple terms how to use these methods. As I figure out more tools and combination methods I will add to it.

### TOOLS
I'm starting with the tools whose output is combined by the machine learning method FusorSV. I will also include information on how to install and run FusorSV.

Tool | Documentation written | Installed on Hoffman2 | Wrapper available | Example runs available | Example output available
-----|-----------------------|-----------------------|-------------------|------------------------|-------------------------
[LUMPY](https://github.com/samanthaleejensen/svfindermanual/wiki/LUMPY) | ✓ | ✓ | ✓ | ✓ | ✓ 
[BreakDancer](https://github.com/samanthaleejensen/svfindermanual/wiki/BreakDancer) | ✗ | ✓ | ✓ | ✓ | ✓
[Genome STRiP](https://github.com/samanthaleejensen/svfindermanual/wiki/Genome-STRiP) | ✗ | ✓ | ✗ | ✗ | ✗
[CNVnator](https://github.com/samanthaleejensen/svfindermanual/wiki/CNVnator) | ✗ | ✓ | ✓ | ✗ | ✗
[BreakSeq](https://github.com/samanthaleejensen/svfindermanual/wiki/BreakSeq) | ✗ | ✓ | ✗ | ✗ | ✗
[cn.MOPS](https://github.com/samanthaleejensen/svfindermanual/wiki/cn.MOPS) | ✗ | ✓ | ✗ | ✗ | ✗
[DELLY](https://github.com/samanthaleejensen/svfindermanual/wiki/DELLY) | ✗ | ✓ | ✓ | ✗ | ✗
**_[FusorSV](https://github.com/samanthaleejensen/svfindermanual/wiki/FusorSV)_** | **_✗_** | **_✓_** | **_✓_** | **_✗_** | **_✗_**

### For all explanations, see the [wiki](https://github.com/samanthaleejensen/svfindermanual/wiki).

I'm a graduate student at UCLA and will also push accessible scripts I write to run these tools on UCLA's Hoffman2 supercomputer. They might not be useful to you at another institution, but they can show you examples of how to make the tools work on a system where you don't have root access.

Most of my scripts are based on the work of Huajun Zhou and Jerome Luo for Dr. Jae Hoon Sul. You can find Huajun's work at https://github.com/hjzhou988/Structural_Variants_pipeline.
