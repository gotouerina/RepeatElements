# RepeatElements

##     Prepare
    singularity pull EDTA.sif docker://quay.io/biocontainers/edta:2.2.0--hdfd78af_1
    mv EDTA.sif Repeat.sif
    perl RepeatAnnotation.pl $genome $prefix

##    Download and Help
    wget https://github.com/gotouerina/RepeatElements/releases/download/v1.0/RepeatAnnotation
    ./RepeatAnnotation $genome $prefix
