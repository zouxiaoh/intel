User Guide
1.  Build environment
      Choice 1: ubuntu21.04, glibc 2.27：
                sudo apt-get install autoconf libtool linux-libc-dev
      Choice 2: Yocto board, glibc 2.27  

2.  Building libcamhal
      mkdir build
      cd build
      cmake ../
      make -j
      make package

3.  Install libcamhal



