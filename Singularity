Bootstrap: docker
From: centos:latest

%post

	echo "Installing Devlopment Tools YUM group"
	yum -y groupinstall "Development Tools"

	echo "installing kernel"
	yum -y install kernel kernel-devel
	
	echo "force installing of bash"
	yum -y install bash
	
	mkdir {/volatile,/cache}
