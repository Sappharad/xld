# XLDVorbisDecoder modifications
XLD Vorbis Decoder modified to build against the 20170729 release of XLD

Note that this requires you to copy the versions of the frameworks
inside XLD to the xld_frameworks directory (not inside the repository) 
and provide header files for them in there too. Unless you build against 
the same frameworks in the release XLD binary, the plug-in will not load.
It does not like newer ones.

This probably will not work anymore the next time XLD is updated.
Checking it in here in case someone wants a head-start on fixing it next time it breaks.
