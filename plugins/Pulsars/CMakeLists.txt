SET(PSR_MAJOR "0")
SET(PSR_MINOR "3")
SET(PSR_PATCH "1")
SET(PSR_VERSION "${PSR_MAJOR}.${PSR_MINOR}.${PSR_PATCH}")

ADD_DEFINITIONS(-DPULSARS_PLUGIN_VERSION="${PSR_VERSION}")
ADD_DEFINITIONS(-DPULSARS_PLUGIN_LICENSE="GNU GPLv2 or later")

ADD_SUBDIRECTORY( src )
