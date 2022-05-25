Squashfs-Tools Version
======================

The patches contained in this directory were built against squashfs tools v4.3, available on [Sourceforge](http://sourceforge.net/projects/squashfs/files/).

Modified Files
==============

The following files have been modified from their original version:
 
 * compressor.c
 * compressor.h
 * error.h
 * lzma_wrapper.c
 * Makefile
 * process_fragments.c
 * read_fs.c
 * squashfs_fs.h
 * unsquashfs.c
 * LZMA/lzmalt/WindowOut.h
 * LZMA/lzmalt/LZMADecoder.c
 * LZMA/lzmadaptive/C/7zip/Compress/LZMA_Lib/ZLib.cpp
 * LZMA/lzmadaptive/C/7zip/Compress/LZMA_Lib/lzmadaptive.h
 
 * patch1 (Raxone)
 
 * repatch unsquashfs.c (ubuntu 22.04 Fix "-Werror=misleading-indentation" "if(swap)")
 * Change build.sh (ubuntu 22.04 Fix error.h:34 "multiple definition of `verbose'" )
