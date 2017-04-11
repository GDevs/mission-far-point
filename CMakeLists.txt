add_executable(mission_farpoint main.cpp)

# ogre
# specify which version you need
find_package(OGRE 1.10 REQUIRED)
# the search paths
include_directories(${OGRE_INCLUDE_DIRS})
link_directories(${OGRE_LIBRARY_DIRS})
