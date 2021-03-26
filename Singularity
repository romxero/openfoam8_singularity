Bootstrap: docker
From: openfoam/openfoam8-paraview56
%labels
Author "Randall Cab White - rcwhite@stanford.edu"


#########
#%setup
#########

#Downlaod packages
%post

%environment
export IMAGE_NAME="openfoam8"
export FOAM_INST_DIR=/opt
export WM_PROJECT_INST_DIR=$FOAM_INST_DIR
export WM_PROJECT_DIR=$WM_PROJECT_INST_DIR/openfoam8
. /opt/openfoam8/etc/bashrc
export PATH=/opt/ThirdParty-8/platforms/linux64Gcc/gperftools-svn/bin:/opt/paraviewopenfoam56/bin:/opt/site/8/platforms/linux64GccDPInt32Opt/bin:/opt/openfoam8/platforms/linux64GccDPInt32Opt/bin:/opt/openfoam8/bin:/opt/openfoam8/wmake:$PATH
export LD_LIBRARY_PATH=/opt/ThirdParty-8/platforms/linux64Gcc/gperftools-svn/lib:/opt/openfoam8/platforms/linux64GccDPInt32Opt/lib/paraview-5.6:/opt/paraviewopenfoam56/lib:/opt/openfoam8/platforms/linux64GccDPInt32Opt/lib/openmpi-system:/opt/ThirdParty-8/platforms/linux64GccDPInt32/lib/openmpi-system:/usr/lib/x86_64-linux-gnu/openmpi/lib:/opt/site/8/platforms/linux64GccDPInt32Opt/lib:/opt/openfoam8/platforms/linux64GccDPInt32Opt/lib:/opt/ThirdParty-8/platforms/linux64GccDPInt32/lib:/opt/openfoam8/platforms/linux64GccDPInt32Opt/lib/dummy:$LD_LIBRARY_PATH
%runscript
