^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package map_tools
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

1.8.0 (2018-08-31)
------------------
* [Fix] Moved C++11 flag to autoware_build_flags (`#1395 <https://github.com/CPFL/Autoware/pull/1395>`_)
* [Feature] Makes sure that all binaries have their dependencies linked (`#1385 <https://github.com/CPFL/Autoware/pull/1385>`_)
* [Fix] Extend and Update interface.yaml (`#1291 <https://github.com/CPFL/Autoware/pull/1291>`_)
* Feature/pcd grid divider (`#1271 <https://github.com/CPFL/Autoware/pull/1271>`_)
  * PCD Grid Divider added.
  * Clang format applied.
  * README added
  * Missing dependencies added.
  Unnecessary header removed.
  * Added CMake missing commands for installation on map_tools package
  * removed launch files installation for map_tools
* Contributors: Esteve Fernandez, Kenji Funaoka, Yuki Kitsukawa

1.7.0 (2018-05-18)
------------------
* update Version from 1.6.3 to 1.7.0 in package.xml and CHANGELOG.rst
* Contributors: Kosuke Murakami

1.6.3 (2018-03-06)
------------------

1.6.2 (2018-02-27)
------------------
* Update CHANGELOG
* Contributors: Yusuke FUJII

1.6.1 (2018-01-20)
------------------
* update CHANGELOG
* Contributors: Yusuke FUJII

1.6.0 (2017-12-11)
------------------
* Prepare release for 1.6.0
* use header.frame_id included in initialpose topic
* bug fix on output filename.
* fix compile error in map_extender.
* Contributors: Yamato ANDO, yukikitsukawa

1.5.1 (2017-09-25)
------------------
* Release/1.5.1 (`#816 <https://github.com/cpfl/autoware/issues/816>`_)
  * fix a build error by gcc version
  * fix build error for older indigo version
  * update changelog for v1.5.1
  * 1.5.1
* fix compile error in map_extender.
* Contributors: Yusuke FUJII, yukikitsukawa

1.5.0 (2017-09-21)
------------------
* Update changelog
* add map_extender
* Contributors: Yusuke FUJII, yukikitsukawa

1.4.0 (2017-08-04)
------------------
* version number must equal current release number so we can start releasing in the future
* added changelogs
* Contributors: Dejan Pangercic

1.3.1 (2017-07-16)
------------------

1.3.0 (2017-07-14)
------------------

1.2.0 (2017-06-07)
------------------
* add pcd2csv
* Contributors: yukikitsukawa

1.1.2 (2017-02-27 23:10)
------------------------

1.1.1 (2017-02-27 22:25)
------------------------

1.1.0 (2017-02-24)
------------------
* pcd_binarizer supports PointXYZ, PointXYZI and PointXYZRGB
* pcd_filter supports PointXYZ, PointXYZI and PointXYZRGB
* Contributors: yukikitsukawa

1.0.1 (2017-01-14)
------------------

1.0.0 (2016-12-22)
------------------
* Add pcd_converter.
* Output filtered PCD in Binary.
* add map_tools/pcd_arealist
* Add module graph tool
* Add map_tools.
* Contributors: USUDA Hisashi, kondoh, yukikitsukawa
