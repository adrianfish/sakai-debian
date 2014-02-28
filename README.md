Sakai Debian
===========

A debian package build for Sakai.

Build your Sakai source into this directory using the maven.tomcat.home
directive. Modify the debian/control file so you don't depend on the
'sakai-tomcat' package, modify the debian/install file so your Sakai artefacts
go into the right place, update debian/changelog to reflect the new version,
then run:

debuild --no-lintian -us -uc

Sakai's .deb file will be be built into the directory above this one.
