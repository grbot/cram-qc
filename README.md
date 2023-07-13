Run samtools flagstat on a set of CRAM files. Generate a MultiQC report from the output.

To run:
```
nextflow run https://github.com/grbot/cram-qc --input "/path/*.cram"
```

or

```
nextflow run https://github.com/grbot/cram-qc --input "1.cram 2.cram 3.cram"
```
