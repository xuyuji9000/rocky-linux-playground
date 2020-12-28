# Introduction

An example of installing from SRPM.

> Through this example to practice and deepen the understanding of how this RPM(RPM package management system) works.

## Steps

1. Get [source](https://nginx.org/packages/centos/8/SRPMS/)

    Get nginx **SRPM** for **Centos 8**

2. Extract content from `.rpm` files

    `rpm2cpio ./packagecloud-test-1.1-1.x86_64.rpm | cpio -idmv`[1]

3. Prepare RPM build commands

    `yum install rpm-build`


# Reference

1. [Inspecting and extracting RPM package contents](https://blog.packagecloud.io/eng/2015/10/13/inspect-extract-contents-rpm-packages/)

2. [Set Up an RPM Build Environment under CentOS](https://wiki.centos.org/HowTos/SetupRpmBuildEnvironment)

3. [How to unpack, modify, rebuild and install a SRPM](https://unix.stackexchange.com/questions/16904/how-to-unpack-modify-rebuild-and-install-a-srpm#answer-16909)

    > Get steps of how to build binary RPM from SRPM here.
