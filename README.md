# Docker Fedora JDK

![](https://images.microbadger.com/badges/image/rigon/fedora-jdk.svg)

Fedora baseline docker container with Oracle JDK and RPM build tools.
The [Java](https://www.java.com/en/) version installed is `8u102`.


## Description

This image is based on the image [rigon/fedora-rpmtools](https://hub.docker.com/r/rigon/fedora-rpmtools/).

Beyond Oracle JDK, the necessary tools to build RPMs were installed, with `dnf`:

- `rpm-build`
- `rpmdevtools`

