cmake_minimum_required(VERSION 3.10.2 FATAL_ERROR)
project(ignition-find_all VERSION 0.1.0)
find_package(ignition-cmake2 REQUIRED)
ign_configure_project()

ign_find_package(GTS PRETTY gts REQUIRED)

ign_configure_build(QUIT_IF_BUILD_ERRORS)
