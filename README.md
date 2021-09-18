# WIP - Camss Support For Wt88047

* Not Working Yet . Just For Reference.
* FlashLight Can Work Perfectly!
* Only Support Ov8865(rare camera).
* i2cdetect can find ov8865 at 0x20 but return broken pipe when use it. 
* /dev/media0 can created by qcom-camss.ko normally with no problem.
* WIP front camera  + rear camera devicetree can find in msm8916-wingtech-wt88047-backup.dts 

# note

* Leaked UserSpace Driver For Android (libmmcamera) 

  ​		[libmmcamera_ov8865_q8v18a.so](https://github.com/zoggn/proprietary_qcom_mm-camera/blob/master/mm-camera2/media-controller/modules/sensors/sensor_libs/ov8865_q8v18a/ov8865_q8v18a_lib.c)

  ​		[libmmcamera_ov2680_skuhf.so](https://github.com/zoggn/proprietary_qcom_mm-camera/blob/master/mm-camera2/media-controller/modules/sensors/sensor_libs/ov2680_skuhf/ov2680_skuhf_lib.c)

  ​		[libmmcamera_ov2680_5987fhq.so](https://github.com/zoggn/proprietary_qcom_mm-camera/blob/master/mm-camera2/media-controller/modules/sensors/sensor_libs/ov2680_5987fhq/ov2680_5987fhq_lib.c)

  ​        [libmmcamera_sunny_q8v18a_eeprom.so](https://github.com/zoggn/proprietary_qcom_mm-camera/blob/master/mm-camera2/media-controller/modules/sensors/eeprom_libs/sunny_q8v18a/sunny_q8v18a_eeprom.c)

  ​	

* Camera Dtsi In downsteam kernel

  ​        [msm8916-camera-sensor-wt88047.dtsi](https://github.com/dev-elixir/hx_wt88047/blob/master/arch/arm/boot/dts/qcom/wt88047/msm8916-camera-sensor-wt88047.dtsi)

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

