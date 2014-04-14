Virtuoso
========

This repository gives description about virtuoso installations for different Operating Systems and injecting local dpedia with it.

Steps to install virtuoso with local dbpedia
========
Following are the 4 generic steps to install virtuoso and inject dbpedia data with it's triplestore to try out queries on dbpedia data.

step1: Get the source code 
get the virtuoso source from github (checkout stable/7 branch!!): https://github.com/openlink/virtuoso-opensource/
step2: Build it 
Follow as per the instruction given below based on your Operating system
step3: download triples
download dbpedia (all the different dumps!!): http://wiki.dbpedia.org/Downloads39
step4: Injecting triples
ingest the data using this: http://virtuoso.openlinksw.com/dataspace/doc/dav/wiki/Main/VirtBulkRDFLoader

List of Platform supported and tested:
========
Follow this link to know more :http://virtuoso.openlinksw.com/dataspace/doc/dav/wiki/Main/VOSPort

The current version of virtuoso, 32-bit builds are not possible, due to changes in the Virtuoso engine. For 32 bit builds you to switch to older version 6.1.0.
Follow this link for downloads of virtuoso cource code and packages:
http://virtuoso.openlinksw.com/dataspace/doc/dav/wiki/Main/VOSDownload
Follow this link for knowing deplyment information of all OS:
http://virtuoso.openlinksw.com/dataspace/doc/dav/wiki/Main/VOSBuild

It's easier to follow operating system specific steps as follows:

Installtion process for Open source Operating Systems
========
Installation and build process varies based on different operating systems.
for Open source Operating Systems(Unix,Fedora,RedHat) and Mac OS X follow following steps and links:
step1: get the virtuoso source from github (checkout stable/7 branch!!): https://github.com/openlink/virtuoso-opensource/
step2: install from source: http://virtuoso.openlinksw.com/dataspace/doc/dav/wiki/Main/VOSMake
  OR
You can also follow the OS specific steps for installing virtuoso
1)For CentOS: http://virtuoso.openlinksw.com/dataspace/doc/dav/wiki/Main/VOSCentosNotes
2)For Fedora: http://virtuoso.openlinksw.com/dataspace/doc/dav/wiki/Main/VOSFedoraNotes
3)For Debian/GNU Linux :http://virtuoso.openlinksw.com/dataspace/doc/dav/wiki/Main/VOSDebianNotes

Installtion process for Ubuntu 
========
The latest version of Virtuoso is not supported on 32 bit Ubuntu. You can install Virtuoso 6.1.0 on ubuntu directly from synaptic manager or from command line. Follow these steps and links for more details :
Step1 and step2: http://www.openlinksw.com/dataspace/doc/dav/wiki/Main/VOSUbuntuNotes

Installtion process for Windows
========
Installations and build process for windows are little complicated.
Step1: Get the source code from : http://virtuoso.openlinksw.com/dataspace/doc/dav/wiki/Main/VOSBuild#Building for Windows
Step2: build and install from the source :http://virtuoso.openlinksw.com/dataspace/doc/dav/wiki/Main/VOSMakeWindows

Injecting Dbpedia Examples:
========
After following step 3 and 4 to inject dbpedia, follow this link for examples 
http://virtuoso.openlinksw.com/dataspace/doc/dav/wiki/Main/VirtBulkRDFLoaderExampleDbpedia
