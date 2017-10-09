This file goal is to have a modification to commit in order to trigger Travis-CI

20171006: First try with original source from master. 
	Add comment in util/install.sh/of13() :
    	\# Normally this should not work because the netbee should come from:
    	\# git clone https://github.com/netgroup-polito/netbee.git
	Build #5 passed

20171009: Second try because build job for install_of13 branch fails
	although the difference between branches are only in of13() function
	which is not called in the .travis.yaml
