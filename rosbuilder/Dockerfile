FROM base/devel

RUN pacman -Syu zlib python python2 wget texinfo --noconfirm --needed

RUN wget https://github.com/kprkpr/dockerfile/raw/master/rosbuilder/RosBE-Unix-2.1.2.tar.bz2 -O RosBE-Unix-2.1.2.tar.bz2
RUN tar -xzf RosBE-Unix-2.1.2.tar.bz2
RUN cd RosBE-Unix-2.1.2 && 
RUN ./RosBE-Builder.sh
