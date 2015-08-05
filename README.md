Repository for Dockerfile.

Dockerfile is:
* build on latest 'centos' (FROM centos maintainer)
* upgrades (no effect - needs to be checked)
* adds wget (not needed?)
* installs latest Java (Java8u51 build 16)
* sets up alternatives for
	* jar
	* java
	* javaws
	* javac
