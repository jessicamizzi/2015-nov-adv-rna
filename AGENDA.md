# Agenda

## Nov 2-3, 2015.

[Workshop page](http://dib-training.readthedocs.org/en/pub/2015-11-02-mRNAseq-intermediate.html)

Starting at 9:15am, going until noon, with a coffee break;

1-3pm, individual/group consultation

## Tutorials

1. [Using Salmon to quantify RNAseq](salmon.rst)

   Salmon is one of a breed of new, very fast RNAseq counting packages.
   Like Kallisto and Sailfish, Salmon counts fragments without doing
   up-front read mapping.  Salmon can be used with edgeR and others
   to do differential expression analysis.

2. [Using Salmon to eliminate low-expressed transcripts](simplification-using-salmon.rst)

   In many assemblies - especially de novo assemblies, done without a
   reference genome - there are many transcripts that don't have significant
   expression levels.  This can interfere with quantification and annotation.
   We can use Salmon to eliminate many of these transcripts, by estimating
   their transcription levels and removing low-expressing transcripts.

3. [Using transrate to evaluate RNAseq assemblies](transrate.rst)

   How do you measure the quality of your transcriptome? In some of the
   beginner workshops, we suggested mapping your RNAseq reads back to
   the transcriptome and counting the fraction that mapped.  Transrate
   takes this kind of idea quite a bit further and measures several
   read-based metrics.

