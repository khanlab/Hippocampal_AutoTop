Bootstrap: docker
From: khanlab/autotop_deps:v0.1

%setup
mkdir -p $SINGULARITY_ROOTFS/src
cp -Rv . $SINGULARITY_ROOTFS/src

%environment
export AUTOTOP_DIR=/src

%runscript
/src/mcr_v97/AutoTops_TransformAndRollOut.sh /opt/mcr/v97


