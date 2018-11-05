project(class6)
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_FLAGS "-fPIC")
set(CMAKE_BUILD_TYPE Release)


include_directories("../..")


#set(SURFACE_RECONSTRUCTION_SOURCES
#        class6_surface_reconstruction.cc)
#add_executable(task6_surface_reconstruction ${SURFACE_RECONSTRUCTION_SOURCES})
#target_link_libraries(task6_surface_reconstruction mvs util core surface)

set(SURFACE_RECONSTRUCTION_SOURCES
        class6_surface_reconstruction.cc)
add_executable(qcit_surface_reconstruction ${SURFACE_RECONSTRUCTION_SOURCES})
target_link_libraries(qcit_surface_reconstruction mvs util core surface)