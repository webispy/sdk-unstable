[![Build Ubuntu](https://github.com/webispy/sdk-unstable/workflows/Build%20Ubuntu/badge.svg)]((https://github.com/webispy/sdk-unstable/actions?query=workflow%3A%22Build+Ubuntu%22)) [![Build Allwinner](https://github.com/webispy/sdk-unstable/workflows/Build%20Allwinner/badge.svg)]((https://github.com/webispy/sdk-unstable/actions?query=workflow%3A%22Build+Allwinner%22))

# NUGU SDK for Linux unstable repository

Unstable release page: <https://webispy.github.io/sdk-unstable/>

Unstable API document: <https://webispy.github.io/sdk-unstable/doxygen/>

## Usage

Add NUGU SDK for Linux PPA:

    sudo add-apt-repository ppa:nugulinux/sdk

Create a `/etc/apt/sources.list.d/nugu-unstable.list` file with following content.

Ubuntu 16.04:

    deb [trusted=yes] https://webispy.github.io/sdk-unstable/ubuntu/ xenial main

Ubuntu 18.04:

    deb [trusted=yes] https://webispy.github.io/sdk-unstable/ubuntu/ bionic main

Update the package information

    sudo apt-get update
