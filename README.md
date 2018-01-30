## Overview

This repository contains the trunk from the previous subversion (svn) repository of the Los Alamos Sea Ice Model, CICE, including release tags through version 5.1.2. 
More recent versions are found in the [CICE](https://github.com/CICE-Consortium/CICE) and [Icepack](https://github.com/CICE-Consortium/Icepack) repositories, which are now maintained on github by the CICE Consortium.  

## Obtaining an older CICE release

If you expect to make any changes to the code, we recommend that you work in the CICE and Icepack repositories.  Changes made to code in this repository will not be accepted, other than critical bug fixes.

Release tags from svn are available in this git repository and can be obtained two ways:
### Tarball
Download a tarball for a particular version. Tarballs with source code are available under [Releases](https://github.com/CICE-Consortium/CICE-svn-trunk/releases).

### Using git or svn
Checkout at the command line using git or svn commands. The pull-down list under "Branch: master" on the [CICE-svn-trunk github page](https://github.com/CICE-Consortium/CICE-svn-trunk) shows all of the available release versions.

1. Git clone the branch with just the tag of interest to you:

   git clone -b svn/tags/release-5.1.2 https://github.com/CICE-Consortium/CICE-svn-trunk CICE_v5.1.2

2. Git clone the entire repository using standard git commands:

   git clone https://github.com/CICE-Consortium/CICE-svn-trunk

3. svn checkout the branch with just the tag of interest to you:

   svn checkout https://github.com/CICE-Consortium/CICE-svn-trunk/branches/svn/tags/release-5.1.2 cice_v5.1.2   

## More information

Documentation is provided in https://github.com/CICE-Consortium/CICE-svn-trunk/cicedoc/cicedoc.pdf, including both a technical description and user guidance.
Earlier versions of this documentation, for each release, is in the [doc/](https://github.com/CICE-Consortium/CICE-svn-trunk/cice/doc/) directory within the CICE code distribution of that release.

The [wiki](https://github.com/CICE-Consortium/CICE-svn-trunk/wiki) pages contain links to additional information, e.g.    
- copyright 
- larger files such as the gx1 grid, land mask, and forcing files

The ["About-Us" repository](https://github.com/CICE-Consortium/About-Us) includes background and supporting information about the CICE Consortium, including how to interact with it.    
