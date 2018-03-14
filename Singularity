Bootstrap: docker
From: centos:latest

%help
This is a test container using the latest version of centos.  Its purpose is just to perform basic tests of the singularity installation.

%post
	echo "test image"

	echo "Installing Devlopment Tools YUM group"
	yum -y groupinstall "Development Tools"

	echo "installing kernel"
	yum -y install kernel kernel-devel
	
	mkdir {/volatile,/cache}
