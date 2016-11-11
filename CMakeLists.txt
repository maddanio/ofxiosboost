cmake_minimum_required(VERSION 3.2)

#cpm
set(CPM_MODULE_NAME "ofxiOSBoost")
CPM_ExportAdditionalLibraryTarget(libs/boost/ios/libboost.a)
CPM_ExportAdditionalIncludeDir(libs/boost/include/)
include(cpm_bootstrap.cmake)

CPM_InitModule(${CPM_MODULE_NAME})
