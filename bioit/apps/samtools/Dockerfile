FROM outlierbio/bioit

RUN yum install -y ncurses ncurses-devel zlib-devel

# Install samtools
ADD https://github.com/samtools/samtools/releases/download/1.3/samtools-1.3.tar.bz2 /
RUN tar xvjf samtools-1.3.tar.bz2 && \
  cd /samtools-1.3 && \
  make && \
  mv /samtools-1.3/samtools /usr/local/bin/

