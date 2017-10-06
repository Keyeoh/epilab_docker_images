FROM keyeoh/totoro_bioc

MAINTAINER Gustavo F. Bayon <fernandezgustavo@uniovi.es>

RUN apt-get install -y libcurl4-openssl-dev xorg-dev libglu1-mesa-dev \
  libxml2-dev

RUN Rscript -e "source('http://bioconductor.org/biocLite.R')" \
  -e "biocLite(c(\
    'GenomicRanges'\
    ), ask = FALSE)"


# RUN Rscript -e "source('http://bioconductor.org/biocLite.R')" \
#   -e "biocLite('readr', ask = FALSE)"
# 

# RUN Rscript -e "source('http://bioconductor.org/biocLite.R')" \
#   -e "biocLite('minfi', ask = FALSE)"
# RUN Rscript -e "source('http://bioconductor.org/biocLite.R')" \
#   -e "biocLite('IlluminaHumanMethylation450kmanifest', ask = FALSE)"
# RUN Rscript -e "source('http://bioconductor.org/biocLite.R')" \
#   -e "biocLite('FDb.InfiniumMethylation.hg19', ask = FALSE)"
# RUN Rscript -e "source('http://bioconductor.org/biocLite.R')" \
#   -e "biocLite('TxDb.Hsapiens.UCSC.hg19.knownGene', ask = FALSE)"
# RUN Rscript -e "source('http://bioconductor.org/biocLite.R')" \
#   -e "biocLite('org.Hs.eg.db', ask = FALSE)"
# RUN Rscript -e "source('http://bioconductor.org/biocLite.R')" \
#   -e "biocLite('statmod', ask = FALSE)"
# RUN Rscript -e "source('http://bioconductor.org/biocLite.R')" \
#   -e "biocLite('graph', ask = FALSE)"
# RUN Rscript -e "source('http://bioconductor.org/biocLite.R')" \
#   -e "biocLite('RBGL', ask = FALSE)"
# RUN Rscript -e "source('http://bioconductor.org/biocLite.R')" \
#   -e "biocLite('gtools', ask = FALSE)"
# 

# 
# RUN Rscript -e "source('http://bioconductor.org/biocLite.R')" \
#   -e "biocLite('ggplot2', ask = FALSE)"
# RUN Rscript -e "source('http://bioconductor.org/biocLite.R')" \
#   -e "biocLite('BSgenome.Hsapiens.UCSC.hg19', ask = FALSE)"
# RUN Rscript -e "source('http://bioconductor.org/biocLite.R')" \
#   -e "biocLite('effsize', ask = FALSE)"
# RUN Rscript -e "source('http://bioconductor.org/biocLite.R')" \
#   -e "biocLite('functional', ask = FALSE)"
# RUN Rscript -e "source('http://bioconductor.org/biocLite.R')" \
#   -e "biocLite('gridExtra', ask = FALSE)"
# RUN Rscript -e "source('http://bioconductor.org/biocLite.R')" \
#   -e "biocLite('reshape2', ask = FALSE)"
# 
# COPY epilab_0.5.2.tar.gz /
# RUN R CMD INSTALL epilab_0.5.2.tar.gz
# 
# 
# RUN Rscript -e "source('http://bioconductor.org/biocLite.R')" \
#   -e "biocLite('gplots', ask = FALSE)"
# RUN Rscript -e "source('http://bioconductor.org/biocLite.R')" \
#   -e "biocLite('topGO', ask = FALSE)"  

# RUN curl http://download.r-forge.r-project.org/src/contrib/Vennerable_3.0.tar.gz\
#   > Vennerable_3.0.tar.gz
# RUN R CMD INSTALL Vennerable_3.0.tar.gz
#   
# RUN apt-get install -y openjdk-7-jdk openjdk-7-jre  
# RUN Rscript -e "source('http://bioconductor.org/biocLite.R')" \
#   -e "biocLite('xlsx', ask = FALSE)"  
#   
# WORKDIR /exosomas
# 
# 
# 
