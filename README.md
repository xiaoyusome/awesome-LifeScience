### **Awesome LifeScience**

A collection of awesome things regarding the LifeScience.

## Contents
- [Tools](#tools)
- [Pipelines](#pipelines)
- [Datasets](#datasets)
- [Visualization](#visualization)
- [Learn](#learn)
- [RunAndTests](#run)

## Tools
- DataDownload
    - [GGD](https://github.com/gogetdata/ggd-cli) - The command line interface for gogetdata
    - [SRA-Exporer](https://github.com/ewels/sra-explorer) - Mini web application to explore the NCBI Sequence Read Archive and easily access downloads for data, either as .sra files from the NCBI or as .fastq via the EBI ENA.

- DataCompress
    - [Genozip](https://github.com/divonlan/genozip) - Genozip is a universal compressor for genomic files - it compresses FASTQ, BAM/CRAM, VCF and many other file formats (including non-genomic files)

- Genomics
    - [AfterQC](https://github.com/OpenGene/AfterQC) - Automatic Filtering, Trimming, Error Removing and Quality Control for fastq data. 
    - [Bowtie 2](https://github.com/BenLangmead/bowtie2) - An ultrafast and memory-efficient tool for aligning sequencing reads to long reference sequences. 
    - [BWA](https://github.com/lh3/bwa) - Burrow-Wheeler Aligner for pairwise alignment between DNA sequences.
    - [Bamtools](https://github.com/pezmaster31/bamtools) - Collection of tools for working with BAM files. 
    - [bcftools](https://github.com/samtools/bcftools) - samtools/bcftools are a suite of tools for manipulating NGS data and can be used to call variants.
    - [bam toolbox](https://github.com/AndersenLab/bam-toolbox) MtDNA:Nuclear Coverage; BAM Toolbox can output the ratio of MtDNA:nuclear coverage, a proxy for mitochondrial content.
    - [Cufflinks](https://github.com/cole-trapnell-lab/cufflinks) - Cufflinks assembles transcripts, estimates their abundances, and tests for differential expression and regulation in RNA-Seq samples.
    - [Delly](https://github.com/dellytools/delly)- Structural variant discovery by integrated paired-end and split-read analysis.
    - [DeepVariant](https://github.com/google/deepvariant) - Deep learning-based variant caller
    - [fastp](https://github.com/OpenGene/fastp) - A tool designed to provide fast all-in-one preprocessing for FastQ files. This tool is developed in C++ with multithreading supported to afford high performance.
    - [FastQC](https://github.com/s-andrews/FastQC) - A quality control tool for high throughput sequence data.
    - [Fastqp](https://github.com/mdshw5/fastqp) - FASTQ and SAM quality control using Python.
    - [Fastx Tookit](https://github.com/agordon/fastx_toolkit) - FASTQ/A short-reads pre-processing tools: Demultiplexing, trimming, clipping, quality filtering, and masking utilities.
    - [freebayes](https://github.com/ekg/freebayes) - Bayesian haplotype-based polymorphism discovery and genotyping.
    - [GATK](https://github.com/broadinstitute/gatk) - Variant Discovery in High-Throughput Sequencing Data. 
    - [gridss](https://github.com/PapenfussLab/gridss) - GRIDSS: the Genomic Rearrangement IDentification Software Suite.
    - [lumpy](https://github.com/arq5x/lumpy-sv) - lumpy: a general probabilistic framework for structural variant discovery.
    - [MultiQC](https://github.com/ewels/MultiQC) - Aggregate results from bioinformatics analyses across many samples into a single report. 
    - [MUMmer](https://github.com/mummer4/mummer) - A system for rapidly aligning entire genomes, whether in complete or draft form.
    - [MMseqs2](https://github.com/soedinglab/MMseqs2) - Ultra-fast, sensitive search and clustering suite for protein and nucleotide sequence sets.
    - [manta](https://github.com/Illumina/manta) - Structural variant and indel caller for mapped sequencing data.
    - [mergesam](https://github.com/DarwinAwardWinner/mergesam) - Automate common SAM & BAM conversions.
    - [mosdepth](https://github.com/brentp/mosdepth) - fast BAM/CRAM depth calculation for WGS, exome, or targeted sequencing.
    - [Octopus](https://github.com/luntergroup/octopus) - A polymorphic bayesian genotyping model with wide applicability. 
    - [POA](https://github.com/ljdursi/poapy) - Partial-Order Alignment for fast alignment and consensus of multiple homologous sequences.
    - [Parasail](https://github.com/jeffdaily/parasail) - SIMD C library for global, semi-global, and local pairwise sequence alignments
    - [RSEM](https://github.com/deweylab/RSEM) - A software package for estimating gene and isoform expression levels from RNA-Seq data.
    - [SeqFu](https://github.com/telatin/seqfu2) - Sequence manipulation toolkit for FASTA/FASTQ files written in Nim.
    - [SeqKit](https://github.com/shenwei356/seqkit) - A cross-platform and ultrafast toolkit for FASTA/Q file manipulation in Golang. 
    - [seqmagick](https://github.com/fhcrc/seqmagick) - file format conversion in Biopython in a convenient way.
    - [Seqtk](https://github.com/lh3/seqtk) - Toolkit for processing sequences in FASTA/Q formats.
    - [smoove](https://github.com/brentp/smoove) - structural variant calling and genotyping with existing tools, but,smoothly.
    - [smof](https://github.com/incertae-sedis/smof) - UNIX-style FASTA manipulation tools.
    - [SAMstat](https://github.com/TimoLassmann/samstat) - Displaying sequence statistics for next-generation sequencing. 
    - [Somalier](https://github.com/brentp/somalier) - Fast sample-swap and relatedness checks on BAMs/CRAMs/VCFs/GVCFs. 
    - [Telseq](https://github.com/zd1/telseq) - Telseq is a tool for estimating telomere length from whole genome sequence data. 
    - [WFA](https://github.com/smarco/WFA) - the wavefront alignment algorithm (WFA) which expoit sequence similarity to speed up alignment

- Protein
    - [alphafold](https://github.com/deepmind/alphafold) - AlphaFold is an AI system developed by DeepMind that predicts a protein’s 3D structure from its amino acid sequence. It regularly achieves accuracy competitive with experiment.


## Pipelines
- Genomics
    - Metagenome
    - [WGS](#wgs)
    - [WES](#wes)
    - single-cell
        - [scanpy](https://scanpy.readthedocs.io/en/latest/) - Single-cell analysis in Python. Scales to >1M cells.
        - [RNA-seq](#rna-seq)

## Datasets

## Visualization
- Genomics
    - General
        - [Biodalliance](http://www.biodalliance.org/) - Biodalliance is a fast, interactive, genome visualization tool that's easy to embed in web pages and applications.
        - [BasePlayer](https://baseplayer.fi/) - BasePlayer is an open source, large-scale discovery tool for genomic variants, exploiting next- and third-generation sequencing data. 
        - [Celera genome browser](https://sourceforge.net/projects/celeragb/) - A Tool for Visualizing and Annotating the Human Genome
        - [Genoverse](https://github.com/wtsi-web/Genoverse) - HTML5 scrollable genome browser
        - [GBrowse 2](http://gmod.org/wiki/GBrowse) - GBrowse is a combination of database and interactive web pages for manipulating and displaying annotations on genomes.
        - [Gosling](http://gosling-lang.org/) - Gosling.js is a declarative grammar for interactive (epi)genomics visualization on the Web.
        - [GeneViTo](http://athina.biol.uoa.gr/bioinformatics/GENEVITO/) - GeneViTo is a JAVA-based computer application that serves as a workbench for genome-wide analysis through visual interaction.
        - [Ensembl genome browser](https://useast.ensembl.org/Homo_sapiens/Location/View?r=17:63992802-64038237) - Use the Genome browser to explore a genomic region and view a gene and its transcripts in the context of the genome.
        - [Ensembl genome browser 2020 edition](http://2020.ensembl.org/) - Use the Genome browser to explore a genomic region and view a gene and its transcripts in the context of the genome.
        - [HiGlass](https://higlass.io) - HiGlass is a fast visualization tool for large Hi-C and other genomic data sets.
        - [IGB](https://bioviz.org/) - GB is a fast, flexible, and free genome browser you can use to explore & visually analyze vast genomic data.
        - [IGV](https://igv.org/) - Integrative Genomics Viewer
        - [IGV.js](https://github.com/igvteam/igv.js/) - igv.js is an embeddable interactive genome visualization component developed by the Integrative Genomics Viewer (IGV) team.
        - [JBrowse](http://jbrowse.org/jbrowse1.html) - JBrowse is a fast, scalable genome browser built completely with JavaScript and HTML5. It can run on your desktop, or be embedded in your website.
        - [JBrowse 2](http://jbrowse.org/jb2) - The mission of the JBrowse Consortium is to develop a comprehensive, pluggable, open-source computational platform for visualizing and integrating biological data.
        - [Kero-BROWSE](https://github.com/DBKERO/genome_browser) - Simple HTML5 canvas based genome browser for NGS data. KERO-browse supports several file formats such as bam(+bai) or BigWig.
        - [NCBI Genome Data Viewer](https://www.ncbi.nlm.nih.gov/genome/gdv/) -  GDV supports the exploration and analysis of NCBI-annotated and selected non-NCBI annotated eukaryotic genome assemblies.
        - [Nucleome browser](http://vis.nucleome.org/entry/)
        - [Pileup.js](https://github.com/hammerlab/pileup.js)
        - [Savant](http://bioinformatics-ca.github.io/savant_genome_browser_lab_2015/)
        - [Tablet](https://ics.hutton.ac.uk/tablet/)
        - [Trackster](https://galaxyproject.org/learn/visualization/)
        - [UCSC genome browser](https://genome.ucsc.edu/)
        - [Valis browser](https://valis.bio/)
        - [WashU epigenomics browser](https://epigenomegateway.wustl.edu/)
        - [Zenbu](http://fantom.gsc.riken.jp/zenbu/)
    - Commercial
        - [10x genomics/Loupe](https://support.10xgenomics.com/genome-exome/software/visualization/latest/structural-variants)
        - [Alamut](https://www.interactive-biosoftware.com/alamut-visual/)
        - [ATCC Genome Portal (American Type Culture Collection)](https://docs.onecodex.com/en/articles/3996697-using-the-genome-browser)
        - [Bionano](https://bionanogenomics.com/technology/structural-variation/)
        - [Benchling](https://www.benchling.com/)
        - [CLC Genomics workbench](https://digitalinsights.qiagen.com/news/blog/discovery/structural-variant-detection-using-clc-genomics-workbench/)
        - [Circa](https://omgenomics.com/circa)
        - [DNASTAR](https://www.dnastar.com/)
        - [Geneious](https://www.geneious.com/)
        - [Genestack](https://genestack.com/blog/2015/05/28/navigation-in-genestack-genome-browser/)
        - [Golden Helix](http://goldenhelix.com/GenomeBrowse/)
        - [Lucid viewer](https://lucidalign.com/)
        - [MacVector](https://macvector.com/)
        - [Persephone](https://persephonesoft.com/)
        - [SnapGene](https://www.snapgene.com/)
        - [Strand NGS](https://www.strand-ngs.com/)
    - MSA
        - [AA](http://www.bioinformatics.org/strap/aa)
        - [abrowse](https://github.com/ihh/abrowse)
        - [alignment.js](https://github.com/veg/alignment.js)
        - [AlignmentComparator](http://bioinfweb.info/AlignmentComparator/)
        - [AlignmentViewer](https://alignmentviewer.org/)
        - [AliView](http://www.ormbunkar.se/aliview/)
        - [ALVIS (MSA viewer)](https://www.ebi.ac.uk/research/goldman/software/alvis)
        - [alignfigR](https://cran.r-project.org/web/packages/alignfigR/vignettes/my-vignette.html)
        - [alen](https://github.com/jakobnissen/alen)
        - [AliTreeViz](https://www.npmjs.com/package/alitreeviz)
        - [BioJS/MSA](https://msa.biojs.net/)
        - [Boxshade](https://embnet.vital-it.ch/software/BOX_form.html)
        - [ESPript](http://espript.ibcp.fr/ESPript/ESPript/)
        - [ggtree](https://github.com/YuLab-SMU/ggtree)
        - [Jalview](https://www.jalview.org/)
        - [JSAV](http://www.bioinf.org.uk/software/jsav)
        - [MSABrowser](https://thekaplanlab.github.io/)
        - [msaR](https://github.com/zachcp/msaR)
        - [MView](https://www.ebi.ac.uk/Tools/msa/mview/)
        - [MEGA-X](https://www.megasoftware.net/)
        - [NCBI MSA Viewer](https://www.ncbi.nlm.nih.gov/projects/msaviewer/)
        - [pyBoxshade](https://github.com/mdbaron42/pyBoxshade)
        - [pymsaplotter](https://github.com/orangeSi/pymsaploter)
        - [ProViz](http://slim.icr.ac.uk/proviz/index.php)
        - [React MSAViewer](https://github.com/plotly/react-msa-viewer)
        - [react-msaview](https://github.com/GMOD/react-msaview)
        - [seqotron](https://github.com/4ment/seqotron)
        - [STRAP](http://www.bioinformatics.org/strap/)
        - [SNPViz](http://www.yeastrc.org/snipviz/4.HTML_Config_retrieve_newick_and_fasta_from_server/snip_viz_HTML_config_with_newick_clustering.html)
        - [TeXShade](http://mirrors.ibiblio.org/CTAN/macros/latex/contrib/texshade/texshade.pdf)
        - [Wasabi](http://wasabiapp.org/)
    
    - Logo
        - [LogoJS](https://logojs.wenglab.org/app/gallery/)
    
    - CNV
        - [aCNVViewer](https://github.com/FJD-CEPH/aCNViewer)
        - [BAMScale](https://github.com/ncbi/BAMscale)
        - [bctools cnv](https://samtools.github.io/bcftools/howtos/cnv-calling.html)
        - [CNVkit](https://cnvkit.readthedocs.io/en/stable/plots.html)
        - [cnvCurator](http://www.acsu.buffalo.edu/~lm69/cnvCurator)
        - [covviz](https://brwnj.github.io/covviz/)
        - [copynumber](https://www.bioconductor.org/packages/release/bioc/vignettes/copynumber/inst/doc/copynumber.pdf)
        - [GenomeSpy](https://genomespy.app/)
        - [GenomePaint](https://genomepaint.stjude.cloud/)
        - [genevisR](https://bioconductor.org/packages/release/bioc/vignettes/GenVisR/inst/doc/Intro.html)
        - [mocha](https://github.com/freeseek/mocha)
        - [PURPLE](https://github.com/hartwigmedical/hmftools/blob/master/purity-ploidy-estimator/README.md)
    - Static
        - [BAMSnap](https://github.com/parklab/bamsnap)
        - [bcftools roh](https://samtools.github.io/bcftools/howtos/roh-calling.html)
        - [ChIA-Pipe](https://github.com/TheJacksonLaboratory/ChIA-PIPE)
        - [CNView](https://github.com/RCollins13/CNView)
        - [CNVPlot](https://github.com/dantaki/CNVplot)
        - [CNVpytor](https://github.com/abyzovlab/CNVpytor)
        - [cgplot](https://github.com/dfguan/cgplot)
        - [DNAPlotLib](https://github.com/VoigtLab/dnaplotlib)
        - [ExonIntron](http://wormweb.org/exonintron)
        - [FeatureViewer](https://github.com/calipho-sib/feature-viewer)
        - [Geneviz](https://jrderuiter.github.io/geneviz/usage.html)
        - [Genome STRiP](http://software.broadinstitute.org/software/genomestrip/)
        - [GenomeTools](http://genometools.org/)
        - [GenomeView](https://github.com/nspies/genomeview)
        - [genoPlotR](http://genoplotr.r-forge.r-project.org/)
        - [ggbio](http://www.bioconductor.org/packages/2.11/bioc/vignettes/ggbio/inst/doc/ggbio.pdf)
        - [GGgenes](https://github.com/wilkox/gggenes)
        - [GGsashimi](https://github.com/guigolab/ggsashimi)
        - [gtrellis](http://bioconductor.org/packages/devel/bioc/vignettes/gtrellis/inst/doc/gtrellis.html)
        - [Gviz](https://bioconductor.org/packages/release/bioc/html/Gviz.html)
        - [Hagfish](https://github.com/mfiers/hagfish/wiki/Plots) 
        - [HiCPlotter](https://github.com/kcakdemir/HiCPlotter)
        - [JVarKit/BamToSVG](http://lindenb.github.io/jvarkit/BamToSVG.html)
        - [Lollipops](https://github.com/joiningdata/lollipops)
        - [Mason](http://www.yeastrc.org/mason/)
        - [Methplotlib](https://github.com/wdecoster/methplotlib)
        - [mummer2circos](https://github.com/metagenlab/mummer2circos)
        - [Pairoscope](http://pairoscope.sourceforge.net/)
        - [pauvre](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6991124/figure/fig-3/)
        - [pyGenomeTracks](https://github.com/deeptools/pyGenomeTracks)
        - [RACER](https://oliviasabik.github.io/RACERweb/articles/IntroToRACER.html)
        - [RepViz](https://bmcresnotes.biomedcentral.com/articles/10.1186/s13104-019-4473-z)
        - [Samplot](https://github.com/ryanlayer/samplot)
        - [SashimiPlot](https://miso.readthedocs.io/en/fastmiso/sashimi.html)
        - [shabam](https://github.com/dlrice/shabam)
        - [SparK](https://github.com/harbourlab/SparK)
        - [Spliceclust](https://github.com/pkimes/spliceclust)
        - [Sushi](https://www.bioconductor.org/packages/release/bioc/vignettes/Sushi/inst/doc/Sushi.pdf)
        - [svist4get](https://link.springer.com/article/10.1186/s12859-019-2706-8)
        - [svv](https://github.com/ryanlayer/svv)
        - [svviz](https://github.com/svviz/svviz)
        - [svviz2](https://github.com/nspies/svviz2)
        - [trackViewer](https://bioconductor.org/packages/release/bioc/vignettes/trackViewer/inst/doc/trackViewer.html)
    - Gene fusion
        - [arriba](https://github.com/suhrig/arriba)
        - [Chimeraviz](https://github.com/stianlagstad/chimeraviz)
        - [clinker (gene fusion software)](https://github.com/Oshlack/Clinker/)
        - [FusionInspector](https://github.com/FusionInspector/FusionInspector/wiki)
        - [MAVIS](http://mavis.bcgsc.ca/)
    - Alignment viewer
        - [Chromatic](https://chromatic.nci.nih.gov/)
        - [GenomeView (java app)](https://genomeview.org/content/quick-start-guide)
        - [Gambit](http://labsergen.langebio.cinvestav.mx/bioinformatics/jacob/?p=473)
        - [LookSeq](https://www.sanger.ac.uk/tool/lookseq/)
        - [pyBamView](https://mgymrek.github.io/pybamview/)
        - [udon](https://github.com/ocxtal/udon)
    - Comparative
        - [Aequatus](https://github.com/TGAC/Aequatus)
        - [AliTV](https://alitvteam.github.io/AliTV/d3/AliTV.html)
        - [GSSPlayground](https://github.com/orangeSi/GSSplayground)
        - [Artemis comparison tool (ACT)](https://www.sanger.ac.uk/science/tools/artemis-comparison-tool-act)
        - [Biodalliance comparative demo](http://biodalliance.org/dev/test-comparative.html)
        - [Chromatiblock](https://github.com/mjsull/chromatiblock)
        - [CMap](http://gmod.org/wiki/CMap)
        - [CoGe](https://genomevolution.org/coge/)
        - [Comparative assembly hub / "snake track"](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4296145/)
        - [CrossBrowse](https://github.com/shenkers/CrossBrowse)
        - [CVit](https://sourceforge.net/projects/cvit/)
        - [Cvit.js](https://github.com/LegumeFederation/cvitjs)
        - [EasyFig](https://mjsull.github.io/Easyfig/)
        - [GBrowse_syn](http://gmod.org/wiki/GBrowse_syn)
        - [Genome Context Viewer](https://www.legumefederation.org/gcv/phytozome_10_2/)
        - [Genome-plots-processing](https://github.com/filip-husnik/genome-plots-processing)
        - [Genomicus](https://www.genomicus.biologie.ens.fr/genomicus/)
        - [gggenomes](https://github.com/thackl/gggenomes)
        - [GIVE](https://zhong-lab-ucsd.github.io/GIVE_homepage/)
        - [mauve-viewer](https://github.com/nconrad/mauve-viewer)
        - [MCScan (python version)](https://github.com/tanghaibao/jcvi/wiki/MCscan-(Python-version))
        - [MCScanX](https://github.com/wyp1125/MCScanX)
        - [mGSV (multiple genome synteny viewer)](https://github.com/kashmatic/mGSV)
        - [MizBee](http://www.cs.utah.edu/~miriah/mizbee/Overview.html)
        - [Multiple genome viewer](http://www.informatics.jax.org/mgv/)
        - [OMA local synteny browser](https://omabrowser.org/oma/synteny/ADH1A_HUMAN/)
        - [pafr](https://github.com/dwinter/pafr)
        - [Parasight](https://baileylab.brown.edu/parasight/galframe.html)
        - [syri/plotsr](https://schneebergerlab.github.io/syri/plotsr.html)
        - [progressiveMauve viewer](http://darlinglab.org/mauve/user-guide/viewer.html)
        - [SyMap](http://www.agcol.arizona.edu/software/symap/)
        - [Synima](https://github.com/rhysf/Synima)
        - [Synteny browser](https://github.com/TheJacksonLaboratory/syntenybrowser)
        - [SynTView](http://hub18.hosting.pasteur.fr/SynTView/documentation/)
        - [SynVisio](https://synvisio.github.io/)
        - [VISTA browser](http://pipeline.lbl.gov/cgi-bin/gateway2)
        - [XMatchView](https://www.bcgsc.ca/resources/software/xmatchview)
        - [LinearDisplay.pl](https://github.com/JCVenterInstitute/LinearDisplay)
        - [FastANI](https://github.com/ParBLiSS/FastANI)
        - [clinker](https://github.com/gamcil/clinker)
        - [RectChr](https://github.com/BGI-shenzhen/RectChr)
        - [pretzel](https://github.com/plantinformatics/pretzel)
        - [PipMaker](http://pipmaker.bx.psu.edu/pipmaker/)
        - [WGDI](https://github.com/SunPengChuan/wgdi)
        - [BRIG](http://brig.sourceforge.net)
        - [GENESPACE](https://github.com/jtlovell/GENESPACE/)
        - [miropeats](http://www.littlest.co.uk/software/bioinf/old_packages/miropeats/)
        - [syntenyPlotteR](https://github.com/marta-fb/syntenyPlotteR)
        - [chromoMap](https://lakshay-anand.github.io/chromoMap/index.html)
        - [SafFire](https://mrvollger.github.io/SafFire/#ref=CHM13_v1.1&query=GRCh38)
        - [SimpleSynteny](https://www.dveltri.com/simplesynteny/about.html)
        - [Cinteny](http://cinteny.cchmc.org/)
        - [AutoGraph](http://autograph.genouest.org/)
        - [EvolutionHighway](http://eh-demo.ncsa.illinois.edu/)
    - Single cell
        - [Millefy](https://github.com/yuifu/millefy)
        - [gingko](http://qb.cshl.edu/ginkgo/?q=/9EiUttUP0CBHs3WnuBa0)
        - [copykat](https://github.com/navinlabcode/copykat/blob/master/vignettes/copycat-vignettes.pdf)
        - [scCNV_heatmap](https://github.com/StefanKurtenbach/scCNV_heatmap)
        - [casper](https://github.com/akdess/CaSpER)
        - [ArchR](https://www.archrproject.com/articles/Articles/tutorial.html)
    - GWAS
        - [PureScript genetics browser](https://github.com/chfi/purescript-genetics-browser)
        - [Locuszoom](http://locuszoom.org/)
        - [LDBlockShow](https://github.com/BGI-shenzhen/LDBlockShow)
    - Dotplot
        - [shinyChromosome](http://150.109.59.144:3838/shinyChromosome/)
        - [D-GENIES](http://dgenies.toulouse.inra.fr/)
        - [Delly-maze](https://github.com/dellytools/maze)
        - [Discoplot](https://github.com/mjsull/DiscoPlot)
        - [Dot](https://dot.sandbox.bio/)
        - [Dotlet](https://dotlet.vital-it.ch/)
        - [Dotplot (chirimoyo)](https://chirimoyo.ac.uma.es/bitlab/portfolio/dotplot/)
        - [iLambda/Dotplot](https://github.com/iLambda/dotplot)
        - [dotPlotly](https://github.com/tpoorten/dotPlotly/)
        - [Dottup](https://www.bioinformatics.nl/cgi-bin/emboss/help/dottup)
        - [FlexiDot](https://github.com/molbio-dresden/flexidot)
        - [Gepard](http://cube.univie.ac.at/gepard)
        - [Jdot](https://github.com/LyonsLab/jdot)
        - [last-dotplot](https://gitlab.com/mcfrith/last)
        - [mcutils](https://github.com/mchaisso/mcutils)
        - [Minidot](https://github.com/thackl/minidot)
        - [Mummer-idotplot](https://github.com/ryought/mummer-idotplot)
        - [Mummerplot](http://mummer.sourceforge.net/)
        - [ggplot2 mummerplot](https://jmonlong.github.io/Hippocamplus/2017/09/19/mummerplots-with-ggplot2/)
        - [Redotable](https://github.com/s-andrews/redotable)
        - [syntenyPlotByR](https://github.com/shingocat/syntenyPlotByR)
        - [Dotter](https://sonnhammer.sbc.su.se/Dotter.html)
        - [JGI/IMG](https://img.jgi.doe.gov/)
        - [MashMap](https://github.com/marbl/MashMap/blob/master/scripts/generateDotPlot)
        - [oxford-plots](https://github.com/jherrero/oxford-plots)
        - [DAGchainer](http://dagchainer.sourceforge.net/)
    - Gene structure
        - [TnT](https://tnt.marlin.pub/articles/introduction)
        - [Apollo aka WebApollo](https://genomearchitect.readthedocs.io/en/latest/)
    - Microbiology
        - [Edinburgh-Genome-Foundry/DnaFeaturesViewer](https://github.com/Edinburgh-Genome-Foundry/DnaFeaturesViewer)
    - Graph
        - [AGB assembly graph browser](https://almiheenko.github.io/AGB/index.html)
        - [Bandage](https://github.com/rrwick/Bandage/)
        - [gfaestus](https://github.com/chfi/gfaestus)
        - [graphgenomeviewer](https://cmdcolin.github.io/graphgenomeviewer/)
        - [MoMi-G](https://github.com/MoMI-G/MoMI-G)
        - [odgi draw + odgi viz](https://odgi.readthedocs.io/en/latest/index.html)
        - [sequence tube map](https://github.com/vgteam/sequenceTubeMap)
        - [Shasta](https://chanzuckerberg.github.io/shasta/ComputationalMethods.html#ReadGraph)
        - [LINX](https://github.com/hartwigmedical/hmftools/blob/master/sv-linx/README_VIS.md)
        - [panGraphViewer](https://github.com/TF-Chan-Lab/panGraphViewer)
        - [IGGE](https://github.com/immersivegraphgenomeexplorer/IGGE)
    - SV
        - [gGnomes.js](https://github.com/mskilab/gGnome.js)
        - [Ribbon](http://genomeribbon.com/)
        - [Gremlin](http://compbio.cs.brown.edu/projects/gremlin/)
        - [InGAP-SV](http://ingap.sourceforge.net/)
        - [Introgression browser](https://git.wageningenur.nl/aflit001/ibrowser)
        - [SplitThreader](http://splitthreader.com/)
        - [SMRT View](http://files.pacb.com/software/smrtanalysis/2.3.0/doc/smrtview/help/Webhelp/App_View_Epipro.htm)
        - [NeoLoopFinder](https://github.com/XiaoTaoWang/NeoLoopFinder)
        - [SVPV](https://github.com/VCCRI/SVPV)
        - [AmpliconArchitect](https://github.com/virajbdeshpande/AmpliconArchitect)
    - Text based
        - [Alan](https://github.com/mpdunne/alan)
        - [Alv](https://github.com/arvestad/alv)
        - [ASCIIGenome](https://github.com/dariober/ASCIIGenome)
        - [Bamcov](https://github.com/fbreitwieser/bamcov)
        - [BLAST+](ftp://ftp.ncbi.nlm.nih.gov/blast/executables/blast+/LATEST/)
        - [Hapviz](https://github.com/ekg/hapviz)
        - [plotReads](http://campuspress.yale.edu/knightlab/ruddle/plotreads/)
        - [Rna Alignment Viewers (Colorstock, SScolor, Ratón)](http://biowiki.org/wiki/index.php?title=Rna_Alignment_Viewers&redirect=no)
        - [Sam2pairwise](https://github.com/mlafave/sam2pairwise)
        - [Samtools depth visualization](https://twitter.com/yokofakun/status/1178686978541441025)
        - [Samtools tview](http://www.htslib.org/)
        - [SvABA](https://github.com/walaj/svaba#alignmentstxtgz)
        - [VizAln (from HipSTR)](https://github.com/tfwillems/HipSTR)
    - Circular
        - [Anvio](https://peerj.com/articles/1319/)
        - [BioCircos.js](http://bioinfo.ibp.ac.cn/biocircos/)
        - [Circleator](http://jonathancrabtree.github.io/Circleator/index.html)
        - [circlize](https://github.com/jokergoo/circlize)
        - [Circos](http://circos.ca/)
        - [CircosJS](https://github.com/nicgirault/circosJS)
        - [DNAPlotter](https://www.sanger.ac.uk/science/tools/dnaplotter)
        - [GenomeProjector](https://github.com/gaou/g-language/wiki)
        - [JupiterPlot](https://github.com/JustinChu/JupiterPlot)
        - [OGDRAW](https://chlorobox.mpimp-golm.mpg.de/OGDraw.html)
        - [Gview](https://server.gview.ca/examples)
        - [RegulomeExplorer](http://explorer.cancerregulome.org/all_pairs/?dataset=TCGA_ACC)
        - [CGView](http://cgview.ca/)
    - Synthetic biology
        - [seqviz](https://github.com/Lattice-Automation/seqviz#viewer)
        - [ApE (a plasmid editor)](https://jorgensen.biology.utah.edu/wayned/ape/)
        - [Chopchop](http://chopchop.cbu.uib.no/)
    - Special-purpose
        - [Apollo](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC151184/)
        - [D3GB](http://d3gb.usal.es/)
        - [DNASkittle](https://www.dnaskittle.com/)
        - [EaSeq](https://easeq.net/screenshots/)
        - [FluentDNA](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7203487/)
        - [Gnomad browser](https://github.com/macarthur-lab/gnomadjs)
        - [IslandViewer and IslandPlot](https://bl.ocks.org/lairdm/c6c235dbfa6e6ee61565)
        - [MagicViewer](http://bioinformatics.zj.cn/magicviewer/)
        - [Panoptes](https://www.malariagen.net/apps/ag1000g/phase1-AR3/index.html)
        - [MapView](https://sites.google.com/site/wjwdavy/)
        - [NGB](https://github.com/epam/NGB)
        - [SeqCover](https://brentp.github.io/seqcover/#gene=AIFM1)
        - [SEQing](https://github.com/malewins/SEQing)
        - [SFARI](https://gene.sfari.org/database/human-gene/)
        - [Short read assembly browser](https://rapdb.dna.affrc.go.jp/AssemblyBrowser2/index.html?ref=%22chr01%22&run_id=%22G4toI1%22&start=%22234780%22&end=%22236631%22)
        - [SNPitty](https://bitbucket.org/ccbc/snpitty/src/master/)
        - [Staden](https://sourceforge.net/projects/staden/)
        - [TASUKE](https://ricegenome.dna.affrc.go.jp/)
        - [UGENE](http://ugene.net/)
        - [Varsome](https://varsome.com/security-validation/?next=/variant/hg19/NM_000088.3(COL1A1):c.658C%3ET)
        - [Vials](http://vials.io/)
        - [wasm bigwig demo browser](https://shk656461.github.io/index.html)
    - Expression
        - [GTEX Locus browser](https://gtexportal.org/home/locusBrowserPage/ACTN3)
    - Population
        - [GWAS catalog browser](https://www.ebi.ac.uk/gwas/variants/rs1558902)
        - [Human genome dating](https://human.genome.dating/region/chr1_13250000)
        - [PopSV](https://github.com/jmonlong/PopSV/blob/master/3-Visualization.md)
        - [SWAV](http://swav.popgenetics.net/)
    - Assembly QC
        - [Icarus QUAST](http://quast.sourceforge.net/icarus.html)
    - Exotic
        - [BigTop](https://blog.dnanexus.com/2019-05-21-bigtop-data-visualization/)
        - [Cylindrical alignment app](https://sourceforge.net/projects/cylindrical-alignment-app/)
        - [sockeye](https://www.bcgsc.ca/resources/software/sockeye)
        - [spinteny](https://github.com/skinner/spinteny)
    - Epigenomics
        - [Chip Monk](http://www.bioinformatics.babraham.ac.uk/projects/chipmonk/)
        - [Chipster](https://chipster.csc.fi/)
        - [cisGenome Browser](https://jhui2014.github.io/browser/screenshots.html)
        - [Epilogos](https://epilogos.altius.org/)
        - [Epiviz](https://epiviz.github.io/)
        - [HiPiler](http://hipiler.higlass.io)
        - [Juicebox](https://github.com/aidenlab/Juicebox)
        - [Juicebox.js](http://www.igv.org/doc/juiceboxjs.html)
        - [Peax](https://github.com/Novartis/peax)
    - Ideogram
        - [eweitz/Ideogram](https://github.com/eweitz/ideogram)
        - [Ideogram](https://github.com/RCollins13/HumanIdiogramLibrary)
        - [Ideoplot](https://github.com/mchaisso/Ideoplot)
        - [karyoploteR](https://github.com/bernatgel/karyoploteR)
        - [KaryotypeSVG](https://github.com/andreasprlic/karyotypeSVG)
        - [NCBI Genome Decoration](https://www.ncbi.nlm.nih.gov/genome/tools/gdp/)
        - [UCSC Genome Graphs](http://genome.ucsc.edu/cgi-bin/hgGenome)
        - [genomegraphs](http://bioconductor.org/packages/2.5/bioc/vignettes/GenomeGraphs/inst/doc/GenomeGraphs.pdf)
        - [IdeoViz](https://www.bioconductor.org/packages/release/bioc/vignettes/IdeoViz/inst/doc/Vignette.pdf)
        - [Flash Gviewer](http://gmod.org/wiki/Flashgviewer/)
        - [Ideogram viewer](https://bioinformatics.mdanderson.org/public-software/ideogramviewer/)
    - Pangenome
        - [Pan-Tetris](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4547177/)
        - [Panacaea](https://github.com/JCVenterInstitute/PanACEA)
        - [Panache](https://github.com/SouthGreenPlatform/panache)
        - [panX](http://pangenome.tuebingen.mpg.de/)
        - [RPAN (3kricedb)](http://cgm.sjtu.edu.cn/3kricedb/visualization/?tracks=DNA%2Cgene%2CPF)
        - [PGAP-X](https://pgapx.zhaopage.com/)
        - [PGV](https://github.com/ucrbioinfo/PGV)
        - [Phandango](https://jameshadfield.github.io/phandango/#/examples)
    - Protein
        - [Protael](http://sanshu.github.io/protaelweb/)
        - [ProteinPaint](https://pecan.stjude.cloud/proteinpaint)
        - [pViz](https://github.com/Genentech/pviz)
        - [Aquaria](http://aquaria.ws/Q9HD67/5i0i/A)
        - [nightingale/protvista](https://ebi-webcomponents.github.io/nightingale/#/msa)
    - Heatmap
        - [UCSC Xena](https://xena.ucsc.edu/)
        - [VIVA](https://www.biorxiv.org/content/10.1101/589879v1.full.pdf)
    - Repeats
        - [REPAVER](https://gitlab.com/gringer/bioinfscripts/)
        - [GraphAlignmentViewer](https://github.com/Illumina/GraphAlignmentViewer)
        - [REViewer](https://github.com/Illumina/REViewer)
    - Historical
        - [Internet Contig Explorer](https://www.bcgsc.ca/resources/software/ice)
    - QC
        - [ALVIS (chimeric alignment viewer)](https://github.com/SR-Martin/alvis)
        - [vcfR](https://knausb.github.io/vcfR_documentation/)
    - Methylation
        - [NanoMethViz](http://www.bioconductor.org/packages/release/bioc/html/NanoMethViz.html)
        - [AnnoJ](https://brainome.ucsd.edu/howto_annoj.html)
    - Phylogenetics
        - [Nextclade](https://clades.nextstrain.org/)
        - [Gingr](https://harvest.readthedocs.io/en/latest/content/gingr.html)
    - Uncategorized
        - [methylartist](https://github.com/adamewing/methylartist)
        - [Haploview](https://www.broadinstitute.org/haploview/haploview)
        - [Smash++](https://github.com/smortezah/smashpp)
        - [plotsr](https://github.com/schneebergerlab/plotsr)
    - Assembly
        - [vega](http://vega.archive.ensembl.org/Homo_sapiens/Location/Chromosome?r=6-QBL)
        - [MIRA](http://mira-assembler.sourceforge.net/docs/DefinitiveGuideToMIRA.html)
    - Coverage
        - [wiggleplotr](http://bioconductor.org/packages/devel/bioc/vignettes/wiggleplotr/inst/doc/wiggleplotr.html)
        - [Trackplot](https://github.com/PoisonAlien/trackplot)
    - Splicing
        - [splicejam](https://github.com/jmw86069/splicejam)
        - [Slinker](https://github.com/Oshlack/Slinker)
    - Hi-C
        - [Plotgardener](https://github.com/PhanstielLab/plotgardener/)
        - [gcMapExplorer](https://github.com/rjdkmr/gcMapExplorer)
    - Manhattan
        - [ggplot2 manhattan plot](https://danielroelfs.com/blog/how-i-create-manhattan-plots-using-ggplot/)

## Learn

## RunAndTests

## THINKS FOR 
- [awesome-genome-visualization](https://github.com/cmdcolin/)
- [Awesome-Bioinformatics](https://github.com/danielecook/Awesome-Bioinformatics)

The project welcomes any life science industry physician to add
        


## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)