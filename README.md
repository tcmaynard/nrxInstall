nrxInstall
==========

NetRexx installation configuration
----------------------------------

Find here all the ancillary files required to compile the executable JAR file containing a NetRexx distribution.

The files are:
- nrxInstall.xml
- NetRexxKingSmall.gif
- TargetPanel.dir.windows
- TargetPanel.dir.mac
- TargetPanel.dir.unix

Drop the files above into a fresh distribution (i.e. unzip the "official" package), put IzPack/bin in your PATH, and
```
compile nrxInstall.xml [-o output.jar]
```
The default behavior is to name the JAR the same as the XML.

For completeness, the resulting JAR is also included here ... but it rather wasteful since it is so easily generated
locally after cloning the files above.
