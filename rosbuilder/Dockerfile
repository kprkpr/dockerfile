FROM base/devel

RUN pacman -Syu zlib python python2 wget texinfo --noconfirm --needed

RUN wget https://svn.reactos.org/amine/RosBEBinFull.tar.gz -O RosBE.tar.gz
RUN tar -xzf RosBE.tar.gz
RUN cd RosBE-Unix-2.1.2 && 
RUN ./RosBE-Builder.sh
