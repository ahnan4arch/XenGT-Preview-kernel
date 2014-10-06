linux-vgt.patch:
	The patch should be applied to linux-3.14.1
	git clone git://git.kernel.org/pub/scm/linux/kernel/git/stable/linux-stable.git
	git checkout -b v3.14.1 v3.14.1
	patch -p1 < linux-vgt.patch
