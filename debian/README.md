### Context

This is a (re)package of Bird2 Debian/Ubuntu package, tailored to Exoscale needs.
Check debian/changelog for details.

### How to 

- check Ubuntu package versions:

  ```
  ➜ rmadison bird2

  bird2 | 2.0.7-2~ubuntu18.04.1 | bionic-backports/universe | source, amd64, arm64, armhf, i386, ppc64el
  bird2 | 2.0.7-2               | focal/universe            | source, amd64, arm64, armhf, ppc64el, riscv64
  bird2 | 2.0.8-2               | jammy/universe            | source, amd64, arm64, armhf, ppc64el, riscv64, s390x
  bird2 | 2.0.10-2              | kinetic/universe          | source, amd64, arm64, armhf, ppc64el, riscv64, s390x
  bird2 | 2.0.10-2              | lunar/universe            | source, amd64, arm64, armhf, ppc64el, riscv64, s390x
  ```

- fetch upstream tarball:

  Assuming we want to (re)package 2.0.8-2:

  ```
  ➜ uscan --download-version 2.0.8  --destdir .

  uscan: Newest version of bird2 on remote site is 2.0.8, specified download version is 2.0.8
  uscan warn: Missing debian/source/format, switch compression to gzip
  Successfully symlinked bird-2.0.8.tar.gz to bird2_2.0.8.orig.tar.gz.
  ```
