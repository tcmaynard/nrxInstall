nrxInstall
==========

NetRexx installation configuration
----------------------------------

Find here all the ancillary files required to compile the executable JAR file containing a NetRexx distribution. The
installation uses [IzPack](http://izpack.org/).

The files are:
<table>
  <tr>
    <th>File</th><th>Description</th>
  </tr>
  <tr>
    <td>nrxInstall.xml</td><td>the installation description</td>
  </tf>
  <tr>
    <td>NetRexxKingSmall.gif</td><td>the NetRexx logo (splash screen)</td>
  </tr>
  <tr>
    <td>TargetPanel.dir.windows</td><td>the destination directories for each platform</td>
  </tr>
  <tr>
    <td>TargetPanel.dir.mac</td><td>(ditto)</td>
  </tr>
  <tr>
    <td>TargetPanel.dir.unix</td><td>...</td>
  </tr>
</table>

Drop the files above into a fresh distribution (i.e. unzip the "official" package), put IzPack/bin in your PATH, and
```
compile nrxInstall.xml [-o output.jar -h izpack_root -b netrexx_dist]
```
The default behavior is to name the JAR the same as the XML.

For completeness, the resulting JAR is also included here ... but it is rather wasteful since it is so easily generated
locally after cloning the files above.
