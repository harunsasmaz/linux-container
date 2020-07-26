# Linux Container

## Dependencies

* [libcap](https://man7.org/linux/man-pages/man3/libcap.3.html)
  * sudo apt-get install libcap-dev
* [seccomp](https://man7.org/linux/man-pages/man2/seccomp.2.html)
  * sudo apt-get install -y seccomp & sudo apt-get install libseccomp-dev

## Environment && Compiling

Environment:

> Linux Ubuntu 18.04 LTS

Compile:

> gcc -Wall -Werror -lcap -lseccomp container.c -o container
