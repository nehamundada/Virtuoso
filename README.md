Virtuoso
========

This repository gives description about [virtuoso](http://virtuoso.openlinksw.com/dataspace/doc/dav/wiki/Main/VirtRDFPerformanceTuning) installations for different Operating Systems and injecting local [dbpedia](http://dbpedia.org/About) with it.


### Steps to install virtuoso with local dbpedia

Following are the 4 generic steps to install virtuoso and inject dbpedia data with it's triplestore to try out queries on dbpedia data.

1. Get the source code 
Get the virtuoso source from [github repo](https://github.com/openlink/virtuoso-opensource/) and checkout the [stable/7 branch!!](https://github.com/openlink/virtuoso-opensource/tree/stable/7) 
2. Build it.
Follow as per the instruction given below based on your Operating system.
3. Download triples from [dbpedia (all the different dumps!!)](http://wiki.dbpedia.org/Downloads39)
4. Injecting triples
[Follow the instruction to ingest the data.](http://virtuoso.openlinksw.com/dataspace/doc/dav/wiki/Main/VirtBulkRDFLoader) 

========

### List of Platform supported and tested:

[Follow this link to know more about supported platforms.](http://virtuoso.openlinksw.com/dataspace/doc/dav/wiki/Main/VOSPort) The current version of virtuoso, 32-bit builds are not possible, due to changes in the Virtuoso engine. 
For 32 bit builds you need to switch to older version 6.1.0. 
* [Follow this link for downloads of virtuoso cource code and packages.](http://virtuoso.openlinksw.com/dataspace/doc/dav/wiki/Main/VOSDownload)
* [Follow this link for knowing deplyment information of all OS. ](http://virtuoso.openlinksw.com/dataspace/doc/dav/wiki/Main/VOSBuild)

=====

## Operating system specific steps are as follows:
Installation and build process varies based on different operating systems.

### Installation process for Open source Operating Systems (Unix,Fedora,RedHat) and Mac OS X)
1. Get the virtuoso source from [github (checkout stable/7 branch!!).](https://github.com/openlink/virtuoso-opensource/tree/stable/7) 
2. [Follow the installation steps here.](http://virtuoso.openlinksw.com/dataspace/doc/dav/wiki/Main/VOSMake)

OR

You can also follow the OS specific steps for installing virtuoso

1. For CentOS: [http://virtuoso.openlinksw.com/dataspace/doc/dav/wiki/Main/VOSCentosNotes](http://virtuoso.openlinksw.com/dataspace/doc/dav/wiki/Main/VOSCentosNotes)
2. For Fedora: [http://virtuoso.openlinksw.com/dataspace/doc/dav/wiki/Main/VOSFedoraNotes](http://virtuoso.openlinksw.com/dataspace/doc/dav/wiki/Main/VOSFedoraNotes)
3. For Debian/GNU Linux: [http://virtuoso.openlinksw.com/dataspace/doc/dav/wiki/Main/VOSDebianNotes](http://virtuoso.openlinksw.com/dataspace/doc/dav/wiki/Main/VOSDebianNotes)

### Installtion process for Ubuntu 
The latest version of Virtuoso is not supported on 32 bit Ubuntu. You can install Virtuoso 6.1.0 on ubuntu directly from synaptic manager or from command line. Follow these steps and links for more details. <br/>
Step1 and step2: http://www.openlinksw.com/dataspace/doc/dav/wiki/Main/VOSUbuntuNotes

### Installtion process for Windows
Installations and build process for windows are little complicated.

1. Get the source code from : http://virtuoso.openlinksw.com/dataspace/doc/dav/wiki/Main/VOSBuild#Building for Windows
2. Build and install from the source :http://virtuoso.openlinksw.com/dataspace/doc/dav/wiki/Main/VOSMakeWindows

### Injecting Dbpedia Examples:
After following step 3 and 4 to inject dbpedia, follow this link for examples 
http://virtuoso.openlinksw.com/dataspace/doc/dav/wiki/Main/VirtBulkRDFLoaderExampleDbpedia
