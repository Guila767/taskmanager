add_library(dllmain SHARED dllmain.cpp)
target_link_libraries(dllmain libmen Psapi gdi32 Version Shlwapi)

add_library(libmen STATIC libs/libmem/libmem/libmem.c)