nrxInstall
==========

NetRexx installation configuration
----------------------------------

Find here all the ancillary files required to compile the executable JAR file containing a NetRexx distribution. The
installation uses [IzPack](http://izpack.org/).

The files are:
- nrxInstall.xml            - the installation description
- NetRexxKingSmall.gif      - the NetRexx logo (splash screen)
- TargetPanel.dir.windows   - the destination directories for each platform
- TargetPanel.dir.mac
- TargetPanel.dir.unix

Drop the files above into a fresh distribution (i.e. unzip the "official" package), put IzPack/bin in your PATH, and
```
compile nrxInstall.xml [-o output.jar -h izpack_root -b netrexx_dist]
```
The default behavior is to name the JAR the same as the XML.

For completeness, the resulting JAR is also included here ... but it is rather wasteful since it is so easily generated
locally after cloning the files above.
