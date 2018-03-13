Bootstrap: docker
From: centos:latest

%post
	echo "test image"

	echo "Installing Devlopment Tools YUM group"
	yum -y groupinstall "Development Tools"

	echo "installing kernel"
	yum -y install kernel kernel-devel
	
	mkdir {/volatile,/cache}
