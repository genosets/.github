# genosets

> **⚠️ This organization is archived and will be deleted in the future.**
> All repositories are preserved as local backups. No further development will occur.

---

Genosets was a personal passion project from around 2013 — a Node.js-based toolkit for doing
amateur analysis of your own raw genome data, primarily from consumer services like 23andMe.
The idea was to build a small ecosystem of composable modules (called *genosets*) that each
evaluated a specific set of SNPs using a streaming query interface called GQL, with `dna2json`
to convert raw genotype files and `AlEx` as a browser-based allele explorer on top.

It was an interesting space to explore at the time — direct-to-consumer genomics was brand new,
the DIY bioinformatics community was small and scrappy, and it felt like building useful tooling
on top of it was within reach. It never came to fruition, though. The project stalled before it
matured into anything practically useful, and in the decade-plus since, the landscape has changed
enormously — both in what commercial platforms offer and in the open-source tooling available.
If you found this org while looking for something to help with your own genomic data, you'll be
much better served by the resources below.

---

## Better alternatives for amateur genomic research

### Analyze your own DNA data
Personal genome files from 23andMe, AncestryDNA, MyHeritage, etc. can be uploaded to several
well-maintained platforms:

- **[Promethease](https://promethease.com/)** — Cross-references your SNPs against SNPedia, the
  most comprehensive community-maintained catalog of SNP-phenotype literature. The go-to for
  serious self-research.
- **[Genomelink](https://genomelink.io/)** — Trait analysis, ancestry, and ancient DNA across 350+
  reports; accepts most major raw data formats.
- **[SelfDecode](https://selfdecode.com/)** — Health-focused trait interpretation with free reports.
- **[OpenSNP](https://opensnp.org/)** — Open repository where users voluntarily share their raw
  genotype data and phenotypes; useful for community-level research.

### Citizen science & research participation
- **[SciStarter](https://scistarter.org/)** — Registry of 2,500+ citizen science projects,
  including genomics and biology; a good starting point for finding projects to contribute to.
- **[Personal Genome Project](https://www.personalgenomes.org/)** — Volunteer your genomic and
  health data to open science; one of the longest-running public genomics initiatives.
- **[All of Us Research Program](https://allofus.nih.gov/)** (NIH) — Large-scale US cohort study;
  participants receive their own genetic data back.

### Open-source bioinformatics tools
- **[Galaxy](https://usegalaxy.org/)** — Web-based, no-code platform for bioinformatics pipelines;
  no local installation required, extensive documentation.
- **[BLAST](https://blast.ncbi.nlm.nih.gov/)** — NCBI's sequence alignment tool; the foundation
  of almost all comparative genomics work.
- **[Bioconductor](https://www.bioconductor.org/)** — 1,500+ R packages for genomic data analysis,
  with thorough documentation and an active community.
- **[Biopython](https://biopython.org/)** — Python toolkit for biological computing; good entry
  point if you're a programmer wanting to work with sequence data directly.

### Learning resources
- **[Bioinformatics Specialization](https://www.coursera.org/specializations/bioinformatics)**
  (UC San Diego / Coursera) — Highly regarded, free to audit; starts from the DNA level and
  builds up to algorithms.
- **[Rosalind](https://rosalind.info/)** — Problem-based bioinformatics learning platform;
  teaches concepts through progressively harder coding challenges.
- **[The Biostar Handbook](https://www.biostarhandbook.com/)** — Practical, hands-on guide to
  bioinformatics for self-learners.

### Communities
- **[Biostars](https://www.biostars.org/)** — Long-running Q&A forum for bioinformatics; well-indexed and active.
- **[SEQanswers](https://www.seqanswers.com/)** — Community focused on next-generation sequencing analysis.
- **[r/Bioinformatics](https://www.reddit.com/r/bioinformatics/)** — Approachable Reddit community for beginners and practitioners alike.

---

*The code is left public for historical reference under its original licenses.*
