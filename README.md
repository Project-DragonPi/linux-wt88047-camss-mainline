# WIP - Camss Support For Wt88047

* Not Working Yet . Just For Reference.
* FlashLight Can Work Perfectly!
* Only Support Ov8865(rare camera).
* i2cdetect can find ov8865 at 0x20 but return broken pipe when use it. 
* /dev/media0 can created by qcom-camss.ko normally with no problem.
* WIP front camera  + rear camera devicetree can find in msm8916-wingtech-wt88047-backup.dts 

# Kernel Readme

```
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
```

