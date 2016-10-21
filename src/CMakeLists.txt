add_library(physfs++ SHARED physfs.cpp)
add_library(physfs++-static STATIC physfs.cpp)
target_link_libraries(physfs++ physfs)
target_link_libraries(physfs++-static physfs)
