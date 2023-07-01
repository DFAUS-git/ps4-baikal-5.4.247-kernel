How to compile this kernel?

git clone https://github.com/DFAUS-git/ps4-baikal-5.4.247-kernel
Move to the root directory of the kernel source by 'cd ps4-baikal-5.4.247-kernel'
.config is already in the kernel source root directory
make -j9 to compile on playstation 4 linux
bzImage located in 'arch/x86/boot/bzImage'

Linux kernel
============

There are several guides for kernel developers and users. These guides can
be rendered in a number of formats, like HTML and PDF. Please read
Documentation/admin-guide/README.rst first.

In order to build the documentation, use ``make htmldocs`` or
``make pdfdocs``.  The formatted documentation can also be read online at:

    https://www.kernel.org/doc/html/latest/

There are various text files in the Documentation/ subdirectory,
several of them using the Restructured Text markup notation.

Please read the Documentation/process/changes.rst file, as it contains the
requirements for building and running the kernel, and information about
the problems which may result by upgrading your kernel.
