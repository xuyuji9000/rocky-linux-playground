# rocky-linux-playground

This repo is used to play with [Rocky Linux](https://github.com/rocky-linux/rocky) and understand what it takes to create a working distribution.


## Join the discussion

- [Slack](https://app.slack.com/client/T0YKGK200/C01HFJK8LFJ)

    > Use **#rocky-devel-packaging** channel for RPM(Red-hat Package Manager) related discussion.
    
    > Use `Saved Items` to glance over the interesting things

## Commands

- Extract content from `.rpm` files

    `rpm2cpio ./packagecloud-test-1.1-1.x86_64.rpm | cpio -idmv`[5]


# Reference 

1. [Koji](https://fedoraproject.org/wiki/Koji)

    > Koji is the software that builds RPM package for the Fedora project.

2. [rpm-software-management/mock](https://github.com/rpm-software-management/mock)

    > A 'simple' chroot build environment manager for building RPMs.

3. [Podcast 72: Gregory Kurtzer, Rocky Linux](https://www.youtube.com/watch?v=KAmmZ1BvLe0)

    > CentOS founder discuss about Rocky Linux


4. [RockyLinux reddit](https://www.reddit.com/r/RockyLinux/)

5. [Inspecting and extracting RPM package contents](https://blog.packagecloud.io/eng/2015/10/13/inspect-extract-contents-rpm-packages/)
