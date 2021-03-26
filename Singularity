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

%runscript
