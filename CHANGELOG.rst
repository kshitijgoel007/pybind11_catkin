^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package pybind11_catkin
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

2.6.1 (2022-09-29)
------------------
* Upgrade to 2.6.1
* Update version - cf. `#15 <https://github.com/kshitijgoel007/pybind11_catkin/issues/15>`_
* Increase CMake version to 3.4 for cfg_extras
* Fix installation of required files and include of required tools for macro
* Fix build (tested in install workspace)
* WIP: update to pybind11 2.6.0
* Add note that pybind11-master is broken as of July 31, 2020 for Melodic
* Update email
* Upgrade minimum required CMake version to 3.0.2. Add note on latest master being broken
* 2.5.0
* Update CHANGELOG
* Upgrade pybind11 to 2.5.0
* Upgrade Travis to include Noetic, reduce jobs
* Update package.xml to format v3
* Bump CMake version to avoid CMP0048
* Contributors: Henry Schreiner, Wolfgang Merkt

2.5.0 (2020-05-24)
------------------
* Update to v2.5.0, add compatibility with ROS Noetic (20.04) (`#12 <https://github.com/ipab-slmc/pybind11_catkin/issues/12>`_)
* Bump CMake version to avoid CMP0048. This breaks support with ROS Indigo (14.04).
* Contributors: Wolfgang Merkt

2.4.3 (2019-12-23)
------------------
* Clean-up of CMake files and logic (by @rhaschke) - `#11 <https://github.com/ipab-slmc/pybind11_catkin/issues/11>`_
* Ensure pybind11 uses same python version as catkin
* Update pybind11 version to 2.4.3
* Clarify bleeding edge vs releases in README - cf `#9 <https://github.com/ipab-slmc/pybind11_catkin/issues/9>`_
* Contributors: Robert Haschke, Wolfgang Merkt

2.2.4 (2019-01-15)
------------------
* Fixes installation of generated files
* Fix for arm-based builds
* Add dummy header to make bloom happy
* Update to v2.2.4
* Do not overwrite the exported include_dirs
  - Addresses `ros/rosdistro#18473 <https://github.com/ros/rosdistro/issues/18473>`_
* Update CMake logic to export devel/install more cleanly
* Added links to examples in readme.
* Update README.md
* Contributors: Artur Miller, Wolfgang Merkt

2.2.3 (2018-07-12)
------------------
* Adds workaround for both devel and install workspaces
* Add README with Travis Badge
* Add ROS Industrial CI
* pybind11_catkin: Do not change source directory on build
* Silence pybind11 warning
* Compatibility with 16.04 and ROS Kinetic
* pybind11 via http clone
* Added back python version override
* pybind11 >> pybind11_catkin with the submodule changed to external project
* Contributors: Vladimir Ivan, Wolfgang Merkt
