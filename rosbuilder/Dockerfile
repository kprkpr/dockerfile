FROM base/devel

RUN pacman -Syu zlib python python2 wget texinfo bzip2 --noconfirm --needed

RUN wget -nv https://github.com/kprkpr/dockerfile/raw/master/rosbuilder/RosBE-Unix-2.1.2.tar.bz2 -O RosBE-Unix-2.1.2.tar.bz2
RUN tar -xf RosBE-Unix-2.1.2.tar.bz2
RUN cd RosBE-Unix-2.1.2 && ./RosBE-Builder.sh
